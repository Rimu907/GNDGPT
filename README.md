
<h3>Vercel自动部署</h3>
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa%2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web)
<h3>Docker部署</h3>
~~~
构建镜像: docker build myapp:v1 .
启动：docker run -d -p 3000:3000 -e OPENAI_API_KEY="your key" -e CODE="ur pwd" myapp:v1
~~~
<h3>本地部署</h3>
create a new `.env.local` file at project root:
```
OPENAI_API_KEY="your key"
```
~~~
yarn install
yarn dev
~~~
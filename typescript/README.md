tsc 编译的时候如果报错就用如下命令，因为我想的是esnext(6等)的js，import语法全部是

> tsc --target EsNext --esModuleInterop --moduleResolution node

然后pm2就可以直接淦了，直接pm2 start xxx.ts没搞定，pm2启动的时候是

> pm2 start xx.js -n [name] -w
>
> pm2 stop <id1> [id2]
>
> pm2 restart  <id1> [id2]
>
> pm2 delete <id1> [id2]
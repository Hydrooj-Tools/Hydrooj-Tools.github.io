## 卸载方式
### 常规模式
若您使用一键脚本部署，请使用以下脚本  
```bash
hydrooj addon remove hydrooj_pastebin
yarn global remove hydrooj_pastebin
pm2 restart hydrooj
```  
### 开发环境模式
若您使用开发模式部署，请**在安装Hydro的目录中**使用以下脚本
```bash
npx hydrooj addon remove hydrooj_pastebin
yarn remove hydrooj_pastebin
```
然后手动重启Hydro
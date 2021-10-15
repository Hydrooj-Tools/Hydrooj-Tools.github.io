## 安装方式
!> 在安装前请完成Hydro安装并保证HydroWeb端可正常访问！
### 常规模式
若您使用一键脚本部署，请使用以下脚本  
```bash
yarn global add hydrooj_pastebin
hydrooj addon add hydrooj_pastebin
pm2 restart hydrooj
```  
### 开发环境模式
若您使用开发模式部署，请**在安装Hydro的目录中**使用以下脚本
```bash
yarn add hydrooj_pastebin
npx hydrooj addon add hydrooj_pastebin
```
然后手动重启Hydro
## 更新方式
### 常规模式
若您使用一键脚本部署，请使用以下脚本  
```bash
yarn global upgrade-interactive --latest # 在交互式界面中选择想要更新的组件
pm2 restart hydrooj
```  
### 开发环境模式
若您使用开发模式部署，请**在安装Hydro的目录中**使用以下脚本
```bash
yarn remove hydrooj_pastebin
yarn add hydrooj_pastebin
```
然后手动重启Hydro
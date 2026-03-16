# game

git add .
git commit -m "update game"
git push origin main


https://yx27508.github.io/game/


# Ultimate Fighter (Web Game)

live-server


GitHub Pages 在线版本：

https://yx27508.github.io/game/

---

# 本地开发

## 1 启动本地服务器

推荐使用 live-server（自动刷新浏览器）。

安装：

npm install -g live-server

启动：

live-server

浏览器会自动打开：

http://127.0.0.1:8080

修改代码后浏览器会自动刷新。

---

## 2 使用 Python 服务器（备用）

如果没有 Node.js，可以使用 Python：

python3 -m http.server 8000

然后打开：

http://localhost:8000

---

# 发布到 GitHub Pages

本地测试完成后运行：

git add .
git commit -m "update game"
git push origin main

GitHub Pages 会自动部署。

网站地址：

https://yx27508.github.io/game/

---

# 项目结构

game/

index.html        游戏主程序  
README.md         项目说明  
.gitignore        Git 忽略文件  

---

# 控制方式

P1  
W 跳跃  
A / D 移动  
Space 攻击  

P2  
↑ 跳跃  
← → 移动  
Enter 攻击  

---

# 开发流程

修改代码

↓  

本地运行

live-server

↓  

测试完成

git add .
git commit -m "update"
git push origin main

↓  

GitHub Pages 自动更新
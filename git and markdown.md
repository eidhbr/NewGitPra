## Git操作

---
### 配置：

+ **配置提交作者**：  
	- git config --global user.name "username"	配置姓名  
	- git config --global user.email "email"		配置email地址

- **禁用换行符自动转换**：  
	- git config --global core.autocrlf false

---
### 从零开发，先创建远程库，然后克隆远程库：  
- **git clone url 本地库名**  

+ **检查本地仓库文件状态：**  
	- git status

- **暂存文件，建立跟踪：**  
	- git add 具体文件  
	- git add .

+ **提交一个版本到本地仓库：**  
	- git commit -m "commit info"

- **将本地仓库的提交推送到远程仓库：**  
	- git push 远程仓库origin 远程分支master

---
### 解决版本冲突，拉取远程库的版本，合并到本地库  
- **git pull 远程仓库origin 远程分支master**

---
### 对于本地已有的代码，初始化库:** 
+ **git init**  

- **添加远程库：**  
	1. git remote add origin 远程库的url
	2. git pull origin master  
	5. git add 文件 ：建立追踪  
	7. git commit -m "..."  
	4. git push -u origin master ：-u关联远程库

# markdown规范

> 一个块  
>> 块中块  

```java
public class A {
	public static void main(String[] args) {
		System.out.println("java代码块");
	}
}
```
[超链接文字](https://www.baidu.com/ "百度")  
![图片未正常显示时显示这些文字](https://s.cn.bing.net/th?id=OJ.zMppy8OaHdS41A&w=75&h=75&pid=MSNJVFeeds "鼠标瞄上时显示,上同")











# Python Flask Web 开发入门与项目实战
## 1-开发环境安装配置
### 1.1-安装Python(略)
### 1.2-安装virtualenv
为什么要安装virtualenv？
不同的应用可能使用的Python版本不同，为了使Python多版本共存，需要virtualenv创建隔绝的Python环境，是每个应用各自拥有一套独立的Python运行环境。
安装命令 pip3 install virtualenv
### 1.3-为工程创建一个虚拟环境
cd F:\MyWorkingProjects\Flask
virtualenv venv

* If different verions of Python installed on computer, use below command to set the environment for the projet
virtualenv-p C:\Python37\python.exe venv


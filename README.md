# Python Flask Web 开发入门与项目实战
## 1-开发环境安装配置
### 1.1-安装Python(略)
### 1.2-安装virtualenv
为什么要安装virtualenv？
不同的应用可能使用的Python版本不同，为了使Python多版本共存，需要virtualenv创建隔绝的Python环境，是每个应用各自拥有一套独立的Python运行环境。
安装命令 pip3 install virtualenv
### 1.3-Setup a virtual environment for the new project
cd F:\MyWorkingProjects\Flask
virtualenv venv

#### If different verions of Python installed on computer, use below command to set the environment for the projet
virtualenv-p C:\Python37\python.exe venv

#### -p parameter designate the path to Python
#### To enable the virtual environment
cd F:\MyWorkingProjects\Flask\venv\Scripts
activate
#### To disable the virtual environment
desactive
#### To delete the virtual environment
rmvirtualenv Flask
#### To view 3rd party library installed inside the virtual environment
pip list
### 1.3-Install PyCharm (skipped)
#### Create a new Flask project in PyCharm
File > New Project > Choose Flask
#### Set default code as UTF-8
File > Settings
Editor > File and Code Tempaltes
Python Script
Adding this line:
#encoding:utf-8
Restart PyCharm after saving
#### Using existing virtual environment in PyCharm


https://www.zhihu.com/pub/reader/119627099/chapter/1139498000626962432




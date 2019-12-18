# 项目结构
* frontend
* backend
  * IdentifyModel.py
  * ImgModel.py
  * Localserver.py
  * main.py
  * test.py
  
# 环境配置

## 前端
  * 安装node.js
  * 安装react

## 后端
* 安装python3
* >pip install tornado
* >pip install numpy
* >pip install tkinter //tkinter只在自己测试时使用
* 程序中需要的其他包都是python3自带的，如果使用Anaconda3进行包管理，在那么上面的tornado、numpy、tkinter都已经装好了


# 运行
## 前端
  * >cd front
  * >npm install
  * >npm start
  
## 后端
 * 在验证自己的模型时，输入
 * >cd backend
 * >python3 test.py
 * 在test.py中编写了（简陋的）GUI界面用来测试，所以测试时不需要运行前端

 * 在与前端联调时，输入
 * >cd backend
 * >python3 main.py
 * 在main.py中编写了本地服务器与前端交互

# 编程
需要完成的函数是IdentifyModel.py的identify，为了测试方便，这个函数有两个返回值，一个是outputPilImage，在测试模块中，显示的图片是这个函数返回的图片，一个是List，list里面是标记数据，格式为(node1, node2, form)，在运行时会把list print到命令行中

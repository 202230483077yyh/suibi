1.创建虚拟环境
python -m venv 虚拟环境名字

2.激活虚拟环境
windows平台：
cd 虚拟环境名字
cd  Scripts
.\activate

linux平台
cd 虚拟环境名字
cd  Scripts
source activate

3.切换到虚拟环境下并不意味着虚拟的解释器启用，目前只是在配置虚拟解释器
pip install 
pip search 包名     可以获取各个版本号

pip show 包名       可以获取当前下载的包信息

4.配置好虚拟环境的解释器后，可以启动解释器了
先添加
左上角->文件->设置->项目->python解释器->添加解释器->选择现有->选择虚拟环境路径->确定

再应用
点击右下角切换当前解释器


主要用于：解决包版本不同步问题
问题体现：属性缺失，接口依赖已经废弃


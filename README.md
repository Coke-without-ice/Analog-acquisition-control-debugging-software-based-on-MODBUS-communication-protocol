

# A GUI For Analog acquisition control by PyQt5

模拟量采集控制模块调试软件

### How to Run

- `python=<3.9`
- Install all required modules
- python main.py

必须安装全部的库

否则期待的画面将不会出现

!!The corresponding version of the library must be installed
!!Otherwise, the following error will appear: not enough values to unpack (expected 5, got 4)

## Notice

这是作者第一款作品即第一次开源，可能会存在文件存储混乱，代码杂乱的问题，请多谅解

PyQt5只支持到python3.9且部分代码需要python3.0以上才能运行，如果你的版本大于3.9小于3.0版本可以使用Anaconda创造一个合适的环境

推荐使用pycharm运行，确保qtdesigner.exe文件能被识别到，请提前添加到工具里

在调试运行时应先设置数据报警参数，以免频繁激发弹窗报警提醒

上位机与下位机的串口设置应一致，确保能正常接收，可以先使用串口调试助手测试一下

图像窗口的名称可以更改

如果保存了数据或者图像，默认保存路径即为项目的路径

软件目前仍有需要完善的地方，仅供参考学习，可能仍存在部分bug

通信的协议有两种，一种是串口协议，一种是modbus协议，您可以在界面上手动选择

This is the author's first work that is the first open source, there may be file storage confusion, code clutter, please understand

PyQt5 only supports python3.9 and some code needs python3.0 or later to run. If your version is greater than 3.9 or less than 3.0, you can use Anaconda to create a suitable environment

It is recommended to use pycharm to ensure that the qtdesigner.exe file is recognized, please add it to the tool in advance

Data alarm parameters should be set first during debugging to avoid frequent pop-up alarm reminders

The serial port Settings of the upper computer and the lower computer should be consistent to ensure normal reception, you can first use the serial debugging assistant to test

The name of the image window can be changed

If data or images are saved, the default save path is the path of the project

At present, the software still needs to be improved, only for reference and learning, there may still be some bugs

### How to contact me

如何联系我

email:we2382918168@163.com

B站：小陈同志爱科研

抖音:小陈努力科研(逃离版)

皮皮虾：小陈玩命科研(摸鱼版)


### Complete list of modules

完整模块列表

Package             Version

------------------- --------------------

aiohttp             3.9.1
aiosignal           1.3.1
async-timeout       4.0.3
attrs               23.2.0
certifi             2024.2.2
charset-normalizer  3.3.2
click               8.1.7
colorama            0.4.6
contourpy           1.2.0
crc16               0.1.1
crcmod              1.7
cycler              0.12.1
filelock            3.9.0
fonttools           4.44.0
frozenlist          1.4.1
fsspec              2023.4.0
future              0.18.3
globals             0.3.36
idna                3.6
importlib-resources 6.1.0
iso8601             2.1.0
Jinja2              3.1.2
kiwisolver          1.4.5
markdown-it-py      3.0.0
MarkupSafe          2.1.3
matplotlib          3.8.1
mdurl               0.1.2
mpmath              1.3.0
multidict           6.0.4
nest-asyncio        1.5.8
networkx            3.2.1
numpy               1.26.1
opencv-python       4.9.0.80
packaging           23.2
pandas              2.2.1
Pillow              10.1.0
pip                 24.0
ply                 3.11
prompt-toolkit      3.0.42
psutil              5.9.8
py-cpuinfo          9.0.0
pygame              2.5.2
Pygments            2.17.2
pymodbus            3.6.3
pyparsing           3.1.1
PyQt-builder        1.15.3
PyQt5               5.15.9
pyqt5-plugins       5.15.9.2.3
PyQt5-Qt5           5.15.2
PyQt5-sip           12.13.0
pyqt5-tools         5.15.9.3.3
PyQtChart           5.15.6
PyQtChart-Qt5       5.15.2
pyqtgraph           0.13.3
pyserial            3.5
PySide2             5.15.2.1
python-dateutil     2.8.2
python-dotenv       1.0.0
python-helper       0.3.74
pytz                2024.1
PyYAML              6.0.1
qt5-applications    5.15.2.2.3
qt5-tools           5.15.2.1.3
requests            2.31.0
rich                13.7.0
scipy               1.11.4
seaborn             0.13.2
serial              0.0.97
setuptools          68.2.2
shellingham         1.5.4
shiboken2           5.15.2.1
sip                 6.7.12
six                 1.16.0
sympy               1.12
thop                0.1.1.post2209072238
tomli               2.0.1
torch               2.2.1+cu121
torchaudio          2.2.1+cu121
torchvision         0.17.1+cu121
tqdm                4.66.2
typer               0.9.0
typing_extensions   4.9.0
tzdata              2024.1
ultralytics         8.1.24
urllib3             2.2.1
wcwidth             0.2.13
wheel               0.41.3
xlwt                1.3.0
yarl                1.9.4
zipp                3.17.0


# ATravelerRecognizeImage
图像识别旅者

| :exclamation: 免责声明<br>本脚本使用后果均为使用者个人承担<br>The consequence of using this script must be undertaken by user. |
| ------------------------------------------------------------------------------------------------------------------------- |

主要使用pyautogui的库实现，以及使用gooey库制作了GUI

## 功能
- [x] 支持图形化界面
  - [x] 自定义excel和图片路径
  - [x] 使用checkbox选择是否循环和跳过匹配不到的图片
  - [x] 设置菜单，显示关于文本
- [x] 鼠标功能
  - [x] 单击
  - [x] 双击
  - [x] 右键
  - [x] 移动到指定图片的位置
  - [ ] 自定义点击位置（非默认的图片中心）
  - [ ] 长按鼠标拖拽
- [x] 输入功能
  - [x] 文本输入
  - [ ] 键盘按键键入
- [x] 等待功能
  - [x] 用户自定义每一步等待时长
- [x] 滚轮功能
  - [ ] 优化控制滚动距离
- [ ] 判断功能
  - [ ] 图片判断
- [ ] 截图功能
  - [ ] 截全屏
  - [ ] 自定义范围
- [x] 用户自定义鼠标参数
- [ ] 优化gui界面
- [ ] 脚本外接


## 使用方法：
在Example.xlsx文件中配置每一步的指令，根据表格提示填入对应的内容，指令12345678，分别具备单击，双击，右键单击，输入，等待，滚动，移动的功能。

点击ATRI.py文件运行。
## 注意事项
excel文件必须放在根目录中，如Example.xlsx存放的同级位置，放在文件夹中识别不到，是相对路径。

鼠标点击和移动默认为图片的中心位置，所以需要在截图的时候考虑，另外图片不易过小，会增加识别时长（虽然影响不大，也不是什么大项目）
## 安装依赖
在cmd窗口中执行：
```
py -3.8 -m pip install -r requirements.txt
```

## 更新 
### v1.1
改了功能“7”为移动鼠标，判断功能后面再补。

主要添加了是否循环和匹配不到自动跳过的功能，图片也支持手动输入文件夹检索了。

### v1.0
这是一个基于图片匹配的自动操作脚本，可以实现部分软件操作的自动化。

我根据gooey库，制作了一个图形化界面，用来调用参数和用户选项。



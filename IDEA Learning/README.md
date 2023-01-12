# 开发工具 IDEA 从入门到爱不释手
## 目录
+ 第2章 项目初始配置
   + <a href="#2-2">2-2 常用的基本设置</a>
   + <a href="#2-3">2-3 编辑区设置</a>
+ 第3章 开发中必会的技能
  + <a href="#3-1">3-1 高效的代码编辑技能</a>
  + <a href="#3-2">3-2 快速跳转</a>
  + <a href="#3-3">3-3 快速查找和替换</a>
  + <a href="#3-4">3-4 万能快捷键 Alt+Enter</a>
  + <a href="#3-5">3-5 键盘鼠标的配合</a>
+ 第4章 运行与调试
  + <a href="#4-1">4-1 启动项目</a>
  + <a href="#4-2">4-2 调试项目</a>

## <a id="2-2">2-2 常用的基本设置</a>
1. Font size  
   File - Settings (Ctrl+Alt+S)
   + Appearance - Name, Size
   + Editor - Color Scheme - Color Scheme Font - Size
   + Editor - Console Font - Size
   + Editor - General - Change font size with Ctrl + Mouse Wheel
   + Search for "font" directly in the upper left corner
2. Modify encode  
   Search for "encode" and change all to UTF-8
3. JDK  
   File - Project Structure - Project Settings - Project: new jdk to 1.8
4. Auto scroll  
   ⚙️ - Autoscroll to/from Source
5. Auto import  
   Settings search for "Auto import", tick Add... and Object...

## <a id="2-3">2-3 编辑区设置</a>
1. 显示行号  
   Settings search line numbers - click show line numbers
2. tabs 位置  
   right click tab,（2019.2 version）Configure Editor Tabs.. - Tab placement - Left
3. tabs 排序  
   right click tab, Configure Editor Tabs.. - Sort tabs alphabetically
4. tabs 数量  
   Settings search tabs - Tab limit (The number should be just enough to fill the list)
5. 自动换行  
   Settings - Editor - General - Use soft wraps in editor

## <a id="3-1">3-1 高效的代码编辑技能</a>
1. 复制  
   + 复制一行：光标放任意位置，Ctrl+C  
   + 点击左侧文件名，Ctrl+C 复制文件名  
   + 复制历史：Ctrl+Shift+V，双击记录后，可在当前光标处粘贴（保留5个历史）
2. 普通粘贴和简单粘贴
   + 普通粘贴（Ctrl+V）后，会自动格式化
   + (2019.2 version) 右键，Paste without Formatting (Ctrl+Alt+Shift+V 不需要记)，简单粘贴，不会格式化，但是会保留空格
   + Alt+鼠标左键并拖动：纵向选择多行文本
3. 格式化代码
   + Ctrl+A：全选；Ctrl+Alt+L：格式化
4. 剪切和复制一行或多行
   + Ctrl+X：剪切光标所在行，可以当删除用（不需要选中）
   + Ctrl+D：复制光标所在行
5. 上下移动一行或多行
   + Alt+Shift+上/下：当前行向上/下移动一行
   + Shift+上，选中两行；Alt+Shift+上/下移动
## <a id="3-2">3-2 快速跳转</a>
1. 行内跳转和选中
   + Home 键跳到行首，End 键跳到行尾 
   + Ctrl+左/右：跳过一个词
   + Ctrl+Shift+左/右：选中一个词 
2. 根据行号定位
   + Ctrl+G：跳到指定行
3. tabs 快速切换
   + Alt+左/右：左/右切换Tabs
4. 查看浏览过的文件
   + Ctrl+E：查看浏览过的文件列表
5. 快速打开文件所在文件夹
   + 右键-Show In Explorer：打开文件/类所在的文件夹
   + 提醒：项目路径不要带中文
6. 导航栏文件切换
   + 双击 tab 可以全屏，上方导航栏可以点开其他文件
## <a id="3-3">3-3 快速查找和替换</a>
1. 内容查找和替换
   + Ctrl+F：当前文件查找
   + Ctrl+R：当前文件替换
   + Ctrl+Shift+F：全局查找
   + Ctrl+Shift+R：全局替换
   + 光标定位到日志窗口，Ctrl+F：日志内容查找
2. 查找文件
   + Ctrl+Shift+N：按文件名查找文件
3. 查找操作和菜单
   + Ctrl+Shift+A：查找所有的菜单或操作
   + 或者点击上方 Help - Find Action...
4. 万能查找
   + 连按两次 Shift：查找文件、菜单、操作等，但不能查找文件内容
5. 2019.2 版本
   + 以上操作合并到同一个窗口，连按两次 Shift 即可

## <a id="3-4">3-4 万能快捷键 Alt+Enter</a>
Alt+Enter：智能辅助提示。给出的提示与当前光标所在的位置有关系。
1. 见到红色报错就按
2. 见到波浪线警告就按
3. 没报错没警告也可以按

小提示：1. 红色报错一定要解决；2. 尽量让代码不要出现警告，利用 Alt+Enter 解决各种警告。

## <a id="3-5">3-5 键盘鼠标的配合</a>
1. 纵向选择
   + 纵向选择多列：按住Alt键不放，鼠标点击拖动
2. 选中一大段代码
   + 鼠标点击开始位置
   + 找到尾行的位置
   + 按住Shift+鼠标点击结尾位置
3. 快速移动/复制代码
   + 纯键盘移动多行：
     - 按住Shift+上/下选中多行；
     - 按住Shift+Alt+上/下移动多行
   + 纯键盘移动多行，不适合移动的行数比较多，移动的距离比较远，或者跨文件移动
   + 键盘鼠标配合：
     - 用上一个小点学的选择多行，注意要选择到选择范围的再上一行的结尾，Ctrl+C复制
     - 光标定位到目标位置的上一行结尾，Ctrl+V粘贴
4. 类或方法的跳转
   + 按住Ctrl+鼠标左键，进入方法（method）/类（class）
   + 小提示：要跳回刚才的位置，可以按Ctrl+Alt+方向键左

## <a id="4-1">4-1 启动项目</a>

## <a id="4-2">4-2 调试项目</a>
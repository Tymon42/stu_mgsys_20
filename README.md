# stu_mgsys_20
# 学生成绩管理系统
## 概述
#### 自设存放学生信息的2个文件，分别是：  
Stu_Info.txt中有学生信息，包括学号、姓名、学院代码、性别代码、4门成绩  
C_Code.txt中有学院代码及其所对应的学院名称  
> Ps：数据自己造，学生数不少于30个，学院不少于3个  

## 要求如下：  
设计至少4个结构体来描述上述文件中包含的内容；  
进入系统前要求用户首先登陆，密码正确方可进入  
（要求建立一个保存密码密文的文件，如果文件不存在，首先创建文件并设置密码）

### 设计《学生成绩管理系统》的框架（要求至少7个函数，至少3个源文件，1个头文件）：  
> \*\*\*\*\*\*学生成绩系统菜单\*\*\*\*\*\*\*
> 1. 按姓名排序，输出
> 2. 按平均成绩排序，输出
> 3. 输出给定学院学生
> 4. 添加学生及其成绩
> 5. 修改给定学生成绩信息
> 6. 按姓名查询学生，输出
> 7. 删除学生成绩
> 8. 修改系统密码
> 9. 输出挂科学生信息并强调其挂掉的科目
> 0. 返回上一级菜单  
\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*


> 【注意】修改后的信息，均需同步到文件，如4、5、7、8功能  

#### 【提示1】开始进入菜单前，除了登陆外，还需要进行系统初始化：即读取原始文件数据，并以链表保存。

#### 【提示2】设计为交互式，程序执行后，显示上述菜单；比如输入2后，执行按姓名排序；进入2后，也可以再设计子菜单，从大到小？还是从小到大？还是返回上一级菜单？可由用户输入，比如：
  1. 从大到小排序
  2. 从小到大排序
  0. 返回上一级菜单
【提示3】可增加功能，但是不能减少功能，即0-9是必须的
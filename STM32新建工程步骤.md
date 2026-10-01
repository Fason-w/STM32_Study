# STM32新建工程步骤

- 建立文件夹，Keil5中新建工程(Project)，选择型号
- 工程文件夹里面建立Start，Library，User等文件夹，复制固件库里面的文件到工程文件夹

![image-20261001161623012](C:\Users\27608\AppData\Roaming\Typora\typora-user-images\image-20261001161623012.png)

- 工程里对应建立Start，Library，User等同名称的分组，然后将文件夹内的文件添加到工程分组里

![image-20261001161541937](C:\Users\27608\AppData\Roaming\Typora\typora-user-images\image-20261001161541937.png)

- 工程选项，C/C++，include Paths内声明所有包含头文件的文件夹

![image-20261001161707579](C:\Users\27608\AppData\Roaming\Typora\typora-user-images\image-20261001161707579.png)

- 工程选项，C/C++，Define内定义USE_STDPERIPH_DEIVER
- 工程选项，Debug，下拉列表选择对应的调试器，Settings，Flash Download里勾选Reset and Run

![image-20261001161834655](C:\Users\27608\AppData\Roaming\Typora\typora-user-images\image-20261001161834655.png)

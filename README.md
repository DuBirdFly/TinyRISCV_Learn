## 工具的使用



### CMD
`dir`
显示当前目录下的所有文件

`cls`
给CMD清屏


### make 工具链
`make clean`
清除该目录下由make产生的一切东西


### python仿真工具链
#### 运行指令测试程序
原作者[4.3运行指令测试程序](https://gitee.com/liangkangnan/tinyriscv#431-%E8%BF%90%E8%A1%8C%E6%97%A7%E7%9A%84%E6%8C%87%E4%BB%A4%E6%B5%8B%E8%AF%95%E7%A8%8B%E5%BA%8F)
#### 运行C语言程序
原作者[4.4运行C语言程序](https://gitee.com/liangkangnan/tinyriscv#44%E8%BF%90%E8%A1%8Cc%E8%AF%AD%E8%A8%80%E7%A8%8B%E5%BA%8F)
(当前c文件目录)make --> (sim目录)python .\sim_new_nowave.py ../tests/example/xxx/xxx.bin inst.data --> (cmd显示)pass --> (sim)目录下vcd波形文件刷新 --> gtkwave查看



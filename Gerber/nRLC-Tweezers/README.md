## PCB工艺 (PCB process)

PCB：4层板

厚：**1.6mm**

最小间隙：5mil

Gerber文件叠层顺序：GTL, G1, G2, GBL



PCB：4 layer 

Thickness：**1.6mm**

Minimum clearance：5mil

Gerber file stacking order: GTL, G1, G2, GBL

## 2021/03/24 文件修改 (Modify the file)

请使用PCB-Tweezers_0324_ZT.zip文件，修改部分：将3.5音频连接器悬空的第4引脚进行接地

这个修改不是致命缺陷，之前打过PCB-Tweezers_0301_ZT.zip文件的朋友不会产生本质的问题，具体区别如下：

- PCB-Tweezers_0301_ZT.zip文件：两条测试信号线在3.5音频连接器内部被第3脚包地

- PCB-Tweezers_0324_ZT.zip文件：两条测试信号线在3.5音频连接器内部被第3脚和第4脚包了两次地



Please use the PCB-Tweezers_0324_ZT.zip file, modified part: connect the 4th pin of the 3.5 audio connector to ground.

This modification is not a fatal flaw. Friends who have previously typed the PCB-Tweezers_0301_ZT.zip file will not have essential problems. The specific differences are as follows:

- PCB-Tweezers_0301_ZT.zip file: The two test signal lines are grounded by pin 3 inside the 3.5 audio connector.

- PCB-Tweezers_0324_ZT.zip file: The two test signal lines are grounded twice by pins 3 and 4 inside the 3.5 audio connector.


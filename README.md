# ATmega32U4--1.7--Timer-Application2
使用Timer（计数器）让LED模拟心脏一强一弱的跳动
####  电路图  
![890088680699154420](https://github.com/wenxiwei00/ATmega32U4--1.7--Timer-Application2/assets/114196821/2bd43aea-fc5d-4e87-b371-cb4dc647b434)  

注意这里一定要用PC6口才可以，因为我的代码里面用到了OCR3A寄存器，只有PC6与OCR3A关联  
<img width="474" alt="40b7affe50dca9e6497f2fd98db97e3" src="https://github.com/wenxiwei00/ATmega32U4--1.4--Timer2/assets/114196821/13a6e06d-37fe-4839-b3e1-d59b9d8f8c29">
####  最终效果  
最终效果也可以在youtube上查看：https://youtu.be/fSUryMGqG-I    
t表示时间，i表示LED亮度，100表示最亮  
t=0 i = 0  
t=0.1 i = 100  
t=0.5 i = 0  
t=0.6 i = 50  
t=1.0 i = 0  
t=3.0 i = 0  
t=3.1 i = 100  
t=3.5 i = 0  
t=3.6 i = 50  
t=4.0 i = 0   
####  参考资料  
可以找到如何设置Timer mode，如何设置pre-scaler...  
https://medesign.seas.upenn.edu/index.php/Guides/MaEvArM-timer3

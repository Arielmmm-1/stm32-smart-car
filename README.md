# stm32-smart-car

![Smart car](images/Smart%20car.jpg)

## 目录
- [废话](#废话)
- [学习路程](#学习路程)
- [尝试复刻](#~~抄袭~~复刻怎么从零开始?)
---
## 废话
从应试性考试高中转变大学，什么都不会，但想尝试上手做一个简单的小小的智能车项目，十分迷茫，所以我就想记录一下自己的学习历程，肯定是很野的路子哈

## 学习路程
---> C语言:这个是毋庸置疑要学的呀，一开始满怀期待到后面感觉无聊，所以我就先学到结构体，后面要学的话再继续  
[语言程序设计从入门到进阶【比特鹏哥c语言2024完整版视频教程】](https://www.bilibili.com/video/BV1Vm4y1r7jY/?spm_id_from=333.1387.favlist.content.click&vd_source=1a7e1f3e114f171851fd820f1e7de84e)

--->51单片机：这个真不是必要的，51太旧了，当时是水水就过了，也考虑过51单片机来做小车，但连线都不会，干脆就算了

--->stm32:这个是关键了，怎么让小车动起来就是靠编程来驱动，看江科大的视频学习的，而且你不需要学完就能做一台简单的基础智能车，可以边学边拓展小车的内容  
[STM32入门教程-2023版 细致讲解 中文字幕](https://www.bilibili.com/video/BV1th411z7sn/?spm_id_from=333.1387.favlist.content.click&vd_source=1a7e1f3e114f171851fd820f1e7de84e)  

当时还喜欢先看keysking的视频学习原理，再去看江科大的代码  
[【keysking】第0集 超易懂的STM32教程！！](https://www.bilibili.com/video/BV12v4y1y7uV/?spm_id_from=333.1387.favlist.content.click&vd_source=1a7e1f3e114f171851fd820f1e7de84e)

## ~~抄袭~~复刻怎么从零开始?
一开始连怎么连线共地都不会，最简单的方法当然是照抄啦：先模仿，去钻研，再去创新实现自己的想法  
B站上面很多基础智能车的组装视频，不妨看一看，比如我当时参考的up视频  
[【含全套代码】STM32智能小车入门教程（蓝牙遥控+红外循迹+超声波避障 ）TB6612驱动 单片机STM32F103 PW](https://www.bilibili.com/video/BV1CAe5zjEBv/?spm_id_from=333.1387.favlist.content.click&vd_source=1a7e1f3e114f171851fd820f1e7de84e)

## 目录结构
- Hardware 基础驱动程序
- System 延时等函数
- User 用户代码 主程序
- images 相关照片
- PCB 小车的pcb板子

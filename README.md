# Go_Bypass
一个免杀生成器模板，目前可以过国内主流杀毒。
20220716 视频演示
<br />T
https://mp.weixin.qq.com/s/hLjBa-0uka2GAxjnJRblwA
## 捆绑功能 2022-3-22
1. Golang 捆绑文件体积优化 3M 左右
2. 捆绑走HTTP请求
<br />Tip. 项目在用，暂不公开
<br />演示：https://www.bilibili.com/video/bv1VT4y117e4
## 功能更新：
1. 2022-1-1 修复BUG，国内全国，WDF过，卡巴过。
2. 2022-1-5 测试仍免杀并优化代码。
3. 2022-1-10 增加反沙箱
4. 2022-1-14 修复免杀
5. 2022-2-22 解决标记
6. 2022-3-22 动态解决特征标记
7. 2022-6-27 修复免杀，闭源主EXE,这次的主要优化方面  免杀一次很持久
8. 2022-7-16 多编译模式，由于三六零查杀编译特征，所以本次更新多种编译方式，具体生产12 个exe，只需要12个exe 去批量扫描，留下存活的就是蛊王
## 使用方法
使用方法：
<br />
go mod download
<br />
main.exe -h
<br />
可以使用Garbel混淆,效果可能会拉。
![image](https://user-images.githubusercontent.com/82130343/147438586-2ec0c4d5-2e8b-4689-a203-1236afc44f2e.png)

## 问题
1.不上线问题 
<br />部分CS生成Payload 需要勾选X64 或者使用C2 Profile文件 解决。
<br />Some CS-generated payloads require gou'xX64 or use the C2 Profile to resolve.
<br />
<br />
2.运行报错问题
<br />
![image](https://user-images.githubusercontent.com/82130343/176105293-5083d76b-e1c0-464b-8be0-3bcd87c264c2.png)
<br />如有以上问题，请按照以下命令了解决
<br />go mod download
<br />go get github.com/gonutz/ide

### 2022/06/27 测试：
![image](https://user-images.githubusercontent.com/82130343/175862101-afd0d347-5427-4956-a9ca-1650dc748990.png)
![image](https://user-images.githubusercontent.com/82130343/175862139-391a4366-050b-4151-a8be-e6b4427a875f.png)




### 上线
![image](https://user-images.githubusercontent.com/82130343/147844234-3580502d-ed13-4be9-89e9-2fb4ad7e0b5f.png)
![631dd04ce2b3c5f548ad8b99c979db5](https://user-images.githubusercontent.com/82130343/147847431-cd4cfb42-ca9b-4a05-aca3-1ab0f2d80eea.png)

收回之前的话，卡巴动态也发出来给大家玩了！
### 演示视频
https://www.bilibili.com/video/BV1Ym4y1Q7kf#reply97248324864

# 免责声明：
本代码仅用于学习，授权使用，下载后请勿用于非法用途。
本人不参加任何HVV行动，任何活动与我无瓜。

后续模等待添加.............
## 微信公众：一颗好韭菜
![8da12679da6d22c1c68464f4c1d64f8](https://user-images.githubusercontent.com/82130343/147440529-e6efd14d-6d2b-4161-9e9e-3543877539cb.jpg)

## 前言

欢迎来到宿舍管理系统小程序项目！本项目是基于Spring Boot框架开发的，结合了微信小程序、Java等前沿技术，旨在为高校宿舍管理提供便捷、高效的服务。接下来，让我们一起了解这个项目吧！

## 内容介绍

宿舍管理系统小程序主要实现了宿舍分配、维修申请、水电费查询、公告通知等功能。通过该小程序，学生可以方便地查看宿舍信息、提交维修申请，管理员可以轻松地进行宿舍管理、发布公告等。此外，项目还采用了前后端分离的设计，使得开发、维护更加便捷。

## 技术介绍

本项目采用以下技术栈：

- **语言**：Java
- **使用框架**：Spring、Spring MVC、MyBatis、微信小程序
- **前端技术**：JS、Vue、CSS3、Uniapp
- **开发工具**：IDEA/Eclipse、Uniapp
- **数据库**：MySQL 5.7/8.0
- **数据库管理工具**：phpstudy/Navicat
- **JDK版本**：jdk1.8
- **Maven**：apache-maven 3.8.1-bin
- **前端环境**：Node.Js 12\14\16

## 核心代码

以下是一段关于宿舍分配功能的后端代码：

```java
// 宿舍分配Controller
@RestController
@RequestMapping("/dormitory")
public class DormitoryController {

    @Autowired
    private DormitoryService dormitoryService;

    // 分配宿舍
    @PostMapping("/allocate")
    public ResponseEntity<?> allocateDormitory(@RequestBody AllocateDormitoryRequest request) {
        boolean success = dormitoryService.allocateDormitory(request.getStudentId(), request.getDormitoryId());
        if (success) {
            return ResponseEntity.ok("宿舍分配成功");
        } else {
            return ResponseEntity.status(HttpStatus.BAD_REQUEST).body("宿舍分配失败");
        }
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图
![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/331250/9/13151/140135/68c63b6fFac2ef016/44bcbc0bdeaf4bc3.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/342371/30/3227/28692/68c63b47Fda716450/73c2d1b7967de33e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/326717/31/19999/22056/68c63b47F633ffcf6/1f101783a53455eb.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/339513/5/10543/24471/68c63b47F3878795b/37f628194b2ac67c.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/335924/29/10613/27282/68c63b47Ffc0ab139/d22a77e20c7abd80.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/325858/1/19902/36318/68c63b48Fa7987005/1761204314bb196e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/330339/39/13132/88019/68c63b48Fe36b7c31/57cf64bd328363ab.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/348880/39/3118/35235/68c63b48F809c756a/d680a7b47466a5f3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/323462/30/19998/23117/68c63b48Fc9006075/89e67f347412a383.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/342531/26/3334/50289/68c63b48F96758d80/b595f517d623b407.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

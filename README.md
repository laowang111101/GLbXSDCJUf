# 前言

欢迎来到本学生作业管理系统项目，该项目是基于Web的，使用Java和Spring Boot框架进行开发。此项目适用于毕业设计或实战项目，不仅包含了源码和文档报告，还有详细的代码讲解，让你轻松理解和掌握系统开发过程。

# 内容介绍

本学生作业管理系统致力于帮助教师和学生高效地管理作业。系统主要包括以下功能模块：学生模块、教师模块、作业模块和成绩模块。学生可以在线提交作业，查看成绩；教师可以发布作业，批改作业，管理学生信息等。该系统界面简洁，操作方便，大大提高了教学管理效率。

# 技术介绍

## 语言：Java
## 使用框架：Spring Boot
## 前端技术：JS、Vue、css3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven：apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下是一段关于学生查询作业的核心代码：

```java
@RestController
@RequestMapping("/student")
public class StudentController {

    @Autowired
    private HomeworkService homeworkService;

    @GetMapping("/getHomework")
    public ResponseEntity<List<Homework>> getHomeworkByStudentId(@RequestParam("studentId") int studentId) {
        List<Homework> homeworkList = homeworkService.getHomeworkByStudentId(studentId);
        return ResponseEntity.ok(homeworkList);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/340012/27/8065/85265/68bdab04Fc3372569/c86057d144f12fe3.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/331310/3/10572/18773/68bdaadcF527a7e39/9ad652f064208f57.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/350104/32/736/20159/68bdaaddFe10aa7d7/be94eead49675ac3.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/348340/16/775/53410/68bdaadeFa6216f79/147ebbd842e9c6d5.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/323675/6/17396/36803/68bdaadeFb5a939b8/ed8e32e8bf206290.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/329377/20/10629/64218/68bdaadfFe76c8349/775d0e4bc112fd7f.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/326066/1/17337/18775/68bdaadfFa2e8c4c5/b0701213b68b59b9.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/333172/22/10560/22298/68bdaae0F206d90f6/7ac7a763f119d06f.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/340697/37/6927/48557/68bdaae1Fa03b26b6/ff208a361d0393a9.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/325608/8/17138/25088/68bdaae1F25237ba2/16680c5a4cb07a46.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

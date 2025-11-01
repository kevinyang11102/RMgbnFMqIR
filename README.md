# 前言

欢迎来到本课程作业管理系统项目，该项目是基于SpringBoot开发的，旨在为教师和学生提供一个便捷、高效的管理课程作业的平台。以下是本项目的详细解读和相关信息。

## 内容介绍

本项目是一款基于Java语言和Spring Boot框架开发的课程作业管理系统，该系统涵盖了作业发布、提交、评分、讨论等核心功能。通过本系统，教师可以轻松发布作业，实时查看学生提交情况，并进行在线批改和评分；学生则可以便捷地查看作业要求，提交作业，查看评分和反馈。此外，系统还提供了作业讨论区，方便师生互动交流。

## 技术介绍

- **语言：** Java
- **使用框架：** Spring Boot
- **前端技术：** JS、Vue、CSS3
- **开发工具：** IDEA/Eclipse
- **数据库：** MySQL 5.7/8.0
- **数据库管理工具：** phpstudy/Navicat
- **JDK版本：** jdk1.8
- **Maven：** apache-maven 3.8.1-bin
- **前端环境：** Node.Js 12\14\16

## 核心代码

以下是本项目中的一段核心代码，展示了如何使用Spring Boot整合MyBatis进行数据库操作：

```java
// 注入Mapper接口
@Autowired
private HomeworkMapper homeworkMapper;

// 查询所有作业
public List<Homework> findAllHomework() {
    return homeworkMapper.selectAll();
}

// 根据ID查询作业
public Homework findHomeworkById(Integer id) {
    return homeworkMapper.selectByPrimaryKey(id);
}

// 添加作业
public void addHomework(Homework homework) {
    homeworkMapper.insert(homework);
}

// 更新作业
public void updateHomework(Homework homework) {
    homeworkMapper.updateByPrimaryKeySelective(homework);
}

// 删除作业
public void deleteHomework(Integer id) {
    homeworkMapper.deleteByPrimaryKey(id);
}
```

## 免费源码获取

```
8000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/312152/26/12042/85659/689f36c3F8c7c8f43/8d0e0b14aac3cd4e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/315439/21/26509/17244/689f369eF9ed8dd6c/8dc380c41112809d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/313417/1/27006/19532/689f369eF87dcfbf7/5fcca951a01a673d.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/302675/19/25590/24659/689f369fF70dea11b/1902e332f0d2748d.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/319946/39/25457/46206/689f369fF17a2f25d/1ae5eb7c4f1270d6.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/320823/21/25961/110577/689f36a0Ffe939dd3/fbb968ebae2a2313.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/324132/39/5006/20721/689f36a0Ffe5595fe/5cba0c0ae4f6d91e.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/307212/33/26652/23475/689f36a1F6b16d331/77ed7966623de533.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/294799/26/7545/21940/689f36a1Faadc9916/4ef49f4df44b158e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/315042/17/26547/22061/689f36a2F8ff38f2a/8f2f33151c3ff57f.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326180/27/5128/22783/689f36a2F114ac0ed/09ed53638284674e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/289500/16/26374/24852/689f36a3Ff535bd7a/52572bba72959ad4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327027/25/5054/107965/689f36a3Fc7f5efda/9990897cd4d27d58.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

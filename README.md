# 前言

欢迎来到基于微信小程序的学生宿舍管理系统。本项目旨在帮助高校宿舍管理人员高效地完成日常工作，同时为学生们提供一个便捷、舒适的生活环境。本系统后端采用Spring Boot技术，前端使用微信小程序，实现了宿舍管理的信息化、智能化。

## 内容介绍

本项目主要包括以下功能模块：宿舍基本信息管理、宿舍人员管理、报修管理、卫生管理、费用管理等。系统界面简洁，操作方便，能够满足宿舍管理的日常需求。通过微信小程序，学生可以随时随地查询宿舍相关信息，进行报修、缴费等操作，提高了宿舍管理的透明度和效率。

## 技术介绍

### 语言：Java

### 使用框架：

- Spring
- Springmvc
- MyBatis
- 微信小程序

### 前端技术：

- JS
- Vue
- CSS3
- Uniapp

### 开发工具：

- IDEA/Eclipse
- Uniapp

### 数据库：

- MySQL 5.7/8.0

### 数据库管理工具：

- phpstudy/Navicat

### JDK版本：

- jdk1.8

### Maven：

- apache-maven 3.8.1-bin

### 前端环境：

- Node.Js 12\14\16

## 核心代码

以下是一段查询宿舍人员信息的核心代码：

```java
// 宿舍人员管理Service层
public List<DormitoryMember> getDormitoryMembers(String dormitoryId) {
    return dormitoryMemberMapper.selectByDormitoryId(dormitoryId);
}
```

```java
// 宿舍人员管理Mapper层
<select id="selectByDormitoryId" resultType="DormitoryMember">
    SELECT * FROM dormitory_member WHERE dormitory_id = #{dormitoryId}
</select>
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
![封面图片](https://img10.360buyimg.com/ddimg/jfs/t1/327174/23/19884/81594/68c6268aFde30260c/26e3db76a4123f9d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/348534/36/3227/12572/68c62662F9bb50f49/23b73bc535165d40.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/339299/19/10563/12130/68c62662F600a2149/a297bc8098f00dcd.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/337843/9/10553/24036/68c62662Fad4f7246/770a0d2269a1780d.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/326731/16/18941/27816/68c62663F090e151a/502a4a7f7e27396c.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/346092/19/3109/30160/68c62663F06ad05a9/61beaffa6c9e4a36.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/346515/37/3248/19268/68c62663F876532aa/2cc0c7083a5fa30e.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/342489/31/3290/17658/68c62664F88b0a686/33b1286552b6bded.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/336322/10/10588/12427/68c62664F811a5c86/c34329614f4b53d0.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/343043/7/3108/22990/68c62664Fbf4af9ec/773d7bd8c67f6a58.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

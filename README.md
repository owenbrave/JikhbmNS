# 校园医疗保险管理系统

## 前言

随着国家对高校学生健康保障工作的不断加强，校园医疗保险管理系统在高校中的应用变得越来越重要。本项目基于Java语言和MySQL数据库，采用Spring Boot框架开发，旨在为高校提供一个便捷、高效、安全的管理平台，实现对学生医疗保险信息的全面管理。

## 内容介绍

本项目主要包括以下几个模块：用户管理、保单管理、报销管理、统计查询等。系统支持学生在线投保、查看保单信息、提交报销申请，同时为管理员提供保单审核、报销审批、数据统计等功能。通过本项目，学校可以更加高效地管理学生医疗保险，提高工作效率，减轻师生负担。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为保单管理模块的部分核心代码：

```java
@RestController
@RequestMapping("/policy")
public class PolicyController {

    @Autowired
    private PolicyService policyService;

    @GetMapping("/list")
    public ResponseEntity<List<Policy>> list() {
        List<Policy> policyList = policyService.list();
        return ResponseEntity.ok(policyList);
    }

    @PostMapping("/add")
    public ResponseEntity<String> add(@RequestBody Policy policy) {
        policyService.add(policy);
        return ResponseEntity.ok("添加保单成功");
    }

    // 其他保单相关接口...
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

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/313268/7/26851/134060/689eefe4F3d14e1ad/0f4f6fbb3887b750.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/317500/29/24601/13448/689eefbdF98edb9e4/1d59a11861ef953e.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/269808/35/17660/82551/689eefbdF9e023485/68923ac55f8859af.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/324001/2/4963/35714/689eefbeF73c3e20f/97ba6771e64113d1.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/294037/14/18934/92129/689eefbeF781ee25c/1851671e8ab0812a.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325875/13/4812/43933/689eefbfF502331d8/dcd325f764629963.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/320003/33/25592/33682/689eefc0F57942dda/38bdbce2ecc4a433.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/287313/4/16159/42623/689eefc0F1d512824/37286973228f3d52.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/327082/3/5023/37293/689eefc1F4dc6a200/5a1b9a6436f73175.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/291051/24/27144/40218/689eefc2F2e967f32/f77a6f7db9d69ead.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)

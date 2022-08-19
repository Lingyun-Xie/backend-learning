# 系统介绍

这是一个简单的用户系统，可以添加用户、删除用户、查询用户、修改用户信息

用户介绍：用户ID userId 姓名 userName 性别 年龄 地址 技能

# 准备

安装JDK11, IDE

初始化一个 Springboot 项目（gradle, jdk11）, 导入到IDE中

添加gradle依赖，如测试库依赖，lombok依赖

提供一个Get接口，无入参，返回 Success

# 业务需求

1. 获取所有用户

Return Example:

```json
[
  {
    "userId": 1,
    "userName": "zhangsan",
    "gender": "Man",
    "age": 20,
    "addr": "Chengdu",
    "skills": "Backend Dev, TDD"
  },
  {
    "userId": 1,
    "userName": "lisi",
    "gender": "Woman",
    "age": 18,
    "addr": "wuhan",
    "skills": "Frontend Dev"
  }
]
```












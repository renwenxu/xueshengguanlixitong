# 学生管理系统 疫情 管控
###所有代码都已经完成使用的是Spring+SpringMvc+Mybatis框架
##SSM框架实现
需要代码的可以加我的QQ：873015763
或者我的wx
![输入图片说明](%E7%A7%81%E4%BA%BA%E5%BE%AE%E4%BF%A1.png)


#### 此项目是一个大学毕设项目，其中功能主要分为角色管理和权限管理
#### 功能主要为
- 疫情防控模块，疫情防控知识
- 学生管理
- 教师管理
- 个人设置
- 
 登录注册模块本模块主要为，本平台分为三个角色用户，分别是学生用户、教师用户、管理员用户，不同的角色用户具有不同的菜单资源以及操作权限，管理员直接设置，学生和教师可以注册，登录的时候选择对应的角色，最后显示当前账号所具有的资源与赋予相应的操作权限。

疫情动态防疫知识模块主要为，管理员用户在后台管理和上传疫情动态信息，学生、教师用户通过该模块可以接受查看对应的疫情动态信息，对于疫情动态信息，管理员具有增修改查权限操作，教师用户、学生用户具有查看权限操作。

班级管理模块主要为管理员对班级进行增删改查操作。

教师管理模块主要为，管理员用户对教师账号进行添加、删除、修改、查看权限操作，添加操作的时候，在已存在的所有班级中唯一选择一个班级作为该教师用户管理的班级，教师担任班主任角色。教师用户可以添加同一班级的学生用户作为自己的学生。班级与班主任属于一对一关系，一个班级只有一个班主任，一个班主任只管理一个班级。

学生管理模块主要为，管理员用户对学生账号进行添加、删除、修改、查看权限操作，添加操作的时候，在已有的所 有班级中唯一选择一个班级作为该学生用户所在的班级。班级与学生的关系为一对多关系，一个班级可以有多个同班学生，多个学生可以属于一个班级。

我的学生模块主要为，班主任用户具有添加学生的权限操作，被添加的学生相当于换了班级，换了班主任。班主任与学生属于一对多关系，一个班主任可以有多个学生，多个学生的班主任可以是同一个人。

学生状态模块主要为，管理员用户和班主任用户可查看学生提交的健康表单，对于健康表单管理员用户具有查看、删除权限操作，老师用户具有查看权限操作，学生用户具有增加、修改、查看权限操作

学生回校离校相关模块本模块主要为，学生用户提交回校申请表单，教师用户对学生用户提交的回校申请做一级审批， 如果一级审批通过则管理员用户做二级审批，否则管理员不进行二级审批操作，对于回校申请表单，教师具有查看、审批权限操作，管理员具有删除、查看、审批操作，学生具有增加、查看权限操作。

个人设置模块本模块主要为，用户可以查看自己的用户信息，包括账号、姓名、邮箱、手机号，可进行个人信息修改，密码修改

主要图片
登录
![输入图片说明](%E7%99%BB%E5%BD%95.png)
注册
![输入图片说明](%E6%B3%A8%E5%86%8C.png)
学校模块
![输入图片说明](%E5%AD%A6%E6%A0%A1%E6%A8%A1%E5%9D%97.png)
疫情模块
![输入图片说明](%E7%96%AB%E6%83%85%E7%9F%A5%E8%AF%86.png)
角色模块
![输入图片说明](%E8%A7%92%E8%89%B2%E8%8E%AB%E8%8B%A6%E7%86%AC5.png)
人员管理
![输入图片说明](%E4%BA%BA%E5%91%987.png)

申请审批模块
![输入图片说明](%E5%AE%A1%E6%89%B98.png)

健康表单模块
![输入图片说明](%E5%81%A5%E5%BA%B7%E8%A1%A8%E5%8D%95%E6%A8%A1%E5%9D%971.png)






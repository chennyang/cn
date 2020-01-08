# 用户管理


用户管理支持多种用户维护及配置操作，包括创建/删除用户、导入用户、启用/停用用户、编辑用户基本信息及角色、搜索用户等。


**新建用户**

用户是可以登录堡垒机的自然人。堡垒机的用户类型有本地用户、IAM子账号用户。

用户创建方式包括：手动创建、导入IAM子账号、从本地文件中导入。

![](/image/Bastion/user.png) 


- 手动创建：单击新建用户进入创建页，按页面要求填写用户信息，完成后单击创建用户。
- 导入IAM子账号：单击导入IAM子账号，在弹窗中选择需要导入的子账号。
- 从本地文件导入：点击从本地文件导入，可以批量导入用户

操作步骤

1、 进入用户 > 用户管理页，选择 新建用户，手动创建用户。

  在新建用户页面，输入用户名、密码、姓名，选择角色，并根据需要补充联系信息。
  
  
   其中，角色分为运维和管理员
   
   - 运维：仅可以登录有权限的机器
   
   - 管理员：可以添加用户、资产等，可以管理堡垒机
 
   
  ![](/image/Bastion/addUser.png) 
  
 
  
2、 导入用户，选择 从本地文件导入，批量创建用户。

  1） 在 从本地文件导入 页面，点击 模版下载。
  
  2） 填写模板,其中 用户名 密码字段必填，其中密码必须 8 - 30 位，同时包含大小写字母、数字和特殊字符，且字母和数字不能连续或重复
      角色包含管理员和运维；
      
  ![](/image/Bastion/moduleUser.png) 
  
  3） 完成模版之后，点击 上传文件。
  
**停用用户**

用户被停用之后将不能登录堡垒机，直到管理员重新设置为启用。

操作步骤

1、 进入用户 > 用户管理页

2、 在用户列表中，单击 停用

  ![](/image/Bastion/userStop.png) 

**启用用户**

操作步骤

1、 进入用户 > 用户管理页

2、在用户列表中，单击 启用

  ![](/image/Bastion/userStart.png) 


**删除用户**

操作步骤

1、 进入用户 > 用户管理页。

2、 在用户列表中勾选需要删除的用户，单击删除。

**编辑用户**

操作步骤

1、 进入用户 > 用户管理页。

2、 在用户列表中，单击 编辑，支持编辑用户的基本信息



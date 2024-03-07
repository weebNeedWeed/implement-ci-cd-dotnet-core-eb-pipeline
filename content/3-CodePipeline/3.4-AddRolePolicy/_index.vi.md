---
title : "Thêm Policy cho Service Role"
date :  "`r Sys.Date()`" 
weight : 4
chapter : false
pre : " <b> 3.4 </b> "
---

#### Thêm Policy cho Service Role

1. Tìm và truy cập trang quản trị **IAM**.

![0001](/images/3-CodePipeline/3.4-AddRolePolicy/0001.svg)

2. Chọn **Roles** sau đó chọn Service Role CodePipeline tạo ra.

![0002](/images/3-CodePipeline/3.4-AddRolePolicy/0002.svg)

3. Chọn **Add permissions** > **Attach policies**.

![0003](/images/3-CodePipeline/3.4-AddRolePolicy/0003.svg)

4. Tìm và chọn Policy ```AdministratorAccess-AWSElasticBeanstalk```.

![0004](/images/3-CodePipeline/3.4-AddRolePolicy/0004.svg)

5. Chọn **Add permissions**.

![0005](/images/3-CodePipeline/3.4-AddRolePolicy/0005.svg)
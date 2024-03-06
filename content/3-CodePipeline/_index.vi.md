---
title : "Triển khai CodePipeline"
date :  "`r Sys.Date()`" 
weight : 3 
chapter : false
pre : " <b> 3. </b> "
---

#### Triển khai CI/CD cho ứng dụng với CodePipeline

Trong phần này ta sẽ cùng nhau triển khai CI/CD cho ứng dụng .NET 6 được xây dựng sẵn trong **[Repository này](https://github.com/weebNeedWeed/sample-code-for-eb-codepipeline)**. Ứng dụng có duy nhất một endpoint là "**/**" trả về dòng chữ *Hello world* khi được gọi.

{{% notice note %}}
Để thực hiện các nội dung trong phần này, bạn nên clone **[Repository này](https://github.com/weebNeedWeed/sample-code-for-eb-codepipeline)** và push lên một Repository khác thuộc tài khoản Github của chính bạn.
{{% /notice %}}

![Architecture](/images/1-Introduction/0001.svg)
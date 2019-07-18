---
title: "EasyDining - Java Web Development"
layout: post
date: 2019-04-22 19:10
tag: [Java, SpringBoot, MySQL, RESTful, Logback, WebSocket] 
image: https://res.cloudinary.com/do3j5ljcx/image/upload/v1563394461/spring-boot.png
headerImage: true
projects: true
hidden: true # don't count this post in blog pagination
description: "Full-stack web application in MVC architecture for food delivery website to handle orders and manage inventory"
category: project
author: zhihaozhang
externalLink: false
---



Full-stack web application in MVC architecture for food delivery website to handle orders and manage inventory.

[Source code](https://github.com/zhihaozhangim/EasyDinning). 

---

What is EasyDinning all about?

- Created RESTful API with Spring Boot, applying SLF4J and Logback to record real-time system logs
- Utilized MySQL database to store products and orders information, using Spring Data JPA for efficient database looking-up and manipulation, supplemented with Redis as Cache layer to boost server performance
- Built a user-friendly frontend with Bootstrap and FreeMarker, leveraging WebSocket to push instant notifications
- Implemented distributed lock with Redis, enabling server to handle 300 QPS tested by Apache ab

---

Project Demo

Order List
![Order List](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396644/List.png)


Product List
![Product List](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396645/Product_List.png)


Order Detail1
![Order Detail1](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396643/Order_Detail1.png)


Order Detail2
![Order Detail2](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396644/Order_Detail2.png)


Category List
![Category List](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396642/Category_List.png)


Create/Update Product
![Create/Update Product](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396643/Create_update_Product.png)


New Order Notification
![New Order Notification](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396643/New_Order_Notifications.png)


Special credits to my friend [Shawn Wang](https://www.linkedin.com/in/jinghao-wang-shaw/) for creating the awesome client side UI

Client List
![Client List](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396642/Client_Side_List.png)


Client Side Comments
![Client Side Comments](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396642/Client_Side_Comments.png)


Client Side Make Order
![Client Side Make Order](https://res.cloudinary.com/do3j5ljcx/image/upload/v1563396642/Client_Side_Make_Order.png)


---

[Check it out](https://github.com/zhihaozhangim/EasyDinning) here.
If you need some help, please [file an issue](https://github.com/zhihaozhangim/EasyDinning/issues).

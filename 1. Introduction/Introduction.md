Introduction  
译：介绍

Definition of DevOps:  
译：DevOps的定义：

DevOps is a set of practices that works to automate and integrate the processes between software development and IT teams, so they can build, test, and release software faster and more reliably.  
译：DevOps是一套实践，旨在自动化和整合软件开发与IT团队之间的流程，以便他们可以更快、更可靠地构建、测试和发布软件。

The term DevOps was formed by combining the words “development” and “operations” and signifies a cultural shift that bridges the gap between development and operation teams, which historically functioned in silos.  
译：DevOps这个术语是通过结合“开发”和“运维”两个词形成的，它标志着一种文化转变，弥合了历史上在孤岛中运作的开发和运维团队之间的鸿沟。

A frequently asked question: What happens after a user types www.google.com into a browser?

1. The browser sends www.google.com as a query to the DNS Server.
2. The DNS Server returns Google's corresponding IP address to the user's browser.
3. After obtaining the IP address, the user sends a web page request to the Google server.
4. The Google server responds with the web page content to the user's browser.

一个常被问到的问题：当用户在浏览器输入了www.google.com，之后发生了什么？
1. 浏览器把www.google.com作为query发送给DNS Server
2. DNS Server将google对应的ip发还给用户的浏览器
3. 用户拿到ip地址以后，向google server发送网页请求
4. google server将网页内容response给用户浏览器

What does CDN(Content Delivery Networks) use for?  
Low Latency, Better UX, Globally Availability  
译：CND用来做什么？降低延迟，有更好的用户体验，全球可用性

For example:  
Client Side -> Amazon Route 53 -> Amazon CloudFront -> S3 Bucket (Static Web Page)

How to handle requests from different users in parallel?
1. Reverse Proxy / Load Balancer
For example: Nginx; ELB
2. AutoScalable Stateless Servers / Lambda functions
3. Multi-region

What does DevOps need to code?
1. Script - automation
2. Infra as Code - code defined

Build and Test <==> CI - Continuous Integration  
Release and Deploy <==> CD - Continuous Deployment

Use Pipeline -> CI/CD

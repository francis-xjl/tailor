# tailor
Tailor is a webapp for looking at and searching through files and streams. This project is a full rewrite of https://github.com/gvalkov/tailon for java. Tailor try to add more powerful function in production.

Tailor是一个通过文件与流的搜索工作。本项目基于https://github.com/gvalkov/tailon，使用Java进行完全重写。并且在此基础上试图加入更多具有生产力的功能：

- [] 1.支持独立部署
- [] 2.支持嵌入项目(spring-boot-starter)
- [] 3.awk/grep可以选择全文件，而不只是tail -f | grep 
- [] 4.支持多节点汇集(需要与nacos集成)，同时查询多个节点的服务日志

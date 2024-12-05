---
uuid: c8126604-8300-aa56-3184-26ad61c86941
title: MYSQL 常见操作
categories:
- 后端
tags:
- MySql
---
MYSQL 常见操作
---------------------------------------------------------------------------------------------------
SELECT date_format( CREATED_TIME, '%Y-%m-%d' ) from problem_t;
SELECT date_sub( curdate(), INTERVAL 7 DAY ) ;
SELECT date_sub(curdate(),interval 30 DAY);
SELECT date_sub(curdate(),interval 90 DAY)
SELECT date_sub(curdate(),interval 180 DAY)
SELECT date_sub(curdate(),interval 360 DAY)
SELECT curdate();
SELECT NOW();
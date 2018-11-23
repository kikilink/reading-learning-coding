# 数据库表信息查询

show table status where name = 'm_user'

show index from m_user

show full fields from m_user

set global slow_query_log=1;
show errors
show variables  

show variables  like '%slow_query_log%';


--单位是秒
show variables like 'long_query_time%';

log_output='FILE,TABLE'
日志存储位置
show variables like '%log_output%';


是否记录未使用索引日志
show variables like 'log_queries_not_using_indexes';



select * from mysql.slow_log;




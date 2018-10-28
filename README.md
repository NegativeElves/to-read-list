[blog]
https://my.csdn.net/dog250
https://blog.csdn.net/fuzhongmin05/article/details/71001857 (Singleton)
http://www.cnblogs.com/xdp-gacl/p/3633936.html (Thread 1)
https://www.cnblogs.com/xdp-gacl/p/3634382.html (Thread 2)

[GDB]
https://deepzz.com/post/gdb-debug.html#toc_27

[Spring,IOC]
https://www.zhihu.com/question/21346206
https://www.zhihu.com/question/23277575

[VIM for Java]
https://blog.csdn.net/fxy832231/article/details/60904908
http://fiandes.io/vim-configuration-for-happy-java-coding/

[Design Pattern]
https://java-design-patterns.com/

[面试题]
http://www.cnblogs.com/wang-meng/p/5898837.html
各部门在各年龄段的平均工资
select deptid,
sum(case when age < 20 then salary else 0 end) / sum(case when age <20 then 1 else 0 end) as “20岁以下平均工资”,sum(case when age >= 20 and age <40 then salary else 0 end) / sum(case when age >= 20 and age <40 then 1 else 0 end) as “20至40岁平均工资”,sum(case when age >= 40 then salary else 0 end) / sum(case when age >=40 then 1 else 0 end) as “>40岁及以上平均工资”,from employee group by deptid
[HashMap]
https://blog.csdn.net/luanlouis/article/details/41576373

## what's the most difficult thing you have  solved?(challenge)

When I worked at Hailiang Education Company, A service meets OOM exception often. The reason is that many threads create files at the same time.

so I use kafka to handle this problem. I create one Topic named file-messge, and 3 partitions, the number of services is same as the number of partitions. so ervery service only has one thread to create files.

This action can make save many memory resources, so the OOM exception disappeared.

## please introduce yourself and discuss your experience

hi,I'm bulingfeng. I'm a Java develper with 8 years. I focus on backend development with using java language.

I have much experience in building microservices with springboot and springcloud framewrok, I play a key role as  a team learder and a senior java developer in my last job. my job can be divided into two parts:

1. I will assign some tasks to the others.
2. I will write the core codes for the project.

and I have the ability to solve online issues, for example, a sql runs very slowly, so I use the explain key word to analyze, then I add a unique index  to the order no. after that, the sql ran faster than before. Performance improved by 80%

## how did you optimize SQL queries

- avoid select all columns
- add some indexes
- Using explain plan to analyze query performance and optimize it

## Why did you resign from last company?

because I think there is a big platform and more chances in BeiJing, so I quit my job from Hangzhou.

## Please introduce your project you have developed

recently, I developed an AI application with LLM. before developing it , when I ask for a leave, I have to login oa system, and fill some key information. That is so complex.

but now, I just say a sentence to my mobile phone, for example, I want to make a leave, the reason is I'm sick. This AI application can make a leave automately. This AI appplication is very convinent.



second project is student project. this project includes many student information, parents can pay money for their children. 

There are some flows in this student system, such as student's upgrading, student's dropout and student enrollment.

This project use springboot,springcloud to build a hight available micro-services. 

the database is mysql. the cache is redis.message midleware is kafka.

 My role is senior java developer. my main responsibilites include code development and services deployment.

thank you for chatting with me!



the third project is a loan project. I communication with goverment offcers and get some datas, such as marital datas of company boss, the number of active employees in the company and so on.

This system will score  small companies based on this data to determine whether they meet the loan eligibility criteria.



the fourth project is  a peer to peer loan system. The department I work in is the risk control department. This system can dertermined whether a person can loan money.

If the person meets the loan criteria, he can get the loan.



## what are your sthengths and weaknesses?

First, I want to talk about my sthengths.

first, I can learn knowledge quickly from books or lessons. so I can use them in my job immedietly.

second,I can communicate with colleagues well.

Last, I want to talk about my weakness

1. I think my English pronunciation needs to be improved.
2. I think I have to takes some time to adapt foreign environment,but I believe I can adapt it quickly.

其他外企面试参考文章

```
https://blog.csdn.net/xj2369157734/article/details/123920398
```

想起来介绍业务就介绍业务，如果不能介绍业务就说自己使用的技术。

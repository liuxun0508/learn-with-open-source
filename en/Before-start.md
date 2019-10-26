# Before the beginning

## The target audience for this document

### The software developers confused in opensource

* Developers who would like to write readily intelligible code but don't know how to start  
* Developers who would like to understand other people's code  

### Software development beginner

This is a document for software development beginners, who have learned no more than two programming languages and are able to complete most of the exercises in the course in terms of the language skills they have learned. Considering the general situation of college education, they could only complete the baseline of final course assignments arranged by teachers. That is to say, they are not so well in course and have trouble  in finding a way to improve their skills.

For students who have graduated or will graduate from universities(within two years), it is difficult for them to get access to truly complex projects, and they will be incharge of the trivial details even if they are involved in complex projects. They are eager to improve their ability in software development as soon as possible, but what they lack mostly is just the opportunity to improve themselves.

Therefore, this paper hopes to introduce a more reasonable method to help students  improve the ability of software development in a more scientific and reasonable way.

### First-time users of open source software

In the field of software development, it is almost impossible to ignore open source projects at all. How to improve the development efficiency with the help of open source projects in the daily development work and reduce the duplication of effort and how to benefit from open source rather than suffer from it is also an interesting topic. In a nutshell, it is risky to use a open source software without reading its source code (there is no difference from using normal closed source software or closed source libraries). But if we can read and understand the source code, we can avoid this risk,and the better we understand it, the better we can use the software. Open source software can offer us this possibility.

This article also hopes to help those who are new to open source and want to make good use of it by sharing experience of the experienced individuals.

### Hobbyists wandering outside the open source community

Do you want to be part of the open source community and to repay some help to the open source community after enjoying the benefits it offerd? What is going on in the open source community? There are a lot of people who have a natural affinity with open source and hope to join in, integrate into the open source community faster, to make more contributions to open source project, or even to start their own open source project and pull up a team to do something amazing. There should be many friends that have such idea. We hope the introduction of this article can have certain help.

Since this is an open writing document, I am not particularly sure that when I write this paragraph this document will have only four target users. Maybe it can be of value to more people……

## The basic conditions

### A computer with Internet access

It does seem irresponsible to say that these are all the basics. But it's really enough. Assuming that you are just working in an open source JavaScript project, install a developer-friendly browser like FireFox/Chrome and you will be basiclly ready to start.

Furtherly, of course, there can be more fastidious. For example, Windows or Linux/MacOS? What distribution should you choose for Linux? Once you get into it, there will be endless problems waiting for you.

### The preferred Ubuntu

First, the reason why Linux should be choosen is that open source software, in many cases, is a more stable and reliable version for Linux, which is easier to solve when it comes to version dependence. Of course, there are many reliable open source projects for Windows, so Linux is more of a preference for using more open source. The jade bed mentioned in JinYong's "The Return Of the Condor Heros" can be used to explain the mystery. When you are in an open source enviroment and when your operations are exposed to open source concepts, you are making progress all the time and it's going to be faster.

The reason of choosing Ubuntun is actually my own preference, for it is by far the easiest to use. It's more friendly for beginners. There are more Chinese resources on the Internet.

In addition, there is a very famous article on the Internet named "[Why developers should use Mac OS X and simple history of OS X(《开发人员为何应该使用Mac OS X 兼 OS X 小史》）](https://blog.youxu.info/2010/02/28/why-mac-os-x-for-programmers/)", which is also very convincing and recommended to read.

### If you really like Windows

Admittedly, in the Windows enviroment, you can also learn about open source. There are many open source persons working hard on the Windows platform. A lot of environment building tools are being developed inch by inch like RubyInstaller, XAMPP, cygwin and so on.(Specific nouns will not be explained here)

But, at a lot of time, you will encounter inexplicable report errors and it is not unreasonable that a lot of people will suddenly look up into the sky in a night and curse:"This rotten Windows!"

### The network will not be blocked

Google is a better search engine for software development in the most of time, so even if you have to go though a lot of trouble, make sure to use Google to search for the projects, documents and materials you are looking for.

Reference:

* [HuoJu: Google Baidu and Google（《霍炬：google百度和谷歌的那些事》）](http://blog.devep.net/virushuo/2010/01/14/blog56google_blogtinyfool_1_go.html)  
* [ChenHao: To be an enviromental programmer from not using Baidu on(《陈皓：作环保的程序员，从不用百度开始》)](https://coolshell.cn/articles/9308.html)

## Somethin You need to be specific

### Do you really want to learn software development?

Before the formal start of learning, I really can't help myself to ask you again and again: Do you really want? Do you really want to be a "code farmer"?  Do you really want to master the craft of software development, or even make a living from it? Well, I have to tell you some truth:

* Software development is not the kind of high-paid and little-responsibility white-collar worker you might expect to be. Many programmers will call themselves "code farmers", because this occupation is very hard, and not easy to do well.  
* In addition, this is a career that requires lifelong learning. Many other fields do not have such a rapid rate of knowledge updating. But in the field of software development, if you don't touch the latest developments in technology for a year or two, you will be OUT.  
* Also, software development is not much easy to find a job. Job prospects are not as bright as the fabled success stories.  
  However, there are some people who love this industry. Coding is not only their job, but also their hobby.

### Are you really fit in software development?

Software development, though, is not the high-IQ and nerd industry in the legend. But it does need some qualities and abilities that if you find yourself lacking or having to hard to achieve, you're not suited for the job.

* Laziness:There is a famous saying that "laziness is the virtue of programmers", because real programmers must hate to do the same thing repeatedly, at least they will write a function to complete for themselves. If they find the same paragraph is repeated in the code, they can't help themselves to eliminate it.  
* Organization:If this is a complex thing, I can handle it in three stages. If I think carefully about it, the first stage could be divided into five parts. Before starting the first pahse, there are four preparations that must be considered first.  
* Patience: A lot of time, the trouble in the program will come to you, and how to solve it? Solving "bug" requires insight, care and, most of all, patience. Sometimes, I really enjoy the process of "solving cases".  
* Curiosity: There are so many things worth to be curious about. We have a lot of curiosity in new technologies that will never be finished learning, recent developments and best practices, and even other industries and fields because no matter what industry, they will come to us and help them write code.  
* Serious: It is said that a lot of things almost ok is really ok. But computer is so strict that even if one hundredth of a millisecond faster than before is faster. A one in ten thousand chance of a bug is still a bug. If you are not a serious enough people, you will ignore a lot of problems which could lead to disaster.

### OK, cut the cackle and let's start!

Translated by LiYancheng
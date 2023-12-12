---
날짜: '"2023-12-12"'
넘버: 
태그: 42subject
출처: 42seoul
aliases:
---
### 날짜  2023-12-12 19:11

### 태그: #42subject 

>[!메모]
> This project is about doing something you've never one before.
> Remind yourself the beginning of your journey in computer science.
> Look at you now. Time to shine!
> 
> Version: 14.1

### 원문
---
# Essential Points
This project is a complex undertaking, requiring decision-making within the specified constraints. You have some flexibility in implementing certain modules, and it is left to you discretion **within the scope of the subject**. All your choices must be justifiable.

If you believe it's necessary to use _nginx_ to set up your website, there's no issue, but ask yourself first, is it truly necessary? Can I do without it? Similarly, when faced with a library that could assist you, it's crucial to understand whether it will fulfill your tasks. Your not expected to rework uninteresting sub-layers but rather to make the proposed features function.

It's crucial to understand that you'll encounter decisions where doubts about implementing certain features will arise. Initially, it is **STRONGLY recommended**  to comprehend the project requirements thoroughly. Once you've grasped what needs to be accomplished, it is necessary to stay within the framework of the project. When we mention an imposed technology, it explicitly means that everything officially related to the requested framework/language is allowed.

However, we emphasize that when you wish to implement a module, all restrictions apply to that module. For instance, if you want to realize the project with the Backend module as specified in the subject, you can no longer use the default language and must adapt your project accordingly. If you still want to create a backend using the default language, it's also possible, but since you'er not using the requested language/framework, this module will not be considered valid.

Before concluding, it's important to note that some modules intentionally have strong dependencies on others.

Your choices are significant and must be justified during your evaluation. Exercise caution.
Take the time to contemplate the design of your application with your choices before delving into toe code - it's crucial.

Have a fun ! :)

# Mandatory part
This project is about creating a website for the mighty **Pong** contest!
> [!caution]
> The use of libraries or frameworks or tools to replace your job is strictly prohibited. Each part of the subject will explicitly present the authorized [[third party]] software you can use. Nevertheless, it is allowed and even recommended to use anything possible to simplify certain actions. it is important to note that any tools or resources utilized must be justified. Please be aware that simplifying does not equate to completing your work.

## 1 Overview
Thanks to your website, user will play Pong with others. You have to provide a nice user interface and real-time multiplayer online games!
- Your project needs to adhere to the following guidelines as a minimum requirement, contributing only a small portion to the final grade.
- The second part of this subject will offer additional modules that can replace or complete the following rules.
In this Subject, certain words are highlighted in green. These represent technology choices that will evolve over time. Pay close attention to the version of the subject.

## 2. Minimal technical requirement
Your project has to comply with the following rules:
> [!info]
> Again, some of these contraints could be overriden by the choice of specific modules.
- You are free to develop the site, with or without a backend
	- If you choose to include a backend, it must be written in pure ==Ruby==. However, this requirement can be overriden by the **Framework module**.
	- If your backend or framework uses a database, you must follow the constraints of the **Database module**.
- The frontend should be developed using pure vanilla ==javascript==. However, this requirement can be altered through the **FrontEnd module.**
- Your website must be a [single-page application](https://en.wikipedia.org/wiki/Single-page_application). the user should be able to use the Back and Forward buttons of the browser. 
- Your website must be compatible with the **latest stable up-to-date version** of ==Google Chrome==.
- The user should encounter no unhandled errors and no warnings when browsing the website.
- Everything must be launched with a single command line to run an autonomous container provided by ==Docker==. Example: docker-compose up --build
> [!caution]
> If your container solution is Docker:
> When your computers in clusters run under Linux, you will use Docker in rootless mode for security reasons. this comes with 2 sideways:
>
> - Your Docker runtime files must be located in /goinfre or /sgoinfre.
> - You can't use so called "bind-mount volumes" beteen the host and the container if non-rootUIDs are used in the container.
>
> Depending on the project, your situation and the context, several fallbacks exist: Docker in a VM, rebuild you container after your changes, craft your docker image with root as unique UID.






---
### 생각(파생된 질문/생각)

### 출처
- https://cdn.intra.42.fr/pdf/pdf/115340/en.subject.pdf

### 연결 문서 (연결 이유)

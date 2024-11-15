# Contribute to (OSS) Open source software
All of us using OSS, more over most of the software we use is based on oss. Routine process of development is picking packages from platform sources for example npm if you are developing java script program and writing some ligth glue code for that to make work your app. This is nature of software development because of one the base pricinples "DRY" - do not repeat yoursesf. Folloiwng that principle developers try to reuse every piece of code that is repeated. It is become hard to find this pieces because many developers already did that work. Also when piece of software is done by developer who realy love his work it is polished, and done with best efforts. With all that things in mind, it becomes really hard to put something valueable to public or contribute to project that is already used by many developers for person without years of developement experience or someone from IT but non developers like software testrs or designers. While this stair is high for beginner, such contributon may become a good starter for developer carier. It also looks very impressive in CV because all developers have some kind of pet projects but iusually they to shy to put it on public. Purpose of this guide is to help beginners to step on that stair.

## Choosing tech and project
From practical point of view it is alway better to stay with most popular technology because of larger communit there will be large amout of edge cases solved, bigger toolset and more documentatios, it is till humans writing code so more humans more code =). According to [github 2024 octoverse](https://github.blog/news-insights/octoverse/octoverse-2024/) Python beats JavaScript as most popular language. 

<img src="github_octoverse_2024.webp"> 

>-*There are three kinds of lies: lies, damned lies, and statistics.* — Mark Twain

>-*TypeScript (TS) is a superset of JavaScript (JS), developed and maintained by Microsoft as an open-source programming language.* — Google

So i would not say that JavaScript is beaten by Python. 

According logic described above my choise for oss contribution will be JavaScript and NodeJs as platform. My primary area of knowledje is Accesibility tools, Im also working as software tester. With this in mind best for me would be to contribute to some accessibility tool that is related to tesing and written in JavaScript. I know this tools a little so i will go directly to https://github.com/dequelabs/axe-core. You may find this logic too smooth to be true, especially since I’m not showing the research process. It's true that I already knew my target project before I started. However, I still recommend not blindly picking just any project. You need to carefully consider the learning curve; otherwise, it might kill your motivation.

## Tools and basics
For sure you have to learn basics to become a developer for this projects it is: 
- Git         - *version control systems*
- JavaScript  - *programming language*
- NodeJs      - *JavaScript runtime*
- Npm         - *JavaScript package manager*
- VSCode      - *Integrated development environment*

You need to download and install this tools on your PC, follow official guides.

From my experience, the best way to learn something is to actually try using it. Some tools are quite straightforward — you don't need to spend hours figuring out how to chop a stick with an axe. A couple of hours of practice might be enough... maybe just a finger or two lost in the process! ;)

### Git
You need Git to commit your changes to the source code. Luckily, you don’t have to fully master it — just understanding the basic principles of version control systems is enough. Long story short, you’ll be editing text files alongside other people, and there are plenty of tools to sync your files in one place. Git is the de facto industry standard for this now. 

### VScode
Editing text in notepad is deadly simple, but you have to use many other tools to make it smooth. Place where all this tools is aggreagted is integrated developemnt  environment. We need VScode to navigate and search in code, it have nice syntax highligthing and text formatting also we can avoid git command line.

### JavaScript
You have to uderstand basics like variables, cycles, functions. Btw you can use any code generatrion tools, like ChatGPT or analogs.

### NPM and NodeJs
While developing software you need to use other developers code in yours othervice you will write everything from scratch each time you start a project. Easy way is to go to github and copypaste code from other repositories, how about code that other repositories uses itself? Нou need to climb a dependency tree untill you reach very basics runtime platform code. There is tools for code sharing usually they are specific for platform or code in our Case it is NPM (Node Package Manager) is a default package manager that comes bundled with NodeJs. Each package manament comes with some hidden costs for example where is garamntee that somewhere in deep of dependency graph there is package that contains some malicios code? It is called supply chain attack.

<img src="dependency_graph_example.webp"> 

## Discover choosen project

First of all you need a github account, this days is like facebook for developers, I already have it https://github.com/engineerklimov. I will create copy of [axe core](https://github.com/dequelabs/axe-core) in terms of git is called fork.

Lets donwload source code from mine axe core fork and try some basic operations. As i explained before you dont need to know all git command to use it probbaly you can event avoid its shell. Open vscode and navigate as shown in picture, in text field choose clone from github ot copypaste repository url.

<img src="repo_clone.png"> 

### Restore packages

### Build command

## Find contribution target

## Prepare pull request

## Maintainers review and merge
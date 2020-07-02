# GitHub
GitHub与Git基本操作知识

* **1.GitHub基本概念**
    * **1.1 Repository(仓库)**<br>
    仓库用来存放项目代码，每个项目对应一个仓库，多个开源项目则有多个仓库。  
    * **1.2 Star(收藏)**<br>
    仓库主页star按钮，意思为收藏项目的人数。
    * **1.3 Fork(复制克隆项目)**<br>
    仓库主页Fork按钮，当A点击B仓库的Fork时，A仓库也就多了一个项目，A可以修改此项目，但B不受其影响。
        * **1.3.1 Pull Request(发起请求)**<br>
        当A觉得B的某个项目需要修改时，A可以向B发起一个Pull Request，B收到该请求后，若认可该修改，则接受该请求。
    * **1.4 Watch(关注)**<br>
    当A点击B仓库里项目的Watch按钮时，若B修改该项目，则A会第一时间收到相关通知。
    * **1.5 Issue(事务卡片)**<br>
    当A发现B仓库里项目存在BUG或想讨论时，可以点击该按钮。
	
	
* **2.Git基本操作**
	* **2.1 git config --global user.name "yourname"**<br>
	配置本地仓库操作账号。
	* **2.2 git config --global user.email "youremail"**<br>
	配置本地仓库操作账号对应邮箱。
    * **2.3 git status**<br>
    查看本地工作区状态。  
    * **2.4 git add somefile**<br>
    将某个文件加入暂存区。
    * **2.5 git commit -m '操作解释'**<br>
    将某个文件加入本地仓库。
    * **2.6 git push**<br>
    将本地仓库上传至GitHub云端仓库。
    * **2.7 git clone somelink**<br>
    将GitHub云端仓库克隆到本地。

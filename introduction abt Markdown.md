![cover](http://nvie.com/img/git-model@2x.png)
___

##
***introduction abt***
#
**Git_Workflow**
###
Z.BurNIng Zhang Boning
516030910319
___
#
***what is git workflow***
>workflow
>just like water flows smoothly
>no interruption, no conflict

##
***THREE main process of flow***
+ git flow
+ github flow
+ gitlab flow
___

#
***Git flow***
>**one of the most *earliest*** workflow

###
**two long term branch:**
1. master
2. develop

**three short term branch:**
1. feature branch
2. hotfix branch
3. release branch

once completed, short term branches will be combined into develop or master without saving
___
#
***Github flow***
>**just a simplified version of Git_flow**

###
**only one long term branch**

---------master
##
***steps***
1. creat a new branch
2. open a pull request
3. merge and deploy

>Good to production which is steadily produced
>or updated regularly
___
#
***Gitlab flow***

>it digest all the advantages of the above two workflows
>it is highly recommended by Gitlab.com

##
***"Upsteam first"***
only those codes which were accepted by master can be applied into other branches

##**abt branches**
1. master
2. pre-production
3. production
___
#
***why use Git***

referrence click here [why](https://www.baidu.com/s?wd=Git%20workflow%E4%BC%98%E7%82%B9&rsv_spt=1&rsv_iqid=0xe11503da0002dd5d&issp=1&f=8&rsv_bp=1&rsv_idx=2&ie=utf-8&rqlang=cn&tn=monline_3_dg&rsv_enter=1&oq=%25E4%25B8%25BA%25E4%25BB%2580%25E4%25B9%2588%25E4%25BD%25BF%25E7%2594%25A8Git%2520workflow&sug=%25E4%25B8%25BA%25E4%25BB%2580%25E4%25B9%2588&rsv_t=5d43Zv1dGys%2BgtmVlCGaSkf6NsxOUMlSM%2Bw0Z4gJwws6BQA27GwV3WUt4HmhID%2FP9FkC&inputT=4551&rsv_sug3=18&rsv_pq=f025f75600017cf7&rsv_sug1=8&rsv_sug7=100&rsv_sug2=0&rsv_sug4=5230)
##
***two advantages concluded below***
1. each member can have access to all codes, not just one of copies of them. all can execute "add" and "commit" command, regardless of whether the other side of repo changed or not.
2. several designs, including work space, buffer space, referrence update, etc, free the developer to shift between works, without the loss of codes
___
#
***how to use Git workflow***
assume we have two programmer:
A and B, both develop on the same program
steps are like followings:
1. create a center repo
>just click "create repo"
2. clone center repo to local place as local repo
>git clone /theRepoPath
3.add and commit 
>submit both their changes to the center repo

___
#
***the end***
***thank you***



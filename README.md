# Introduction to  ``` Git  and GitHUb ```
### Git is server level tool to maintain Agile methodology.

### SDLC : Software Developement Life Cycle.

  Product
1. raw material
2. processing
3. manufacturing
4. assembling
5. packing
6. delivery.


S/w product
1. requirement
2. deliver software.
sdlc:- models
1. waterfall model (oldest)
2. spiral model
3. Evolution Model
4. prototype model
5. Iterative model
6. fish Model
7. V Model
8. Big Bang Model
9. Agile Model (latest model)

### Why do we need model:-
we need model so that we can maintain the standards.
1. Software Quality good.
2. Software Deadlines.
3. Software Quantity Benchmark.

### Any model undergoes following steps
1. Requirement Analysis
2. Design or Feasibility Analysis
3. Actual Implementation (Designing and coding)
4. Testing
5. Deployement (Release or Build)
6. Monitoring
7. Feedback
8. maintainance.

### Devops Engineer :- 
it is culture under Agile.
Devops = Developement(Technical Testing +  coding + Designing) + Operations (Non Tech)

### Agile :- modern approach methodology sdlc.
## Agile :- 
1. scrum : 5 sprint = 1 scrum in a week
2. sprint : no of task done in 1 day in 8 hours.
3. scrum master : Team work, scrum master (manager).
	Tool :- Jira.
	worlds popular project management tool.
	Atlassian :Australian Product.
	
4. sprint planning : (monday (45 min)| other days updates or progress(10-15)):- 
	1.psr : planned status report
		1. last friday work down + todays plan.
		task pending on current sprint will become backlog fro another 
		sprint.
		
		1. login
		2. register
		
	2.dsr : daily status report.(closure)
	  1. register 
	  2. login pending
	  
	  Backlog :  
	 
	 Tuesday : psr => 
	 Backlog + current => Todays PSR
	 
	 
	 Friday :- Daily scrum (psr)
	 Deadline : overtime and saturday (Payscale Jira)
	
5. Review :
	Daily Review
	 1. Narrow : done hawa mey 
	 2. wide : register => jira => code push (git)=> jira code is pushed
	 awnish kumar 5:45 min code push 
	 code review => code will show.
	 
	 git push (upload to server)
	 git pull (donwload from server)
	 
	Internal Review :- 45 to 2hours
	Team 
	   1. share the screen and show what you did in, 5 days.
	   2. Other problem or challanges or Errors.
	   
	   challanges, problem genuine
	   next sprint include.
	   
	<-------------------------Sprint Planning  + updates + Backlog
6. retro
	+ Retro:-

		1. keep doing : keep updating, keep cordinating with team, with manager.
		2. stop doing : late in scrum.
		3. start doing : no body tells about problem if faced.
		proper feedback.
		
		Internal Meeting.
		
		Note :: No leaves and formalities are allowed in this time.
		
		ctc: cost to company.
		1,20 : 30 thousand Taxe
		80 in hand - 10 Thousand (perfomance bonus)

		1. Fixed Income + Variable Income 
		
		
		1. (2000/-)
		2. (2000/-)
		3. (2000/-)
		4. (2000/-)
		5. (2000/-)
		

	Friday :- 
	Client Review :- 
	
7. sprint close.

It-Sector : 5 days working.


### What is git?

git is scm or vcs.
scm
vcs

version:changes made in the code.

tools other than git

git svn(sub versioning):

git tool:git bash(cli tool=>command line tool.)

svn tool gui tool:tortoise=> GUI .

in general git do:

it maintains changes made in the code date wise and time wise and author wise and code wise.

we place the code in server also:-

we know that,when our code is saved it remains at local only.
that means,we dont have backup,so if system failure happens,the code will be deleted permanently.
hence we keep the copy of our project in a server which cannot accessed directly.

server:secure,and it does not allow delete Operation.

### What type of server?
*****************************
it is a cloud server.

### Types of cloud Server.

1.Dedicated Server.(private server)
2.Non Dedicated Server.(public server)

1.Centralized Server.
2.Distributed Server.

 ### Difference b/w svn and git
1.svn:centralized server.
2.git:distributed server.

1.svn:outdated or which have dedicated server.

Ex:Security,NIC,CBI.

2.git:modern or can be used by any type of organisation.

3.svn:centralized server then no backup possible.
git: since we have lot of server backup problem is resolved.

## What type of Cloud Server?
1.github  =(latest=> Linux open source free to use for single person,for company it is pais=>Microsoft)
2.gitlab=(latest=>open source =>free)
3.bitBucket
4.BitKeeper(oldest)=>Linux open source free to use.


## Source=> server =>cloud server.
github => account
all files folder.
similarly in github=> file upload in a folder
that folder=>repository

files=> folder => share=> .zip => compressed file=>folder.
in git/github => highly compressed file => delta compressed(10GB to 100Mb)
similarly git/github converted folder to=>.git file.
 this .git is called repository.


Access the git=>(repository)
****************************

every git repository is accessed using git url.

https://github.com/owner-name(profile-name)/repo-name.git


## Every Repo 2 Types
1.Private Repo:(any body can not download)
2.Public Repo:Anybody can download(visible to anybody)

KeyPoints about repo:

1.Every repo is unique for single user.
2.Two different account user can have same repo name.
3.Every repo has a description which is optional.
4.Every repo hjas a licence if you have it ,very good upload.

   none or Unlicensed.
5.Every repo has by default as origin(Branch)
Branch:-by default=>main. github(May-August 2021)  =>master =>main
older<master>
latest<main> =>git/github.

main name is only valid for github.


6.Every repo is followed my initial file=> Readme.md(markdown)
Why name is markdown?
Note:Description allows you to write only few information about.
For more detail information in better way  you can go for readme.md.

#Welcome to git Repo => h1 Heading
##=>h2-h3
###=> h4-h6

can we change name of main to master

### 1.There are two type of setting.

1.Global Setting
    a.account based setting=>
    b.developer setting.=>token,permissions of repo.
2.Project Level Setting.(repo level setting)

when you create a repo you can configure ,repo-permissions
you can add your team member.
change branch name .
add public and private for security.
You can  change visibility of repo(public=>private:private=>public)



1.upload=>push
2.download=>pull
   There are three types of download in git:-
   1.git clone
   2.git pull <code-name> or <branch-name>
   3.git fetch--all
   
   ******************Differenec between git clone | pull| fetch--all*************
   
   first time :code download:git clone : download code at first .
   all commands after clone.
   
   parts by parts code download :git pull
   download all codes at once :fetch--all
   
   
   when you will download git and install
      1.git bash:Terminal is more powerful
      2.git gui
   
   
   
   how to colne the project
   $ git clone <git-url>
   
   Ex:git clone https://github.com/vishwakarmavinay305-dev/First-Repp-Vinay.git
   
   How to see all recents actions
   
   $ git log
   
   
   Linux Commands
   
   1. ls -lart  : show files and folder list
   2.cd folder name : you can inside any folder
   3.cd../  : to come outside of a folder.
   4.touch <filename.extension> :used to create any file of any extension.
   5.mkdir : to make folder
   6.rm -r <filename>:to delete any or any folder.
   7.clear: to clear screen.
   8.echo "You Code" >> filename :append mode.
   9.echo "You Code" > filename :write mode.
   10.whoami:who is user of system.
   11.pwd:to print path of the folder.
   12.cwd :get current working directory.
   13.cat<filename>:content at => shows the code of files.






























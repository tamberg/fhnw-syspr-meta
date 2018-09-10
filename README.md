# FHNW (syspr) Meta
Setup used to teach module [syspr]( https://www.fhnw.ch/de/studium/module/6008081), [CC BY-SA](https://creativecommons.org/licenses/by-sa/4.0/) [@tamberg](https://twitter.com/tamberg) for [FHNW](https://www.fhnw.ch/).

## GitHub Classroom
* https://classroom.github.com/classrooms
  * https://classroom.github.com/classrooms/42295693-fhnw-syspr-3ia (per class)
    * https://classroom.github.com/classrooms/42295693-fhnw-syspr-3ia/assignments/fhnw-syspr-work-00 (assessment, per week)
    * https://classroom.github.com/classrooms/42295693-fhnw-syspr-3ia/assignments/fhnw-syspr-work-01
    * ...
  * https://classroom.github.com/classrooms/42180051-fhnw-syspr-3ib
    * https://classroom.github.com/classrooms/42180051-fhnw-syspr-3ib/assignments/fhnw-syspr-work-00
    * https://classroom.github.com/classrooms/42180051-fhnw-syspr-3ib/assignments/fhnw-syspr-work-01
    * ...

## GitHub Accounts
* https://github.com/tamberg (author, teacher)
* https://github.com/fhnw-syspr-3ia (org, per class)
* https://github.com/fhnw-syspr-3ib
* https://github.com/USER (each student)

## GitHub Repos Teacher
* https://github.com/tamberg/fhnw-syspr (slides &amp; code examples, per module)
  * https://github.com/fhnw-syspr-3ia/fhnw-syspr (fork, per class)
  * https://github.com/fhnw-syspr-3ib/fhnw-syspr
* https://github.com/tamberg/fhnw-syspr-work-00 (hands-on exercises, per week)
  * https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-00 (fork, per class)
    * https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-00-USER (generated copy, per student)
    * ...
  * https://github.com/fhnw-syspr-3ib/fhnw-syspr-work-00
* https://github.com/tamberg/fhnw-syspr-work-01
  * https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-01
  * https://github.com/fhnw-syspr-3ib/fhnw-syspr-work-01
* https://github.com/tamberg/fhnw-syspr-work-02
  * https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-02
  * https://github.com/fhnw-syspr-3ib/fhnw-syspr-work-02
* https://github.com/tamberg/fhnw-syspr-work-03
  * https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-03
  * https://github.com/fhnw-syspr-3ib/fhnw-syspr-work-03
* ...

## Workflow Teacher
### Creating Original Content (once)
* https://github.com/tamberg/fhnw-syspr
* https://github.com/tamberg/fhnw-syspr-work-00

Can be private, if author has private repos.

### Creating a Fork per Class
https://github.com/tamberg/fhnw-syspr-work-00 => click fork button, chose org

### Adding Upstream to Fork
https://help.github.com/articles/configuring-a-remote-for-a-fork/
<pre>$ git remote -v
$ git remote add upstream https://github.com/tamberg/fhnw-syspr-...
$ git remote -v</pre>

### Syncing Forks with Upstream
https://help.github.com/articles/syncing-a-fork/
<pre>$ git fetch upstream
$ git checkout master
$ git merge upstream/master
$ git push</pre>

### Adding a GitHub Classroom Link
To each class specific fork, add a note with the assessment URL
> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/TODO).*

## Workflow Students
### Playing with Code Examples
<pre>$ cd ~
$ git clone https://github.com/fhnw-syspr-3ia/fhnw-syspr</pre>

Changes remain local, forking / pull requests possible to enhance examples.

### Updating Slides and Code Examples
<pre>$ git pull</pre>

Ideally once a week before lesson starts.

### Working on a Hands-on Assignment
https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-00 => click classroom link => get personal repo
<pre>$ cd ~
$ git clone https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-00-USER
$ git add FILE
$ git commit -m "fixed all bugs"
$ git push</pre>

Questions or review request per GitHub issues, right on the personal repo.

Can be private, [request unlimited private repos from GitHub](https://education.github.com/discount_requests/new).

Beware: There's no easy way to update the personal repo copies.

## Tools Teacher
* Google Slides
* AWS S3 (Hosting PDFs)
* GitHub Classroom
* GitHub
* Git
* gcc

## Tools Students
* GitHub
* Git
* gcc

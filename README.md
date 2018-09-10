# FHNW (syspr) Meta

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

## GitHub Repos (Teacher)
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

## Workflow (Teacher)
### Creating a Fork
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

## Workflow (Student)
https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-00
<pre>$ git clone </pre>

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

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

To each original repository, add the following note:
> *Note: Do not work on this repository right away.*<br/>
> *[Check existing Forks, to find the specific repository for your class.](../../network/members)*

```
> *Note: Do not work on this repository right away.*<br/>
> *[Check existing Forks, to find the specific repository for your class.](../../network/members)*
```

Or, in German
> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*

```
> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Prüfen Sie die vorhandenen Forks, um das Repository für Ihre Klasse zu finden.](../../network/members)*
```

### Creating a Fork per Class
https://github.com/tamberg/fhnw-syspr-work-00 => click fork button, chose org

### Cloning the Fork
<pre>$ git clone https://github.com/fhnw-syspr-3ia/fhnw-syspr-work-xx</pre>

### Adding Upstream to Fork
https://help.github.com/articles/configuring-a-remote-for-a-fork/
<pre>$ git remote -v
$ git remote add upstream https://github.com/tamberg/fhnw-syspr-work-xx
$ git remote -v</pre>

### Syncing Forks with Upstream
https://help.github.com/articles/syncing-a-fork/
<pre>$ git fetch upstream
$ git checkout master
$ git merge upstream/master
$ git push</pre>

### Solving Merge Conflicts
<pre>$ nano README.md
$ git add README.md
$ git commit
$ git push</pre>

### Adding a GitHub Classroom Link
To each class specific fork, add a note with the assessment URL
> *Note: Do not work on this repository right away.*<br/>
> *[Create your personal copy by clicking this GitHub Classroom link](https://classroom.github.com/a/TODO).*

```
> *Note: Do not work on this repository right away.*<br/>
> *[Create your personal copy by clicking this GitHub Classroom link](https://classroom.github.com/a/TODO).*
```

Or, in German
> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/TODO).*

```
> *Achtung: Arbeiten Sie nicht direkt auf diesem Repository.*<br/>
> *[Erstellen Sie eine persönliche Kopie, mit diesem GitHub Classroom Link](https://classroom.github.com/a/TODO).*
```

### Disabling / Enabling the Classroom Link
Make sure to disable the Classroom Link in the settings until the repository is in its final version. Once a student copies the repository using the Classroom Link there's no way to update the student's copy.

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

Beware: There's no easy way to update the personal repo copies.

Can be private, [request unlimited private repos from GitHub](https://education.github.com/discount_requests/new) and [add organisations](https://education.github.com/benefits).

## Tools Teacher
* GitHub Classroom
* GitHub
* Git

## Tools Students
* GitHub
* Git

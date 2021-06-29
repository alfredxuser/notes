### [Git][Git]

Git is a **VCS (Version Control System)** for tracking files on your big or small developer project, it will keep your stuff in order. YOU SHOULD USE IT!!!

<br>

Git tutorial: English

<iframe width="560" height="315" src="https://www.youtube.com/embed/USjZcfj8yxE" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

Git tutorial: Spanish

<iframe width="560" height="315" src="https://www.youtube.com/embed/kEPF-MWGq1w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<br>
<br>

#### Usage

```bash
 $ git init
```

First buddy, you need to configure git... Do this:

```bash
 $ git config --global user.name "Name or nickname, whatever you like"
 $ git config --global user.email "Your email"
 $ git config --global core.editor "Editor you will use"
```

Done. If you need changes, just run the command again. Review config file:

```bash
 $ git config --list
```
<hr>
<br>

What's going...

```bash
 $ git status
```

<br>

Add ALL files to stage area

```bash
 $ git add .
```

Dot(.) means add ALL files. If you prefer adding one by one just type your file name instead the dot (Boring) :sleeping:

<br>

"OMG bro I screwed up, I need to unstage a file" easy:

```bash
 $ git rm --cached YOUR-FILE-NAME SECOND-FILE THIRD-FILE BLA-BLA BLABLA
```

You can unstage ONE or multiples files.

<br>

Commits...

```bash
 $ git commit -m "YOUR MESSAGE, CHANGES OR WHATEVER YOU DO AT THIS TIME"
```

:heavy_exclamation_mark: The purpose of commits is to remember throughout a timeline what you do.

<br>

"Bro, Where I can preview my commits?" type:

```bash
 $ git log

 # or

 $ git log --oneline
```

<br>

"But I want to edit a commit message" also:

```bash
 $ git commit --amend COMMIT-TAG
```

:heavy_exclamation_mark: COMMIT-TAG: **4ebd3d9026bb4424e593b572b21bc5937ebc3e0f** You only need to insert first 7 characters

<br>

Go to a specific commit, type:

```bash
 $ git reset --mixed COMMIT-TAG
```

<br>

List branches:

```bash
 $ git branch
```

<br>

Create a branch:

```bash
 $ git branch NAME-OF-BRANCH
```

<br>

Move between branches:

```bash
 $ git checkout BRANCH-NAME
```

<br>

Delete a branch:

```bash
 $ git branch -d BRANCH-NAME
```

<br>

Merge a branch with the master/main. :point_up: Before merging move to master/main branch.

```bash
 $ git merge BRANCH-NAME
```

<br>

List tags:

```bash
 $ git tag
```

Tags are used to create versions of your project.

<br>

Create a tag:

```bash
 $ git tag TAG-NAME-VERSION
```

For more info about how to **version** your project [Click here][Version project]

<br>

Delete a tag:

```bash
 $ git tag -d TAG-NAME-VERSION
```

### [Github](Github)

Add your repository to Github

```bash
 $ git remote add origin URL-THAT-GITHUB-GAVES-YOU.git
 $ git branch -M main
 $ git push -u origin main
```

<br>

Bring the project from Github to your local PC:

```bash
 $ git clone URL-FROM-GITHUB
```

<br>

Repository we're connected:

```bash
 $ git remote -v
```

<br>

Difference between your local repo and github

```bash
 $ git fetch
```

<br>

Upload to github

```bash
 $ git push
```

<br>

Download from github

```bash
 $ git pull
```

<br>

Upload tags

```bash
 $ git push --tags
```

[Back to top](#Usage)

[Back to index](../index.md)

<!--Referenced links-->
[Git]: https://git-scm.com/ "Oficial website for Git"
[Version project]: https://www.instagram.com/p/CBQtfnWqHlB/ "How to version project"

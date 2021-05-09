<h1 align="center">
<br>
  <img src="/img/git-logo.png" alt="Git cheat sheet" width=200"></a>
  <br>
    <br>
  Git cheat sheet
</h1>
<br><br><br><br>

## Introduction
A resume to everything you could need of while using GIT

GOAL: increase productivity

## Unstage changes
Case scenario: after a `git add .` the user realizes that node_modules or the others 4k+ files are getting committed and this is not what he wants

**COMMAND TO USE**: `git reset`
<br>Effect: files will be moved from staged to unstaged without losing anything

**DO NOT RUN**: `git reset --hard`
<br>Effect: It will not only unstage your added files, but will revert any changes you made in your working directory. If you created any new files in working directory, it will not delete them though

## Switch between branches multiple times
If you are switching back and forth different branches multiple times, you would have to write git checkout branch-1 and git checkout branch-2 over and over again. Since developers hate repetition you can use `git checkout - || gco -`





COPY AND PASTE NOTES FROM OLD JOBS, BOOKMARKS AND GOOGLE KEEP NOTES AND REORDER

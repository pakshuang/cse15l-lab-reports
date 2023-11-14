# Lab Report 4 - Vim (Week 7)

## Step 4: Log into ieng6

```bash
$ ssh cs15lfa23lq@ieng6.ucsd.edu
```

Keys pressed: `<up><enter>` (to get to the previous command)

## Step 5: Clone the repository

```bash
[cs15lfa23lq@ieng6-201]:~:62$ git clone git@github.com:pakshuang/lab7.git
```

Keys pressed: `<ctrl+c><ctrl+v><enter>` (to copy and paste the command)

## Step 6: Run tests

```bash
[cs15lfa23lq@ieng6-201]:~:63$ cd lab7
[cs15lfa23lq@ieng6-201]:lab7:64$ bash test.sh
```

Keys pressed: `cd lab7<enter>` (to change directory), `bash test.sh<enter>` (to run the tests)

## Step 7: Edit the code

```bash
[cs15lfa23lq@ieng6-201]:lab7:65$ vim ListExamples.java
```

Keys pressed: `vim L<tab>.java<enter>` (to open the file in vim), `:44lllllxi2:wq<enter>` (to edit, save, and quit)

## Step 8: Run tests again

```bash
[cs15lfa23lq@ieng6-201]:lab7:66$ bash test.sh
```

Keys pressed: `<up><up><enter>` (to run the tests)

## Step 9: Commit and push

```bash
[cs15lfa23lq@ieng6-201]:lab7:67$ git add .
[cs15lfa23lq@ieng6-201]:lab7:68$ git commit -m "fix index1"
[cs15lfa23lq@ieng6-201]:lab7:69$ git push
```

Keys pressed: `git add .<enter>` (to add all files), `git commit -m "fix index1"<enter>` (to commit), `git push<enter>` (to push)

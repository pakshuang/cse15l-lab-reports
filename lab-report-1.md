# Lab Report 1 - Remote Access and FileSystem (Week 1)

## `cd`

### `cd` with no arguments:

```bash
[user@sahara ~/lecture1]$ cd
[user@sahara ~]$ 
```

Without arguments, the `cd` command changes the directory to the root directory
Not an error

### `cd` with path to a directory as an argument:

```bash
[user@sahara ~]$ cd lecture1/
[user@sahara ~/lecture1]$ 
```

With a path to a directory as an argument, the `cd` command changes the directory to the directory provided in as the argument
Not an error

### `cd` with a path to a file as an argument:

```bash
[user@sahara ~/lecture1]$ cd Hello.java
bash: cd: Hello.java: Not a directory
```

With a path to a file as an argument, an error message is shown because a directory is expected, not a file

## `ls`

### `ls` with no arguments:

```bash
[user@sahara ~/lecture1]$ ls
Hello.class  Hello.java  messages  README
```

Without arguments, the `ls` command lists the names of the files in the working directory
Not an error

### `ls` with path to a directory as an argument:

```bash
[user@sahara ~/lecture1]$ ls messages/
en-us.txt  es-mx.txt  ms.txt  zh-cn.txt
```

With a path to a directory as an argument, the `ls` command lists the names of the files in the directory provided in as the argument
Not an error

### `ls` with a path to a file as an argument:

```bash
[user@sahara ~/lecture1]$ ls Hello.java 
Hello.java
```

With a path to a file as an argument, the `ls` command lists the name of the file, not very useful

## `cat`

### `cat` with no arguments:

```bash
[user@sahara ~/lecture1]$ cat

```

Without arguments, the `cat` command waits for an input
Not an error

### `cat` with path to a directory as an argument:

```bash
[user@sahara ~]$ cat lecture1/
cat: lecture1/: Is a directory
```

With a path to a directory as an argument, the `cat` command displays an error message that the argument is a directory, since it expects a filename

### `cat` with a path to a file as an argument:

```bash
[user@sahara ~/lecture1/messages]$ cat en-us.txt 
Hello World!
```

With a path to a file as an argument, the `cat` command prints the contents of the file

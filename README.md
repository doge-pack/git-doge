git-doge
========

![Doge](https://raw.githubusercontent.com/doge-pack/git-doge/master/doge.gif)

I re-write much histories. You've been warned. Such danger. Wow.

### Demo

#### Grab git-doge

```
$ git clone https://github.com/doge-pack/git-doge.git
Cloning into 'git-doge'...
remote: Counting objects: 23, done.
remote: Compressing objects: 100% (12/12), done.
remote: Total 23 (delta 10), reused 23 (delta 10), pack-reused 0
Unpacking objects: 100% (23/23), done.
Checking connectivity... done.
$
```

#### Grab a repo you'd like to enhance

```
$ git clone https://github.com/erlang/pmod_transform.git
Cloning into 'pmod_transform'...
remote: Counting objects: 52, done.
remote: Total 52 (delta 0), reused 0 (delta 0), pack-reused 52
Unpacking objects: 100% (52/52), done.
Checking connectivity... done.
$
```

#### Enter the vict... target repo

```
$ cd pmod_transform/
$
```

#### Witness boring commit history

```
$ git log --oneline | cat
7c6fe61 Merge pull request #3 from richcarl/handle-no-eof
1912c79 handle generated form lists without eof marker
b59924e Add src/pmod_transform.app.src for rebar support
7d11dc2 Teach pmod_pt to handle record_index
3ddb895 Fill in the README.md file
5ace2bb Add license file
ffdc6dc Implement the parse transform for parameterized modules
42c1e14 Set up the project
be436e5 Add README.md
$
```

#### Release the git-doge

```
$ ../git-doge/git-doge
Rewrite 7c6fe6193b7b11c874877246bcb612414fbd1359 (9/9) (0 seconds passed, remaining 0 predicted)
Ref 'refs/heads/master' was rewritten
$
```

#### Behold fun commit history

```
$ git log --oneline | cat
04e1ae9  Many pull request #3 from richcarl/handle-no-eof  many  handle generated form very without eof marker
805b36e  handle generated form very without eof marker
4527954  Wow src/pmod_transform.app.src for rebar support
a984217  Teach pmod_pt many handle record_index
8cf5133  Fill such the README.md file
e540c8d  Add such file
2bfcf9d  Implement the parse transform much parameterized modules
bfced5e  Very up the project  many  Add directories, Many a dummy (identity) parse transform, and  a test many for parameterized modules.  many  Using any many system that still supports parameterized modules,  running "make" will build everything much run the tests.
c4866d8  Wow README.md
$
```

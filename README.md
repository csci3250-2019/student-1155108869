## Lau Tsz Yui

I am a new *developer*!

My hobby is:
* playing computer games
* reading
and much **more**!

### To-Do List
- [x] open repo
- [x] edit readme
- [x] push update using command line
- [ ] make a screenshot and update readme

#### About my gadgets

| Device      | When                |
| ----------  | ----------          |
| Xperia Z    | Secondary 1 - 2     |
| Redmi 1     | Secondary 2 - 5     |
| Iphone 6s+  | Secondary 5 - *now* |

## commands
`   or: git remote [-v | --verbose] show [-n] <name>
   or: git remote prune [-n | --dry-run] <name>
   or: git remote [-v | --verbose] update [-p | --prune] [(<group> | <remote>)...]
   or: git remote set-branches [--add] <name> <branch>...
   or: git remote get-url [--push] [--all] <name>
   or: git remote set-url [--push] <name> <newurl> [<oldurl>]
   or: git remote set-url --add <name> <newurl>
   or: git remote set-url --delete <name> <url>

    -v, --verbose         be verbose; must be placed before a subcommand

╭─ tom0034@DESKTOP-8L53NIG   ~/student-1155108869     master 
╰─ git remote
origin
╭─ tom0034@DESKTOP-8L53NIG   ~/student-1155108869     master 
╰─ git remote --help
╭─ tom0034@DESKTOP-8L53NIG   ~/student-1155108869     master 
╰─ git remote -v
origin  https://github.com/csci3250-2019/student-1155108869.git (fetch)
origin  https://github.com/csci3250-2019/student-1155108869.git (push)
╭─ tom0034@DESKTOP-8L53NIG   ~/student-1155108869     master 
╰─ cd ~
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ ls
csci2100  download  hello-git  install.sh  student-1155108869  tom0034.github.io
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ rm -rf csci2100
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ clear
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ git remote -v
fatal: not a git repository (or any of the parent directories): .git
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ mkdir csci2100
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ cs csci2100
zsh: command not found: cs
╭─ tom0034@DESKTOP-8L53NIG   ~ 
╰─ cd csci2100
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100 
╰─ git init
Initialized empty Git repository in /home/tom0034/csci2100/.git/
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git remote add https://github.com/csci3250-2019/student-1155108869.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=<push|fetch>]
                          set up remote as a mirror to push to or fetch from

╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git remote add origin https://github.com/csci3250-2019/student-1155108869.git
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git remote
origin
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git remote update
Fetching origin
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
From https://github.com/csci3250-2019/student-1155108869
 * [new branch]      master     -> origin/master
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ ls
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git pull --help
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git pull origin
You asked to pull from the remote 'origin', but did not specify
a branch. Because this is not the default configured remote
for your current branch, you must specify a branch on the command line.
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git fetch https://github.com/csci3250-2019/student-1155108869.git
From https://github.com/csci3250-2019/student-1155108869
 * branch            HEAD       -> FETCH_HEAD
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ ls
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git fetch origin
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git branch -r
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git pull origin master
From https://github.com/csci3250-2019/student-1155108869
 * branch            master     -> FETCH_HEAD
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ ls
README.md
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git add README.md
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master  
╰─ git commit -m "update readme"
[master 83c877f] update readme
 1 file changed, 22 insertions(+), 1 deletion(-)
 rewrite README.md (100%)
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git push -u origin master
Username for 'https://github.com': tom0034
Password for 'https://tom0034@github.com':
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 513 bytes | 513.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/csci3250-2019/student-1155108869.git
   e0375ef..83c877f  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─ git add README.md
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master  
╰─ git commit -m "update readme"
[master 8d4a389] update readme
 1 file changed, 2 insertions(+), 2 deletions(-)
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master  1 
╰─ git push -u origin master
Username for 'https://github.com': tom0034
Password for 'https://tom0034@github.com':
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 273 bytes | 273.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/csci3250-2019/student-1155108869.git
   83c877f..8d4a389  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
╭─ tom0034@DESKTOP-8L53NIG   ~/csci2100     master 
╰─`
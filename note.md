#Terms

Repository (Repo) (is a core)
Branch
Conflict
Local
Remote

#Commands

- git init
(and my project is git repository )

- git status(this command will be show you all status in you project )

- git add (help preparation save time point of project)
* nói chung là bấm git add thì file sẽ vào trạng thái chuẩn bị lưu

if git add tenfile -> just preparation this file
(* git add tenfile luu file đó)

(* git add . lưu toàn bộ file)

------
if you don't want to add but you was be add in git you can use command git reset to reset somethings saved before
- git reset
sài lệnh git reset để trả về những file đã cho vào chuẩn bị

- git commit: chinh thuc save
but you need command or note something you was
comment lai nhung gi da lam roi moi commit

- git commit -m ''

- git log -xem lich su luu commit
- git log --oneline(gọn hơn)

- git checkout {branch name} (chuyển đến nhánh)

-git branch (xem nhánh của cây)

- git checkout -b {branch name}
(tạo mới một nhánh)

- if you want merge
you switched to branch you want merge
use - git merge {namebranch}

- delete branch
- git branch -d {branch name}

- Khi đặt tên cho remote repository thì phải đặt cho giống tên project

- git push {url remote repository} {name branch}: lệnh giúp push project lên remote repository

Note: nhưng mỗi lần push ta lại phải copy url remote repository thì rất phiền
nên ta sẽ tạo 1 alius? thì gọi là đường hướng dẫn

hiểu như là tạo một từ ngắn để thay thế cho url dài

- git remote add {nameAlius} {url remote repo}

=======
sau khi đã tạo alius lệnh put sẽ như sau
- git push {name alius} {name branch}

- git clone {url remote}
1 vài lệnh của cmd
- cd "address folder" lệnh chuyển đến 1 folder trong Cd
- cd/d {name DC}: lệnh chuyển đến 1 ổ đĩa
- code . lệnh mở visual studio code
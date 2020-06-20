This project is just a demo how to use Git
//git init (tạo priject mới)
//git status
//git add
//git commit (git commit -m 'mo ta commit')

//git log (xem lich su commit)
//git show syntax: git show id-commit (show noi dung cua commit)
//git diff (difference) (xem nd nhung file modified)

//working directory (folder lam viec)
//staging area (khi commit thi cac file dang thay doi o 'working directory' se duoc add vao 'staging area')
//git repository

//gitk (open GUI\Graphic user interface)

//git checkout |syntax: git checkout --nameFile (delete modified of file chua len "staging area")
//git reset |syntax: git reset HEAD nameFile (de file tu "staging area" xuong "working directory")

//git checkout - b <name_branch> (branching) (tao branch)
//git checkout <branch> (switch branch)
//git merge (keo nhung thay doi cua branch nay vao branch khac)
ex: keo branch B vao A
-phai o branch A truoc (git branch A)
-git merge B

//git branch -D <name_branch> (delete a branch)

== dung git reset de undo commit
//git reset --soft <id commit> (dua ve staging area)
//git reset --mixed <id commit> (dua ve working directory)
//git reset --hard <id commit> (bo han cai commit chon)
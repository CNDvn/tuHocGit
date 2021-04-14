https://gitsheet.wtf/ 

This project is just a demo how to use Git
//git init (tạo project mới)
//git status
//git add
//git commit (git commit -m 'mo ta commit')

//git log (xem lịch sử commit)
//git show syntax: git show id-commit (show nội dung của commit)
//git diff (difference) (xem nội dung những file modified)

//working directory (folder làm việc)
//staging area (khi commit thì các file đang thay đổi ở 'working directory' sẽ được add vào 'staging area')
//git repository

//gitk (open GUI\Graphic user interface)

//git checkout |syntax: git checkout --nameFile (delete modified of file chưa lên "staging area")
//git reset |syntax: git reset HEAD nameFile (để file từ "staging area" xuống "working directory")

//git checkout - b <name_branch> (branching) (tạo branch)
//git checkout <branch> (switch branch)
//git merge (kéo những thay đổi của branch này vào branch khác)
ex: kéo branch B vào A
-phải đang ở trong branch A trước (git branch A)
-git merge B

//git branch -D <name_branch> (delete a branch)

== dung git reset de undo commit
//git reset --soft <id commit> (đưa về staging area)
//git reset --mixed <id commit> (đưa về working directory)
//git reset --hard <id commit> (bỏ hản cái commit đã chọn)

//git revert <id commit> (trả lại trạng thái lúc trước || bỏ một commit chỉ định, tức là quay trở lại nội dung trong file trước khi commit cái đó)

// .gitignore 

==Github
//git remote add origin link_repository
//git remote -v (show danh sách các remote repo)

//git push -u origin master (khi lần đầu push thì dùng câu lệnh này) (không được thì thử git push -f origin master)

//git config --global credential.helper store
// ^^^ not recommend (~/.git-credentitals) (lưu thông tin đăng nhập vào ổ cứng mà không mã hóa nên dễ bị lộ)

//git config --global credential.helper "cache --timeout=18000" (lưu vào ram vào ram == đến timeout là xóa)

//google "gnome-keyring" "git ssh"--timeout=18000

//git clone (git clone <Name'sRepository>)
//git pull (để tải các thay đổi trên git)

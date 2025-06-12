Repository(Repo) : Thư mục dự án(LearningGit)
Branch
Conflict
Local
Remote
# Command
- git init: khởi tạo repo
- git status
-git add: đưa file repo=>staging
-git reset: trả lại file từ staging=> repo
-git commit: đưa vào commitcommit
-git log: xem lịch sử commit => chỉ xem tên commit: git log --oneline
-git checkout id_commit: quay lại code commit mòng muốn
-git checkout Tên_Branch(master): quay về banch hiện tại
-git branch: xem branch hiện tại 
-git checkout -b {branch name}: Tạo mới branch
-git merge {brand name}: gộp brand vào m master
-git branch -d {branch name} hehe
-git push link_repoRemote tên_Branch: push repo_local => repo_remote(các lần push sau có thể thay link_repoRemote bằng tên tự đặt băng lệnh phía dưới)
-git remote add origin link_repoRemote
:wq:trình Vim (mặc định của Git) khi commit xung đột giữa 2  branch
-Đẩy branch lên remote_repo(chỉ lần đầu còn các lần sau chỉ cần git pushpush):
1-Tạo mới branch
2-git push -u link_remoteRepo(đã được đăth là origin) tên_Branch
-Tải branch mong muốn về :
1-git fetch origin
2-git checkout -b tên_branch origin/tên_branch



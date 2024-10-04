# Terms

Repository (Repo)
Branch
Conflict
Local
Remote

# Commands

- git init : Khởi tạo dự án

- git status : Kiểm tra trạng thái các file

- git add : Thêm file vào hàng chờ

- git reset : Hủy bỏ các file ở hàng chờ

<!-- ---------------------------------------- -->

- git commit -m '....' : Lưu lại file trong hàng chờ với thông điệp, lần đầu tạo('initial commit)

- git log : Xem lại các commit

- git log --oneline: Xem lại các commit 1 cách ngắn gọn gồm id và nội dung commit

- git checkout {id} : di chuyển đến thời điểm commit.
  Để quay trở lại thời điểm hiện tại dùng (git checkout {branchname}) tên nhánh chúng ta muốn đến

  <!-- ---------------------------------------- -->

- git branch : Kiểm tra nhánh hiện tại

- git checkout -b {branchname} : Tạo 1 nhánh mới và di chuyển đến nhánh đó

- git merge {branchname} : Hợp nhất nội dung nhánh branchname với nhánh hiện tại

- git branch -d {branchname} : Xóa đi 1 branch

- git commit : sử dụng sau khi xử lý conflict nhằm cập nhật lại merge

<!-- ---------------------------------------- -->

- git push {link repo} {branchname}

- git remote add origin {link repo} : lấy tên origin đại diện cho link repo

- git clone {link repo} : clone repo từ remote về local

- git push -u origin {branch name} : đẩy 1 nhánh lên github

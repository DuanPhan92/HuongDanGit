# Hướng dẫn đưa code trong 1 thư mục lên git
## 1. vào thư mục chứa code muốn update lên git
## 2. Mở terminal
## 3. sử dụng lệnh `git init` để khởi tạo git tại forder hiện tại
## 4. Sử dụng lệnh `git status` để kiểm tra xem có file nào thay đổi không
## 5. Sử dụng lệnh `git add *` để cập nhật tất cả các thay đổi hiện tại
## 6. Sử dụng lệnh `git commit -m "first commit" để update command lên git`
## 7. sử dụng lệnh `git remote add origin https://github.com/DuanPhan92/LastTest.git` để cài đặt đường dẫn đến máy chủ git cần lưu
## 7. sử dụng lệnh nếu cần thay đổi reponsitory`git remote set-url origin git@your.git.repo.example.com:user/repository2.git`
## 8. Sử dụng lệnh `git push origin master` để đưa code lên git, chú ý nếu bị lỗi thì sử dụng thêm tùy chọn force ở cuối <br /> `git push origin master --force`

## các lần sau nếu có thay đổi code chỉ cần thực hiện từ bước 4.5.6.8 là đủ

# Hướng dẫn kéo code từ git về máy tính
## 1. vào thư mục chứa code muốn kéo git về
## 2. Mở terminal
## 2. sử dụng lệnh `git clone tênusername@github.com:DuanPhan92/LastTest.git` để kéo code về

cau hinh git
$ git config --global user.name "John Doe"
$ git config --global user.email "johndoe@example.com"

file cau hinh tai:
~/.gitconfig

# Terms

Repository (Repo)
Branch
Conflict
Local
Remote

# Commands

- Làm dự án của ta trở thành 1 git repository
- git init

- Cho cta thấy được trạng thái của dự án
- git status

- Cho cta lưu lại thời điểm hiện tại của dự án
- git add + tên file => VD: git add index.html
- git add . => lưu lại tất cả file

- Lấy lại file chuẩn bị lưu
- git reset

- Lưu lại file
- git commit -m "Tên commit"

- Xem lại các lần commit
- git log
- git log --oneline

- Chuyển sang 1 commit nào đó:
- git checkout + id của commit. VD: git checkout 85e620b

- Chuyển về ban đầu:
- git checkout {brand name} => VD: git checkout master

- Tạo 1 nhánh mới
- git checkout -b {brand name}

- Merge các nhánh
- git merge {brand name}

- Xóa 1 nhánh
- git branch -d {brand name}

- Đẩy lên remote
- git push 

- Tạo 1 nhánh từ local sau đó đẩy lên remote
- git push -u origin {brand name}

- Lấy 1 nhánh từ trên remote xuống
- git fetch origin
- git checkout -b {brand name} origin/{brand name}

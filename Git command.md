1. mkdir : Tạo một folder mới
2. type con > null newFile.txt : tạo một file mới trong folder
3. copy con file.txt : thêm nội dung vào file
4. git init : tạo một khối lưu trữ trong folder
5. git add [--all] thêm toàn bộ file , [file.txt] thêm file vào cây làm việc
6. git commit -m "Something" : bắt đầu commit lên
7. git checkout <branch_name> : chuyển sang branch branch_name nào đó
8. git remote add origin <link_to_the_repo> : remote lên github 
9. git push -u origin master : không chỉ đẩy thay đổi mà còn thiết lập branch `main` trên máy local để tracking `main` trên remote 
10. git push origin master : đẩy các thay đổi từ main trên local lên branch `main` mà không cần thiết lập tracking giữa hai branch
11. git log : xem lịch sử git
12. git checkout <code_to_the_log> : quay trở về lệnh tại thời điểm đó
13. git checkout -b new-branch : tạo một branch mới
14. git branch : xem tất cả các branch
15. git pull origin <branch_name>: kéo về máy local của bạn
16. git merge <another_branch> : hợp file từ branch mà đưa pull request tới (quay trở lại lệnh 10 để đưa file từ branch này sang branch của bạn)
Nếu có 1 file thay đổi
17. git status : xem tình trạng file -> quay lại lệnh 5 để thêm tệp đã thay đổi để push lên -> quay lại lệnh 6 -> lệnh 10 để đưa lên (đảm bảo phải hoạt động đúng branch)
-u là upstream để cấu hình liên kết, lần sau không cần phải rõ git push origin nhanh-1 mà chỉ cần git push
chỉ có thể xóa nhánh ở local được khi không còn commit nào chưa push trên nhánh đó, dùng -D để xóa nhánh mà không cần quan tâm commit

<!-- di chuyen giua cac nhanh -->
git log / git log --oneline dùng q để thoát
git checkout địa chỉ để chuyển HEAD về commit đó

<!-- merge -->
git merge: đứng ở nhánh muốn lưu (main), git merge nhanh-1 (đem nhánh 1 về main)

<!-- sua noi dung commit -->

commit moi nhat: git commit --amend
commit cu: git rebase -i id_commit_cu (truoc commit muon sua)

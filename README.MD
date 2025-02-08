Learn how to use git and github

HEAD không phải là nhánh mà là con trỏ thôi

-u là upstream để cấu hình liên kết, lần sau không cần phải rõ git push origin nhanh-1 mà chỉ cần git push
chỉ có thể xóa nhánh ở local được khi không còn commit nào chưa push trên nhánh đó, dùng -D để xóa nhánh mà không cần quan tâm commit

git log / git log --oneline dùng q để thoát
git checkout địa chỉ để chuyển HEAD về commit đó

git merge: đứng ở nhánh muốn lưu (main), git merge nhanh-1 (đem nhánh 1 về main)

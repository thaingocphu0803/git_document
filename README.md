<h3 align="center">GIT DOCUMENT</h3>

1. **git init** tạo git respository ở local.
2. **git remote add origin <remote_url>** kết nối respository ở local với respository trên git.
3. **git checkout -b <branch_name>** tạo một nhánh mới từ trạng thái của nhánh hiện tại nhánh hiện tại.
4. **git checkout <branch_name>** chuyển sang nhánh đã có.
5. **git status** xem các file thay đổi trong branch hiện tại.
6. **git add .** thêm tất cả các file đã thay đổi vào stage area để chờ commit.
7. **git commit -m "<description>"** lưu các thay đổi đã đưa vào stage area. Lưu ý: commit lần đầu phải dùng **git commit -m**.
8. **git push origin <branch_name>** đẩy các commit từ local respository lên remote respository.
9. **git branch -D <branh_name>** xóa branch cụ thể ở local.
10. **git pull origin <branch_name>** kéo code mới nhất từ remote branch về local.
11. **git commit --amend** gộp thay đổi mới vào commit trước đó. Lưu ý: nên sử dụng tù lần commit thứ 2.
12. **git push origin <branch_name> -f** force update lênh remote branch đã tồn tại với lịch sử commit mới. Lưu ý: sử dụng từ lần push thứ 2 trên cùng 1 nhánh.
13. **git log --online -n5** hiển thị 5 git log gần nhất.
14. **git reflog --no-abbrev** truy tìm hoặc quay lại trạng thái trước đây của repository mà không lo bị mất thông tin commit.
15. **git rebase --continue** tiếp tục quá trình rebase sau khi giải quyết xong conflict.
16. **git rebase --abort** hủy bỏ toàn bộ quá trình rebase và quay lại trạng thái trước khi rebase.
17. **git rebase <branch_name>** đưa code của branh chỉ định vào branch hiện tại.
18. **git remote rm origin** xóa tất cả remote kết nối với local.
19. **git remote add origin <remote_name> <commit_hash>**: khôi phục lại branch đã xóa với commit hash.
20. **git chery-pick <commit_hash>** chọn 1 commit cụ thể và áp dụng vào nhánh hiện tại. Lưu ý: nếu muốn chọn nhiều nhánh thì mỗi commit hash cách nhau bằng khoảng trắng hoặc **<commit_hash_start>^..<commit_hash_end>** và Sau khi chery-pick xong chỉ cần push.
21. **git chery-pick -m 1 --no-commit <commit_hash_start>^..<commit_hash_end>** chọn các commit cụ thể và áp dụng vào nhánh hiện tại trong trường hợp 1 số commit bị pull request. Lưu ý:  Sau khi chery-pick xong phải add và commit lại rồi mới push.
22. **git remote remove origin** xóa remote hiện tại ở local 



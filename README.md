Câu 1: Tạo thư mục baitap trong home
<img width="952" height="508" alt="Screenshot_20260629_091012" src="https://github.com/user-attachments/assets/5fe3e75e-b8c3-48e6-b861-34a9f4990995" />
Câu 2: Xem nội dung tập tin etc/passwd
- Sử dụng lệnh "kate /etc/passwd"
<img width="1920" height="1056" alt="Cau2" src="https://github.com/user-attachments/assets/44e9ad84-36f3-4ac7-8d40-6bc569067336" />
Câu 3: Không có user nào có uid=100, gid=100

Câu 4: Nội dung tập tin etc/group
- Sử dụng lệnh "kate /etc/group"
<img width="1920" height="1056" alt="Cau4" src="https://github.com/user-attachments/assets/d5f7b5e5-c0d7-46fe-a070-4e54f1d5c240" />
Câu 5: Tạo các nhom hocvien, admin, user
- Sử dụng lệnh "sudo groupadd hocvien, admin, user"
<img width="952" height="549" alt="Cau5" src="https://github.com/user-attachments/assets/c22db9af-391e-4ea5-bf6c-4fd1f766a800" />
Câu 6: Tạo các người dùng
- Sử dụng lệnh "sudo useradd -g -m hocvien hv1,hv2,hv3"
- Sử dụng lệnh "sudo useradd -g -m user user1,user2"
- Lệnh đổi password "echo"$user:123456 | sudo chpasswd"
<img width="952" height="549" alt="Cau6" src="https://github.com/user-attachments/assets/f15b9fb5-2a35-4e9a-a5fc-a4f985f2706a" />
Câu 7: Hủy người dùng
- Lệnh xoá người dùng "sudo userdel -r hv3"
<img width="952" height="549" alt="Cau7" src="https://github.com/user-attachments/assets/a3a6afb8-52a1-4f30-8883-9a31ace831a4" />
Câu 8: Cấp quyền cho tập tin dsuser
- Cấp quyền tập tin dsuser dùng lệnh "chmod 640 /home/kvasir/baitap/dsuser"
<img width="929" height="570" alt="Cau8" src="https://github.com/user-attachments/assets/e50bbf69-7849-4545-9f14-09f3ff395c08" />
Câu 9: Tạo quyền hạn mặc định
- Tạo quyền mặc định sử dụng lệnh "umask 027"
<img width="929" height="570" alt="Cau9" src="https://github.com/user-attachments/assets/4a79c927-bd13-49e6-adeb-8c1863248265" />
Câu 10: Đăng nhập user1 và truy cập dsuser
- Đăng nhập user1 và truy cập dile dsuser báo không có quyền do dsuser chỉ cấp quyền đọc cho owner và group, còn user1 là other nên không có quyền
<img width="929" height="570" alt="Cau10" src="https://github.com/user-attachments/assets/ef675029-ea62-4752-942c-d874285fc529" />

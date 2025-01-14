
# Các lệnh sử dụng:

1.  ls -al ~/.ssh (lệnh này để kiểm tra xem máy của bạn có ssh key nào chưa)
2. ssh-keygen -t rsa -b 4096 -C "mailcuaban@abc.com" (dùng để sinh một ssh key mới)
3. eval "$(ssh-agent -s)" (dùng để đảm bảo rằng ssh-agent đã được kích hoạt)
4. ssh-add ~/.ssh/id_rsa (Thêm ssh key của bạn vào ssh-agent)
5. cat ~/.ssh/id_rsa.pub (show nội dung file)

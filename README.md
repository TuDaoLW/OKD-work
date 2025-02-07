# Cài đặt OKD (Openshift community version) - UPI trên môi trường ảo hóa

1. Mô hình

![image](https://github.com/user-attachments/assets/ea01f27c-311c-43a9-a7bb-29ff324fe96d)

Tài nguyên & số node tối thiểu:
  - 1x Bootstrap: 4cpu 16G ram 100G disk (loại bỏ sau khi cài)
  - 1x Master: 4cpu 16G ram 80G disk 
  - 0x Worker: 2cpu 6G ram 60G disk
  - 1x service node: 1cpu 2G ram 200G disk
    
2. Chuẩn bị
Cài đặt các dịch vụ cần thiết cho cụm OKD trên service node
- DNS, DHCP, NFS, HAproxy, firewall,...
3. Cài đặt 









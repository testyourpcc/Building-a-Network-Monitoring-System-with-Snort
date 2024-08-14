# Building-a-Network-Monitoring-System-with-Snort
Building a Network Monitoring System with Snort
- Xây dựng mô hình mạng sử dụng Winserver, pfsense, Ubuntu, Windows 10 Professional.
- Thiết lặp các hệ thống trong mạng AD-DS, LDAP, Domain, Web server, DHCP server, DNS server...
- Thiết lặp và cài đặt rule cho pfsense Nat, Allow, Block traffic, OpenVPN,...
- Cài đặt và cấu hình Snort trên firewall Pfsense, custom rules phát hiện tấn công, gửi cảnh báo về Graylog server
- Cấu hình Nginx, WinSCP, Filebeat, Task Schedule,... để chuyển log sang Graylog Server.
- Tạo Alert, Dashboard, gửi mail alert về email từ Graylog Server.
- Triển khai tấn công thử nghiệm 3 loại tấn công: DoS Attack, SQL injection, Brute Force SSH Attack.
- Cấu hình để gửi cảnh báo khi bị tấn công.
# Mô hình hệ thống
![image](https://github.com/user-attachments/assets/41b39d37-1603-40d7-92df-7b9d8d4771dd)
# Rule Snort
![image](https://github.com/user-attachments/assets/d7a2fa54-aef1-4db2-aa52-153bfab89c26)
# Build Web
## Build Artifact sử dụng maven
![image](https://github.com/user-attachments/assets/ee00029b-3df2-44c2-908d-7c3c5b3337dd)
## Web application
![image](https://github.com/user-attachments/assets/cc5119fe-62c9-43e1-8369-3925b67d891e)
# Cấu hình Alert trên Graylog
![image](https://github.com/user-attachments/assets/caa3571b-54e9-4243-9101-cdeb6659110c)
# Thử nghiệm các dạng tấn công và gửi cảnh báo
## Tấn công DoS
![image](https://github.com/user-attachments/assets/c7c1a924-2c20-4b15-baad-7291029f4bb0)
### Alert trên Graylog
![image](https://github.com/user-attachments/assets/5624442e-3054-4406-9018-eb33002f011e)
### Email cảnh báo từ Graylog
![image](https://github.com/user-attachments/assets/423df30f-b2d7-4b38-a6a8-924342947b6f)
## Tấn công Brute Force SSH
![image](https://github.com/user-attachments/assets/4008b85c-e90a-4331-b50c-3e10038ed887)
## Tấn công SQL Injection
![image](https://github.com/user-attachments/assets/f3cd2a36-fee1-4e6d-a271-bdb1e0ec90ff)



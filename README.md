
<p align="center">Xin Chào</br><b>

---
## Ubuntu trên Termux Android

---
• Cài đặt ứng dụng trên Android
- [x] [Termux](https://apkcombo.com/id/termux/com.termux)
- [x] [Vnc Viewer](https://play.google.com/store/apps/details?id=com.realvnc.viewer.android)

## Cài đặt

Sao chép và dán lệnh này vào Termux:
</br>
<summary><b><code>Install Ubuntu</code></b></summary>

* Ubuntu 24.04 (Noble Numbat)
```
pkg install wget -y ; wget https://raw.githubusercontent.com/bjendaik/ubuntutermux/main/install.sh ; chmod +x install.sh ; ./install.sh
```

Chạy Ubuntu
```
ubuntu
```

* Dừng Ubuntu
```
exit
```

* Xóa Ubuntu
```
rm -rf ubuntu-fs
```

---
Các lệnh cơ bản Ubuntu
> apt update : Cập nhật gói danh sách.</br>
> apt upgrand: Gói nâng cấp.</br>
> apt search (pkg): Gói tìm kiếm.</br>
> apt install (pkg): Gói cài đặt.</br>
> apt autoremove (pkg): Xóa gói.</br>
> apt -h : Giúp tất cả các lệnh.

---
## Môi trường máy tính để bàn

trên Ubuntu, chạy lệnh này :

</br>
<summary><b><code>Cài đặt Desktop Xfce</code></b></summary>
<p align="center"><img src="https://raw.githubusercontent.com/wahasa/Ubuntu/main/Images/xfce.jpg"</p>

```
apt install wget -y ; wget https://raw.githubusercontent.com/bjendaik/ubuntutermux/main/xfce.sh ; chmod +x xfce.sh ; ./xfce.sh
```

---
Tính năng
- [x] Sửa lỗi Âm thanh
- [x] Truy cập vào Sdcard
- [x] Đã khắc phục sự cố trình duyệt
- [x] Cài đặt ứng dụng [Click here,.](https://github.com/wahasa/Ubuntu/tree/main/Apps)


---
## Trình xem VNC

* Khởi động máy chủ VNC

trên Ubuntu, hãy chạy lệnh này để bắt đầu
```
vnc-start
```

* Mở Vnc Viewer

Thêm (+) VNC Client để kết nối, điền:

Địa chỉ
```
localhost:1
```

Tên
```
Ubuntu Desktop
```

Để ngắt kết nối VNC Client, nhấp vào (X) ở bên phải.

* Dừng máy chủ VNC

trên Ubuntu, chạy lệnh này để dừng:
```
vnc-stop
```
</br>

---
<p align="center">Chúc may mắn</p>

---

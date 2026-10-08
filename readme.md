# DevOps Hackathon - Đề 003: Quản lý công việc (Task)

## 1.Thông tin sinh viên
|Họ và tên       | Mã sinh viên  | Lớp          | Tài khoản Linux    |Github                                                       | Cổng Linux    |
|----------------|---------------|--------------|--------------------|-------------------------------------------------------------|---------------|
| Bùi Thái Sơn   | B24DTCN274    | HN-K24-CNTT2 | sonbui-k24cntt2    | github.com/buithaison17/devops-hackathon-de003-buithaison   | 8081          |
|----------------|---------------|--------------|--------------------|-------------------------------------------------------------|---------------|

## 2.Môi trường triển khai
- Hệ điều hành: Ubuntu.
- Phiên bản Nginx: 1.28.3
- Phiên bản git: 2.53.0
- Nơi chạy: Máy ảo VPS

## 3. Cấu trúc dự án

## 4. Cấu hình Nginx
- Port : 8081 cổng công khai
- server_name: 221.121.4.43 địa chỉ máy chủ
- index_file: index.html file html muốn hiển thị
- web_root /var/www/devops-hackathon-de003/buithaison/src tên đường đẫn tới file html
- ten_tai_khoan: sonbui-k24cntt2 tên tài khoản linux

## 5. Tưởng lửa
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw allow 22/tcp
sudo uwfw allow 8081/tcp

##6. Các câu lệnh triển khai
    1  sudo apt install -y ufw nginx git curl
    2  git config --global user.name "buithaison17"
    3  git config --global user.email "thaisonb936@gmail.com"
    4  sudo ufw default deny incoming
    5  sudo ufw default allow outgoing
    6  sudo ufw 22/tcp
    7  sudo ufw allow 22/tcp
    8  sudo ufw allow 8081/tcp
    9  sudo ufw enable
   10  sudo mkdir /www/var
   11  sudo mkdir -p /www/var
   12  sudo cat /www/var/index.html
   13  clear
   14  sudo nano /etc/nginx/sites-available/sonbui-k24cntt2.conf
   15  sudo ln -s /etc/nginx/sites-available/sonbui-k24cntt2.conf /etc/nginx/sites-enabled/
   16  sudo nginx -t
   17  sudo nano /etc/nginx/sites-available/sonbui-k24cntt2.conf
   18  sudo nginx -t
   19  sudo nano /etc/nginx/sites-available/sonbui-k24cntt2.conf
   20  sudo nginx -t
   21  sudo rm /etc/nginx/sites-enabled/default
   22  nginx systemctl reload nginx
   23  sudo systemctl reload nginx
   24  sudo ufw status
   25  lear
   26  clear
   27  sudo nginx -t
   28  sudo systemctl status nginx
   29  sudo ufw status verbose
   30  cd /var/www
   31  git clone https://github.com/buithaison17/devops-hackathon-de003-buithaison
   32  sudo git clone https://github.com/buithaison17/devops-hackathon-de003-buithaison
   33  ls
   34  cd html
   35  ls
   36  cd ..
   37  ls
   38  cd devops-hackathon-de003-buithaison/src
   39  ls
   40  cd ~/
   41  sudo nano /etc/nginx/sites-available/sonbui-k24cntt2.conf
   42  sudo sytemctl reload nginx
   43  sudo systemctl reload nginx
   44  cd /var/www
   45  ls
   46  cd devops-hackathon-de003-buithaison
   47  sudo git pull
   48  nginx --vesion
   49  nginx --version
   50  nginx --v
   51  nginx -v
   52  git -v
   53  clear
   54  history


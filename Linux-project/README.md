# Linux Projects

This folder contains Linux-based system administration projects. These focus on working with *CentOS Stream 9*, web server setup, firewall configuration, and basic hosting techniques.

## ✅ Project: Creating a Website on Linux (CentOS Stream 9)

### 📌 Tasks Included:
- Installing and configuring Apache HTTP Server (httpd)
- Placing HTML files in /var/www/html
- Setting permissions for hosted content
- Enabling the firewall to allow HTTP/HTTPS traffic
- Verifying website access using IP

👉 [Click here to download the full project file](./Linux_Website_Project.pdf)

### 💡 Commands Used:
```bash
sudo dnf install httpd
sudo systemctl start httpd
sudo systemctl enable httpd
sudo firewall-cmd --add-service=http --permanent
sudo firewall-cmd --reload
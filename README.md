# Day 1: Linux Web Server with Nginx

## What I Built
- Provisioned an Ubuntu Linux environment in GitHub Codespaces.
- Installed and started the **Nginx** web server on Port 80.
- Replaced the default Nginx root page () with a custom HTML page.
- Verified HTTP  responses locally via  and exposed Port 80 in the browser.

## Commands Used
```bash
sudo apt update && sudo apt install nginx -y
sudo service nginx start
curl -I http://localhost
```

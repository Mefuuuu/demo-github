  # 1. Setup git

Setup user and email:

    Open the command line.

    Set your username:
    git config --global user.name "FIRST_NAME LAST_NAME"

    Set your email address:
    git config --global user.email "MY_NAME@example.com"  

# 2. Tạo clone với git

- Clone 1 project có sẵn => git clone link_https
- Tạo 1 project trên github:

      1. Tạo 1 github repository (folder): nơi chứa code
      2. Clone với project này: git clone link_your_repo
      3. Viết code:
      git status (kiểm tra trạng thái các file)
      git add . (thêm file)
      git commit -m "your_message" (tạo nội dung commit)
      git push origin main

- Tạo project local và đẩy lên github

      1. Tạo 1 github repository (folder): nơi chứa code
      2. git init
      3. Viết code:
      git status (kiểm tra trạng thái các file)
      git add . (thêm file)
      git commit -m "your_message" (tạo nội dung commit)
      git remote add origin https://...
      git push origin master

# 3. Https vs ssh  
ssh-keygen -t ed25519 -C "your_email@example.com"

# 4. Sơ đồ hoạt động github
![image](https://github.com/Mefuuuu/demo-github/assets/133778142/a4215f2c-d49b-4ddc-b006-468fdae562b0)


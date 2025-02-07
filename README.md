## Hi there 👋
<!--
**TheoX865/theox865** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# Untuk Ubuntu/Debian:
  sudo apt update && sudo apt install python3 python3-pip

  # Untuk macOS (via Homebrew):
  brew install python@3.12

  # Untuk Windows: Unduh installer dari situs resmi Python.

  pip3 install PyGithub requests

  git config --global user.name "theox865"
  git config --global user.email "theox865@gmail.com"
from github import Github

token = "https://github.com/theox865/$theox865.git"  # Ganti dengan token Anda
repo_name = "https://github.com/theox865/$theox865.git"

# Autentikasi dan buat repository
g = Github(token)
user = g.get_user(theox865)
repo = user.create_repo(name=repo_https://github.com/theox865/thoex865, private=False, description="Repo dibuat via Python")
print(f"Repository {repo.name} berhasil dibuat: {repo.html_url}")
import requests

token = "ghp_AbCdEf..."
api_url = "https://api.github.com/theox865/repos"
headers = {"Authorization": f"Bearer {token}"}
data = {"theox865": "https://github.com/theox865/$theox865.git ", "description": "Repo via API"}

response = requests.post(api_url, json=data, headers=headers)
if response.status_code == 201:
    print("Repository berhasil dibuat!")
else:
    print(f"Gagal: {response.json()}")

    #!/bin/bash

# Input dari pengguna
read -p ": "https://github.com/theox865/$theox865.git repo_name
read -p "Masukkan deskripsi: " description

# Jalankan script Python
python3 - <<EOF
from github import Github
token = "  https://github.com/theox865/$theox865.git  "
g = Github(theox865)
repo = g.get_user().create_repo(name="$theox865", description="$description")
print(f"Repository dibuat: {repo.html_url}")
EOF

# Inisialisasi Git lokal
mkdir "$theox865"
cd "$theox865"
git init
touch README.md
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin "https://github.com/theox865/$theox865.git"
git push -u origin main
echo "# Proyek Baru" > README.md
   git add . && git commit -m "Update README" && git push
ssh-keygen -t ed25519 -C "email@example.com"
  eval "$(ssh-agent -s)"
  ssh-add ~/.ssh/id_ed25519
  echo "venv/" >> .gitignore
  echo "__pycache__/" >> .gitignore
  
  

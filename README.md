### 初回同期用コマンドセット（README自動作成版）

### 

### \# ① 新しいフォルダへ移動

### cd "/c/Users/kohei/Desktop/新しいフォルダ名"

### 

### \# ② Git管理を開始

### git init

### 

### \# ③ README.mdを作成（中身は適当でOK）

### echo "# 新しいフォルダ名" > README.md

### 

### \# ④ ファイルをステージングして初回コミット

### git add -A

### git commit -m "初回コミット"

### 

### \# ⑤ ブランチ名をmainに変更

### git branch -M main

### 

### \# ⑥ GitHubリポジトリと接続（URLは作成したリポジトリのものに変更）

### git remote add origin https://github.com/HamachiWrong/新しいリポジトリ名.git

### 

### \# ⑦ 初回アップロード

### git push -u origin main

### 

### 初回同期用コマンドセット（README自動作成版）

### git pull

### git add -A

### git commit -m "変更内容"

### git push


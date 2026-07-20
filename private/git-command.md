

#### 1. 初期化とコミット
```
bash
git init
git add .
git commit -m "Initial commit"
```

#### 2. リモートリポジトリの登録とプッシュ
```
bash
git remote add origin https://github.com
git branch -M main
git push -u origin main
```

#### 3. 次回以降
```
git add .
git commit -m "commitメッセージ（何をどうしたか）"
git push -u origin main
```
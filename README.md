# Dockerで構築するPython3の環境
## 概要
### 1. コンテナ起動
```
docker-compose up -d --build
```
### 2. コンテナへ接続
```
% docker exec -it python3 /bin/bash
# ls
sample.py
```
### 3. プログラムの実行
```
# python sample.py
```
### 4. コンテナの削除
```
% docker-compose down
```

# 2023_solution_develop
23年度 IPUT ソリューション開発 IoT‐Video班

## 環境構築
### 初回起動
```bash
docker compose build


```

### backend
Go言語
```
docker compose up -d #Docker立ち上げ
compose exec solution_develop sh #コンテナ内へ移動
cd src/solution_develop/ #作業ディレクトリへ移動(書かなくてもいいように要改善)
```

### frontend
Next.js + TypeScript
```
docker compose exec frontend sh
npm install #初回のみ
npm run dev
```
 

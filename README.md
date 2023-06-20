# 使い方

1. 証明書の発行のために、mkcertをinstall
```bash
# mkcertのインストール
brew install mkcert

# ローカルCA(認証局)のインストール
mkcert -install

# 認証書の生成
mkcert localhost
```

2. Next.jsの開発サーバーを起動
```bash
npm run dev
```

3. リバースプロキシを起動
```bash
node reverse-proxy.js
```

4. `https://localhost:3100`にアクセス

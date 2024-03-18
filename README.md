# jitsulina-lab
- 実務で使えるLinuxの演習環境

## 演習ガイド
- TBW
### 演習ガイド執筆用環境のビルド
- install node.js and npm on your OS or container

- install yarn 
```
cd guide && sudo npm install -g yarn
```

- install vuepress
```
yarn add -D vuepress
```

### 執筆中の動作確認
```
yarn dev
```

### 公開用ページのビルド
- docsディレクトリに成果物を出力
```
yarn build
```

- if you get SSL error, run below instead.
```
NODE_OPTIONS='--openssl-legacy-provider' yarn build
```

## 演習環境
### OS
- TBW
### HyperVisor
- Hyper-V

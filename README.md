# Test for stock-manage-system

## 参考にした記事

下記の URL をご覧ください。
- https://qiita.com/Kyou13/items/be9cdc10c54d39cded15


## ディレクトリ構造

```bash
├── back
│   ├── Dockerfile
│   ├── Gemfile
│   └── Gemfile.lock
│
├── front 
│    └── Dockerfile
├── docker-compose.yaml
```

## Front 技術選定まとめ

- JS 主要ライブラリ : Vue
- 状態管理 : Vuex
- AltJS : TypeScript
- Style : tailwind? vuetify?
- Code Formatter : Prettier
- 静的解析ツール : ESLint
- タスク管理ツール : GitHub

## その他
githubなどから初めてローカルに持ってきた場合は以下の手順でプロジェクトを開始します
```bash
$ docker-compose run front npm install
$ docker-compose up
```

課題用の RESAS API を使ったアプリ

## 使い方

https://opendata.resas-portal.go.jp/ から API キーを取得してください
取得後、API キーを src 配下に Api.js を作り、export してください。

```
export default 'APIキー'
```

必要なパッケージは`npm install`でインストールしてください。

その後、`yarn start`で http://localhost:3000/にアクセスするとアプリが起動します。

### `yarn start`に関して

今回は yarn を利用しています。
もし npm でアプリを起動したい場合は package.json を編集してください。

###　補足
当初、heroku アップも検討していたため、コミットメッセージに heroku アップに関する部分がありますが、不要だと気がついたので今回 heroku アップはしていません。
必要であればアップします。

以上。

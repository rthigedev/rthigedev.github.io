# GitHub Pages のブログ

http://rthigedev.github.io のブログのファイル。

## ファイル構成

_config.yml ...タイトルとか
index.markdown ...トップページ

## ローカルでテストする方法

```
cd myblog\rthigedev.github.io
bundle exec jekyll serve
```

ブラウザで http://127.0.0.1:4000/ を開く

## Githubで公開する方法

ローカルでVS Codeなどでコミットして、Githubにプッシュする。

コマンドでも（たぶん）いける。
```
git add .
git commit -m "update"
git push origin main
```

これで、http://rthigedev.github.io が更新される。   
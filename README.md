## RailsとReactでSPA開発するのUber_Eatsのクローン

### 新規プロジェクト作成
- Rails
```
$ rails new uber-eats-like --api
```

- React
Railsのディレクトリの中に入る
```
# このようなディレクトリがあることを確認します。
$ ls
Gemfile      README.md    app          config       db           lib          public       test         vendor
Gemfile.lock Rakefile     bin          config.ru     log          storage      tmp
```
- frontendという名前でReactアプリケーションを構築
```
$ npx create-react-app frontend
```



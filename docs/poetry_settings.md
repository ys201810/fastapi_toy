## poetryの設定手順
1. 利用したいディレクトリに移動
```
$ cd fastapi_toy
```

2. 利用したいpythonのインタプリタを使用できるようにする。
```
$ pyenv versions
$ pyenv global 3.9.11  # example
```

3. セットアップ
```
$ poerty init
```

4. poetry環境をactivateしてインタプリタを確認
```
$ poetry shell
$ which python
```

5. モジュールインストール
```
# fastapiとuvicornをインストール
$ pip install fastapi uvicorn
```


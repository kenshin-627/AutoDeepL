# AutoDeepL

<details><summary>準備</summary>

1. クリップボードを利用するためのライブラリをインストール`pip install pyperclip`
2. DeepLのAPIを利用するためのライブラリをインストール`pip install --upgrade deepl`
3. DeepL APIにクレジットカード情報を登録して，認証キーを発行する． (https://www.deepl.com/ja/pro-api?cta=header-pro-api/)
4. settings.pyを作成し認証キーを設定する
```python:settings.py
AUTH_KEY = "1.で発行した認証キー"
```
</details>

<details><summary>使い方</summary>

1. auto_translate.ipynbを実行
2. 翻訳したい英文をコピー
3. 翻訳後の文がクリップボードにコピーされてるのであとは好きなように
4. 2,3を繰り返す
</details>
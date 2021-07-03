# mkdocs-examples

MkDocs の使用例

## 実行環境

- Node.js 16.4.1
- Python 3.9.6

asdf がある場合、以下のコマンドでインストール可能

```bash
asdf plugin-add nodejs \
    ; asdf plugin-add python \
    && asdf install
```

## 実行方法

### 依存パッケージのインストール

```bash
npm install \
    && pip install --requirement requirements.txt
```

### ローカル環境での起動

```bash
mkdocs serve
```

ブラウザで `http://0.0.0.0:8000/` にアクセスする

## 編集方法

静的解析の自動実行を設定する

```bash
pre-commit install
```

feature ブランチを切り、コミット、プッシュ、プルリクエストを行う

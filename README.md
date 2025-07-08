# Easy Site

これはDjangoフレームワークを使用して構築されたシンプルなWebアプリケーションです。
基本的なユーザー認証機能（ユーザー登録、ログイン、ログアウト）を備えています。

## 主な機能

-   ユーザー登録
-   ログイン / ログアウト
-   ログインユーザー向けのホームページ
-   シンプルなCSSによるスタイリング

## 動作環境

-   Python 3.x
-   Django 5.2
-   その他必要なパッケージは `requirements.txt` を参照してください。

## セットアップ手順

1.  **リポジトリをクローンします**
    ```bash
    git clone https://github.com/your-username/easy-site-django.git
    cd easy-site-django
    ```

2.  **Python仮想環境を作成し、有効化します**
    ```bash
    # Windowsの場合
    python -m venv venv
    venv\Scripts\activate

    # macOS / Linuxの場合
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **必要なパッケージをインストールします**
    ```bash
    pip install -r requirements.txt
    ```

4.  **データベースのマイグレーシ��ンを実行します**
    （これにより、ユーザー認証に必要なテーブルなどが作成されます）
    ```bash
    python manage.py migrate
    ```

5.  **開発サーバーを起動します**
    ```bash
    python manage.py runserver
    ```

6.  **ブラウザでアクセスします**
    Webブラウザを開き、 `http://127.0.0.1:8000/` にアクセスしてください。

## 使い方

-   **トップページ:** `http://127.0.0.1:8000/`
-   **ユーザー登録:** `http://127.0.0.1:8000/accounts/signup/`
-   **ログイン:** `http://127.0.0.1:8000/accounts/login/`

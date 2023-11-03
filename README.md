# satellite-simulator

衛星教材用のシミュレータ（試験的作成中）

## 開始方法

以下の指示に従い、開発用のローカルコピーをセットアップしてください。

### 前提条件

このプロジェクトを実行する前に、Python 3.8以上がインストールされていることを確認してください。

### インストール

リポジトリをクローンし、必要な依存関係をインストールしてください。

```bash
# リポジトリをクローンする
git clone https://github.com/your-username/satellite-simulator.git
cd satellite-simulator

# 仮想環境を作成する
python -m venv venv

# 仮想環境をアクティベートする
# Windowsの場合
venv\Scripts\activate
# macOSとLinuxの場合
source venv/bin/activate

# 必要なパッケージをインストールする
pip install -r requirements.txt
```

## 開発の始め方

共同開発者は以下の手順でプロジェクトに参加できます。

1. リポジトリをフォークして、自分のGitHubアカウントにコピーします。
2. 新しいブランチを作成して機能開発やバグ修正を行います。
3. テストを実行して、変更が既存の機能に影響を与えていないことを確認します。
4. 完了したら、プルリクエストを作成して変更を提案します。

### ブランチルール

- mainブランチは常にデプロイ可能な状態を保ってください。
- 機能開発やバグ修正は、`feature/`や`fix/`を接頭辞としたブランチで行ってください。

### コードのスタイル

このプロジェクトではPEP 8スタイルガイドに従います。コードをコミットする前に、flake8を使用してコードをチェックしてください。

## 使用方法

アプリケーションはコマンドラインから次のように実行します。

```bash
python -m simulator
```

## リリース

ユーザーはGitHubのリリースページから最新バージョンのsatellite-simulatorをダウンロードして使用できます。

## ライセンス

このプロジェクトはApache2.0ライセンスの下で公開されています。詳細についてはLICENSEファイルを参照してください。

## Contributor

Maya Abe - プロジェクトリーダー
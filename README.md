# developments
開発環境の構築、さまざまなインストール手順などに関するメモを配置するためのリポジトリです。  
This repository to place notes on development environment construction, various installation procedures, etc.

## scoop(Win)
Linuxのaptやyumのようなパッケージ管理システム

### インストール
1. PowerShell起動
2. 下記実行
   ```ps
    Set-ExecutionPolicy RemoteSigned -scope CurrentUser
    invoke-Expression (New-Object System.Net.WebClient).DownloadString('https://get.scoop.sh')
   ```

### ライブラリインストール
1. cmd起動
2. 下記必要なものを実行
   ```bat
   @rem git
   scoop install git
   @rem python
   scoop install python
   ```

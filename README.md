# Level1 : Born2beRoot

## 概要
- 目的：仮想化サーバについて学習する
- VirtualBox（またはVirtualBoxが使用できない場合はUTM）で最初のマシンを作成する
- 課題要件に従って、セットアップを実施

### 課題の流れ
- 仮想マシンISOをダウンロード　：　Debian を選択
- 仮想マシンのインストール　：　デフォルトでVirtualBoxを使用します
- Debianのインストール
    - ＜ボーナス要件＞　パーティション分割
- 仮想マシンのセットアップ
    - sudoのインストール、ユーザのグループの構成
    - SSHのインストール、設定
    - UFWのインストール、設定
    - sudoポリシーの設定
    - パスワードポリシーの設定
    - SSH経由での接続
- スクリプトの表示
- Crontabの編集
- 提出用仮想マシンのshasum取得

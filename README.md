> :loudspeaker: While discord.py is undergoing a rewrite, this bot will not receive any major updates. Please do not bug us asking if the project is dead. It is likely that this bot make break at some point due to updates to discord.py. When the discord.py rewrite is complete, this bot will likely be rewritten too.

# ApeiriaBot: Discord用音楽bot

このボットは[Python] を使用して作られました。(https://www.python.org "Python homepage"). リクエストした曲、事前に作成したプレイリストなどを再生できます。
### インストール手順

別途必要なソフト

1.Python 3.5.3 (https://www.python.org/downloads/release/python-353/)
2.git (https://git-scm.com/)

2つのソフトを導入し、インストールしてください。

インストールが終わったら、botを配置したい場所で右クリック、"Git Bash Here" を選択し、
下のコマンドを入力してください。

`git clone https://github.com/QuL-kuluru/apeiriadiscordbot.git`

そして、手動で再生するためのコーデックを導入します。

インストールしたフォルダに新規追加で `bin`というフォルダを作成し、下記ファイルを作成したフォルダに追加してください。
(https://drive.google.com/open?id=1gVeb0f1d3P7QZqCPpS1wlj5OsP9A4vlu)

これでインストールが完了します。

### コマンド (各コマンドはアプリケーション内で詳細を知ることができます。)

!blacklist, !clean, !clear, !disconnect, !id, !joinserver, !listids, !np, !pause, !perms, !play, !pldump, !queue, !restart, !resume, !search, !setavatar, !setname, !setnick, !shuffle, !shutdown, !skip, !stream, !summon, !volume

### コンフィギュレーション

コンフィギュレーションファイルは`config/options.ini` ですが、初期状態では含まれていません。`example_options.ini` を編集してください。（起動時に自動的にリネームされます。）

### 起動方法
任意の場所に解凍し、セッティングが終わったら、`runbot.bat` (または mac、Linux上では `run.sh` )を起動してください。

### プレイリストが読み込めなくなった時
ApeiriaBotにはyoutube、SoundCloud用に音声をダウンロードするプログラムを導入しています。
随時プログラムはアップデートをするため、バージョンが古くなるとエラーを起こす場合があります。
不調だと感じた場合は `update_dependencies.bat` を実行すると改善される場合がありますので、お試しください。

### Google Drive版
gitでのインストールがうまくいかない場合はこちらもお試しください。
(https://drive.google.com/open?id=15CelMwtiovdQMzFXCZWUTWqDK8ifk8_N)

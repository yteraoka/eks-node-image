# journald

再起動でログが消えないように /var/log/journal ディレクトリを作成し
そこに保存されるようにする。

/etc/systemd/journald.conf で `Storage=auto` がデフォルトとなっっている
ため、ディレクトリを作成しておけば保存される。

# journald

再起動でログが消えないように /var/log/journal 配下に保存されるようにする。

/etc/systemd/journald.conf で `Storage=persistent` と明示することで
`/var/log/journal` は存在しなくても作成される。

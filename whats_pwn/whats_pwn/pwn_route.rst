Pwnへのみちすじ
=========================

Pwnの主目的は :command:`/bin/sh` を実行することと言いました。

プログラムの実行中に :command:`/bin/sh` を実行するには次のような方法があります。

* :command:`system("/bin/sh")` を実行する。
* :command:`execve("/bin/sh", ["/bin/sh"], NULL)` を実行する。( :command:`["/bin/sh"]` については :command:`NULL` に置き換えることも出来る。)


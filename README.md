comecon_sample
==============
米魂の企画申込画面テスト用

大会ごとに必ず変更がある部分(名称とかメアドとか)は、すべて
    pgreglib.pm
の中で定義し、吸収しています。

入力項目など変更がありそうな部分は、
    XXXX.tmpl
で定義し、
    pgreglib.pm
の中で吸収しています。

よって、それ以外の
    *html *txt *cgi
は、変更なく次からも使えるはずです。

唯一の例外が、
    index.html
です。
cgiではないので共通化していません。
(する方法はいくつかあるけど、本質的じゃないし)

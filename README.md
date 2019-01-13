# robosys2
数をカウントするプログラムです。 roscoreを立ち上げroslaunch mypkg mypkg.launchをはしらせます。 その後rostopic echo /count_upと打つと数が0.1づつ増えながら表示され、 rostopic echo /flと打つと3の倍数が表示されます。
1秒間に約1回回すプログラムにしました。
プログラムを動かす際にtmuxを使いました。
インストール方法はこちらになります。
sudo apt install tmux
こちらを参考に作りました。
https://github.com/ryuichiueda/robosys2018/blob/master/11.md
https://github.com/ryuichiueda/robosys2018/blob/master/13.md
YouTubeにあげたデモ動画はこちらです。
https://www.youtube.com/watch?v=8ewrKVvIRmI

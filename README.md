<!-- Polybar Themes-->

This repository is forked from <a href="https://github.com/adi1090x/polybar-themes"><b>adi1090x/polybar-themes</b></a>. 

<p align="center">
  <img src="https://raw.githubusercontent.com/adi1090x/files/master/polybar-themes/previews/logo.png">
</p>

このリポジトリは<a href="https://github.com/adi1090x/polybar-themes"><b>adi1090x/polybar-themes</b></a>のフォークです。
基本的な部分は、本家のREADMEを参照してください。


このリポジトリは、
デバイス設定を私のマシン用に調整し、
デザインも私用に調整、
更にxmonadのデスクトップ情報を受け取れるように調整しています。
(今の所、blocksとshapesのみ)


クールにカスタマイズされたpolybarのテーマを更に自分でカスタマイズする際の参考にしてください。


##


### Installation

Follow the steps below to install these themes on your system.

- First, Clone this repository -
```
$ git clone --depth=1 https://github.com/nekolinuxblog/polybar-themes.git
```
- Change to cloned directory and make setup.sh executable -
```
$ cd polybar-themes
$ chmod +x setup.sh
```

- Run `setup.sh` and select a style -
```
$ ./setup.sh

[*] Installing Polybar Themes...

[*] Choose Style -
[1] Simple
[2] Bitmap

[?] Select Option : 1

[*] Installing fonts...
[*] Creating a backup of your polybar configs...
[*] Successfully Installed.
```

- That's it, These themes are now installed on your system.

> Note : These themes are like an ecosystem, everything here is connected with each other in some way. So... before modifying anything by your own, make sure you know what you are doing.

### Launch the bar

To launch the bar with the selected theme, Just...

- Open the terminal and enter the following command - 
```
$ bash ~/.config/polybar/launch.sh

Usage : launch.sh --theme

Available Themes :
--blocks    --colorblocks    --cuts      --docky
--forest    --grayblocks     --hack      --material
--panels    --pwidgets       --shades    --shapes
```

- Now, select your theme and launch the bar - 
```
$ bash ~/.config/polybar/launch.sh --hack
```

- You can add the same command to your WM autostart file to launch the bar on login. For example, to launch the bar at startup on openbox, add following lines in **`$HOME/.config/openbox/autostart`** -
```
## Launch Polybar
bash ~/.config/polybar/launch.sh --cuts
```

### Xmonadの対応

このリポジトリでのxmonad対応は、0.17バージョンで採用されているやり取りの方法を前提にしています。
興味のある方は「<a href=https://ok-xmonad.blogspot.com/2021/11/xmonad0170.html>xmonadの0.17.0へおしゃれにバージョンアップ</a>」で
xmonad.hsを紹介しているので、その中のpolybarに関するコメント部分を参照してみてください。





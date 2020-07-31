# emacs.ahk 
このスクリプトはウィンドウズでEmacsキーバインドを実現するもので、AutoHotkey(AHK)言語で書かれています。このリポジトリのメンテナーは2007年からこのスクリプトを利用しており、様々なアプリケーションで効果的に動作することを確認しています。

## サポートしているキーバインド
<table>
  <tr>
    <th>Emacsキーバインド</th>
    <th>Emacs Lispの機能名</th>
    <th>動作説明と実際に入力されるキーボード入力</th>
  </tr>
  <tr>
    <td>C-Space</td>
    <td>set-mark-command</td>
    <td>選択範囲の開始位置をマーク(シフトキー押下したまま)</td>
  </tr>
  <tr>
    <td>C-x C-f</td>
    <td>find-file</td>
    <td>ファイルを開く(Ctrl + O)</td>
  </tr>
  <tr>
    <td>C-x C-s</td>
    <td>save-buffer</td>
    <td>ファイルを保存する(Ctrl + S)</td>
  </tr>
  <tr>
    <td>C-x C-c</td>
    <td>kill-emacs</td>
    <td>ファイルを閉じる(Alt + F4)</td>
  </tr>
  <tr>
    <td>C-d</td>
    <td>delete-char</td>
    <td>カーソルキーの右を一文字消す(Del)</td>
  </tr>
  <tr>
    <td>C-h</td>
    <td>delete-backward-char</td>
    <td>カーソルキーの左を一文字消す(BackSpace)</td>
  </tr>
  <tr>
    <td>C-k</td>
    <td>kill-line</td>
    <td>カーソルから行末まで削除(Shift + End, BackSpace)</td>
  </tr>
  <tr>
    <td>C-o</td>
    <td>open-line</td>
    <td>改行してその行に移動(End, Enter, Up)</td>
  </tr>
  <tr>
    <td>C-g</td>
    <td>quit</td>
    <td>スペースキーとxキーの事前入力をキャンセル(Esc)</td>
  </tr>
  <tr>
    <td>C-j</td>
    <td>newline-and-indent</td>
    <td>改行とインデント(Enter, Tab)</td>
  </tr>
  <tr>
    <td>C-m</td>
    <td>newline</td>
    <td>改行と事前の入力をキャンセル(Enter)</td>
  </tr>
  <tr>
    <td>C-i</td>
    <td>indent-for-tab-command</td>
    <td>Tabによるインデント(Tab)</td>
  </tr>
  <tr>
    <td>C-s</td>
    <td>isearch-forward</td>
    <td>前方検索(Ctrl + F)</td>
  </tr>
  <tr>
    <td>C-r</td>
    <td>isearch-backward</td>
    <td>後方検索(Ctrl + S)</td>
  </tr>
  <tr>
    <td>C-w</td>
    <td>kill-region</td>
    <td>マーク位置から現在位置までを切り取り(Ctrl + X)</td>
  </tr>
  <tr>
    <td>M-w</td>
    <td>kill-ring-save</td>
    <td>マーク位置から現在位置までをコピー(Ctrl + C)</td>
  </tr>
  <tr>
    <td>C-y</td>
    <td>yank</td>
    <td>貼り付け(Ctrl + V)</td>
  </tr>
  <tr>
    <td>C-/</td>
    <td>undo</td>
    <td>アンドゥ(Ctrl + Z)</td>
  </tr>
  <tr>
    <td>C-a</td>
    <td>move-beginning-of-line</td>
    <td>行頭に移動(Home)</td>
  </tr>
  <tr>
    <td>C-e</td>
    <td>move-end-of-line</td>
    <td>行末へ移動(End)</td>
  </tr>
  <tr>
    <td>C-p</td>
    <td>previous-line</td>
    <td>カーソルを一文字上へ移動(↑)</td>
  </tr>
  <tr>
    <td>C-n</td>
    <td>next-line</td>
    <td>カーソルを一文字下へ移動(↓)</td>
  </tr>
  <tr>
    <td>C-f</td>
    <td>forward-char</td>
    <td>カーソルを一文字右へ移動(→)</td>
  </tr>
  <tr>
    <td>C-b</td>
    <td>backward-char</td>
    <td>カーソルを一文字左へ移動(←)</td>
  </tr>
  <tr>
    <td>C-v</td>
    <td>scroll-down</td>
    <td>スクロールダウン(PageDown)</td>
  </tr>
  <tr>
    <td>M-v</td>
    <td>scroll-up</td>
    <td>スクロールアップ(PageUp)</td>
  </tr>
</table>


## 本スクリプトはいつくかのWEBページで紹介されました
* [AutoHotkeyでemacs風キーバインド - torutkの日記](http://d.hatena.ne.jp/torutk/20101009/p2)
* [オダろぐ : Emacs＞AutoHotKey の Emacsモードを使うことにした](http://blog.livedoor.jp/odaxsen/archives/1546840.html)
* [AutoHotkey &laquo; sea side she side](http://www.a10i.jp/?tag=autohotkey)
* [NTEmacs @ ウィキ - Windows の操作を emacs のキーバインドで行う設定 （AutoHotKey版）](http://www49.atwiki.jp/ntemacs/pages/20.html)
    * 2名の方によって編集されています

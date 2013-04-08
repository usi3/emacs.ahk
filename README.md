# emacs.ahk
An autohotkey script that provides emacs-like keybindings on Windows. 
Feel free to improve and commit.
I have used and maintained this script since Sep 21, 2007.

lynnux:slightly modified for my habit, add M-b, M-f, M-h, M-d

## Supported keybindings
<table>
  <tr>
    <th>Keybinding</th>
    <th>Function(Emacs Lisp)</th>
  </tr>
<tr>
<td>C-t</td>
<td>set-mark-command</td>
</tr>
<tr>
<td>C-@</td>
<td>set-mark-command</td>
</tr>
<tr>
<td>C-x C-f</td>
<td>find-file</td>
</tr>
<tr>
<td>C-x C-s</td>
<td>save-buffer</td>
</tr>
<tr>
<tr>
<td>C-x C-y</td>
<td>yank-pop</td>
</tr>
<tr>
<td>C-x C-h</td>
<td>mark-whole-buffer</td>
</tr>
<tr>
<td>C-x C-p</td>
<td>mark-page</td>
</tr>
<tr>
<td>C-d</td>
<td>delete-char</td>
</tr>
<td>M-d</td>
<td>kill-word</td>
</tr>
<tr>
<td>C-h</td>
<td>delete-backward-char</td>
</tr>
<td>M-h</td>
<td>backward-kill-word</td>
</tr>
<tr>
<td>C-k</td>
<td>kill-line, if caret is at the end of the line, then delete the "`r`n"</td>
</tr>
<tr>
<td>C-o</td>
<td>open-line</td>
</tr>
<tr>
<td>C-g</td>
<td>quit</td>
</tr>
<tr>
<td>C-j</td>
<td>newline-and-indent</td>
</tr>
<tr>
<td>C-m</td>
<td>newline</td>
</tr>
<tr>
<td>C-i</td>
<td>indent-for-tab-command</td>
</tr>
<tr>
<td>C-s</td>
<td>isearch-forward</td>
</tr>
<tr>
<td>C-r</td>
<td>isearch-backward</td>
</tr>
<tr>
<td>C-w</td>
<td>kill-region, if nothing selected, then cut the whole line</td>
</tr>
<tr>
<td>M-w</td>
<td>kill-ring-save</td>
</tr>
<tr>
<td>C-y</td>
<td>yank</td>
</tr>
<tr>
<td>C-/</td>
<td>undo</td>
</tr>
<tr>
<td>C-u</td>
<td>redo, equal to native C-y</td>
</tr>
<tr>
<td>C-a</td>
<td>move-beginning-of-line</td>
</tr>
<tr>
<td>C-e</td>
<td>move-end-of-line</td>
</tr>
<tr>
<td>C-p</td>
<td>previous-line</td>
</tr>
<tr>
<td>C-n</td>
<td>next-line</td>
</tr>
<tr>
<td>C-f</td>
<td>forward-char</td>
</tr>
<td>M-f</td>
<td>forward-word</td>
</tr>
<tr>
<td>C-b</td>
<td>backward-char</td>
</tr>
<td>M-b</td>
<td>backward-word</td>
</tr>
<tr>
<td>M-v</td>
<td>scroll-up</td>
</tr>
</table>


## Webpages introducing this script
* [AutoHotkeyでemacs風キーバインド - torutkの日記](http://d.hatena.ne.jp/torutk/20101009/p2)
* [オダろぐ : Emacs＞AutoHotKey の Emacsモードを使うことにした](http://blog.livedoor.jp/odaxsen/archives/1546840.html)
* [AutoHotkey &laquo; sea side she side](http://www.a10i.jp/?tag=autohotkey)
* [NTEmacs @ ウィキ - Windows の操作を emacs のキーバインドで行う設定 （AutoHotKey版）](http://www49.atwiki.jp/ntemacs/pages/20.html)
    * customized by 2cher
* [WindowsでEmacs風キーバインド - Usipedia](http://usi3.com/index.php?title=Windows%E3%81%A7Emacs%E9%A2%A8%E3%82%AD%E3%83%BC%E3%83%90%E3%82%A4%E3%83%B3%E3%83%89)

# phits.vim

# English
Vim syntax highlighting for PHITS code.

1. Copy phits.vim to syntax directory of vim.

2. Add "au BufNewFile,BufRead *.inp,*.out setf phits" to filetype.vim.

3. Now your PHITS code will be highlighted. If not, try ":syntax on" at your inp or out file.

# 日本語
PHITS コードのためのvimハイライトのシンタックスです。

1. phits.vim を vim の syntax のディレクトリにコピー。

2. filetype.vim に "au BufNewFile,BufRead *.inp,*.out setf phits" を追加。

3. これで PHITS コードがハイライトされます。変化がなければ inp もしくは out ファイルを開いた状態で ":syntax on" を実行してみて下さい。

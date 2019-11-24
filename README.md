# vim-config
vimの設定ファイル.

## Usage
1. まずはdeinをインストールする.
- https://github.com/Shougo/dein.vim

2. 次にvimのバックアップ用のディレクトリを作成する.
    ```bash
    cd
    mkdir .vimbackup
    ```

3. ディレクトリなどの絵文字を表示するためのフォントをインストールする.

- https://github.com/ryanoasis/nerd-fonts#patched-fonts

- 上記のリンクから好きなフォントを選んで, `nerd-fonts/patched-fonts/Ubuntu/Regular/complete/`のように進んで, `*.ttf`や`*.otf`を`~/.fonts`ディレクトリに保存する.

4. ターミナルを開いて, 先程インストールしたフォントを設定する.

5. `fzf`をインストールする．
    ```bash
    git clone --depth 1 https://github.com/junegunn/fzf.git ~/.fzf
    ~/.fzf/install
    ```

6. `.vimrc`をダウンロードする.
    ```bash
    cd
    curl -O https://raw.githubusercontent.com/solareenlo/vim-config/master/.vimrc
    ```

7. `dein.vim`を使ってプラグインをインストールする.
    ```bash
    :call dein#install()
    ```

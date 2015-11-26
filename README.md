#### nvmコマンドインストール
    $ curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.29.0/install.sh | bash

#### ターミナル再起動

#### インストール可能なバージョン確認
    $ nvm ls-remote

#### インストール
    $ nvm install v0.12.8
    $ nvm alias default v0.12.8
#### バージョン確認
    $ nvm ls
    ->      v0.12.8
    node -> stable (-> v0.12.8) (default)
    stable -> 0.12 (-> v0.12.8) (default)
    iojs -> N/A (default)
    
    $ node -v
    v0.12.8

# README

```
code 対象のワークスペース --extensionDevelopmentPath=（このreadme.mdがあるディレクトリ）
```

```
code G:\temp_dir --extensionDevelopmentPath=D:\vscode_this_extension
```

といった指定の仕方で、起動とともにソースビューとなる。  
（拡張機能をインストールすることなく、この拡張機能を有効にする方法）
  
vscode を外部からコマンドラインなどで、gitツール代わりに利用する歳に便利に機能する。

動作に必要なファイルは実際には２つで、

- package.json
- extension.js

のみ。

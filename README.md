## 本プログラムについて

本プログラムでは、jupyter notebookとRemix IDEを用いたコントラクトの実装方法を説明します。

## 利用方法について

1. Remix IDEを用いてスマートコントラクトをコンパイルする。

2. jupyter notebook を開き、ノートブックを実行するフォルダに[Compilation Details]下部のBytecodeをクリックしてコピーして
以下のファイル名で保存しておく。

```
bytecode.json
```

3. deployContract.ipynbを実行する

注意: 以下のようにしてPython3のパッケージをインストールする必要あります
```
!pip install eth_account
!pip uninstall protobuf // Google Colabの場合必要
!pip install protobuf==3.19.5 // Google Colabの場合必要
!pip install web3
```

4. 実装されたコントラクトに関する以下の情報が得られる

-> コントラクトの実装を行ったアカウントの秘密鍵
-> コントラクトの実装を行ったアカウントのアドレス
-> コントラクトの実装を行うトランザクションのハッシュ
-> 実装されたコントラクトのアドレス







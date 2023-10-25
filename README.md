# e-gadget-build-vscode
VScode上でe-gadgetにcファイルをビルドする

## インストールの手順
1. [ここ](https://d.kuku.lu/k7uvbwc5b)から `build.zip` をダウンロードして適当な場所に展開して環境変数にパスを追加する。
2. 展開したフォルダ内にある `setting.json`の `"exe_path"` にc-styleの実行ファイルのパス、`"window_name"` にc-styleのウィンドウ名を入れる。  
    <例>  
    ![dir](https://github.com/kubo314/e-gadget-build-vscode/assets/147988437/b44d7da9-b6d5-4e78-986a-0e4abb8640ae)
    ![window](https://github.com/kubo314/e-gadget-build-vscode/assets/147988437/9c603343-4159-4155-9242-3fb65de7b9f1)

    ``` json
    {
        "exe_path": "C:/Daisen/C-Style for e-Gadget V19017/CStyle_EGCore.exe", 
        "window_name": "DAISEN C-Style for e-Gadget CORE  [ Ver.20190617 ]"
    }
    ```

4. `c-style-build.vsix` をvscodeにインストール<br>
    ![install](https://github.com/kubo314/e-gadget-build-vscode/assets/147988437/ccb74669-b98c-4221-bb2a-8a3be1aeb485)

## 使い方
ビルドしたいcファイルを開いた状態でステータスバーに表示される `ビルドする` ボタンを押す。  
![status](https://github.com/kubo314/e-gadget-build-vscode/assets/147988437/d7a739c3-ed78-410d-b7dd-849dbf9b77e4)

# 30日でできる！ OS自作入門

windows10で開発を進めています。

## 開発環境構

**必要なもの**

- git
- [HariboteOS/z_tools_win](https://github.com/HariboteOS/z_tools_win)を使用させていただいています

```cmd
rem 自作OSを作るためのフォルダを作成します

> md MyOS
> cd MyOS

rem このリポジトリをクローンします
> git clone https://github.com/zztkm/30daysOS.git

rem windows用の開発ツールをクローンします
> git clone https://github.com/HariboteOS/z_tools_win.git
> ren z_tools_win z_tools
```

## 起動方法

**例**

```cmd
rem cmd.exeでの実行を想定しています

> cd haribote\helloos0
> run
```

コマンドプロンプトで上記を実行すれば実行可能です。  
または、エクスプローラー上で`!cons_nt.bat`でコマンドプロンプトを起動してから`run`を実行することでも実行できます。
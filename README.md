# C# 書く教科書
C#について学んだことをまとめるリポジトリーです。

# 参考URL
- [Microsoft. C# 関連のドキュメント](https://docs.microsoft.com/ja-jp/dotnet/csharp/)
- [Nobuyuki Iwanaga, ++C++; // 未確認飛行Cについて](http://ufcpp.net/study/csharp/index.html)
- [paizaラーニング C#入門編](https://paiza.jp/works/cs/primer)
- [ドットインストール C#入門](http://dotinstall.com/lessons/basic_csharp)

# 目次
1. [Visual C#の基本操作](01.md)
1. [プログラミングの肝](README.md#%E3%83%97%E3%83%AD%E3%82%B0%E3%83%A9%E3%83%9F%E3%83%B3%E3%82%B0%E3%81%AE%E8%82%9D)
1. [問題の解消＝デバッグ](03.md)
1. [プロパティ(Property)～性質、属性～](04.md)
1. [計算～移動～](05.md)
1. [コントロール(Control)～表現を増やす～](06.md)
1. [変数～動的なプログラム～](07.md)
1. [if文(その1～基本形～)](08.md)
1. [switch文](09.md)
1. [マウス入力](10.md)
1. [if文(その2～複数の条件判断～)](11.md)
1. [乱数](12.md)
1. [配列～沢山のものを動かす（１）～](13.md)
1. [繰り返し(for文)～沢山のものを動かす（２）～](14.md)
1. [コントロールをプログラムで追加する～沢山のものを動かす（３）～](15.md)
1. [ミニゲームの開発](16.md)
1. [キー入力](17.md)

# Visual C#の基本操作
## Visual Studioの起動手順
- スタートメニュー>Visuak Studio 2019


## 新規プロジェクトの作成手順
1. 新規プロジェクトの作成
2. 言語をC#、Windows、デスクトップにしてWindowsフォームアプリを選択
3. 保存先を選択→ファイル名は日付などが良きかも。とりあえず、設定して、次へ
4. ターゲットフレームワークは変更せずに、作成をクリック

## プログラムの開始方法
-  緑の三角アイコンの開始ボタンを押す
- デバッグメニューから、デバッグを開始
- F5キーでデバッグ開始
-

### 注意：ctrlキーを押すのはダメ、デバッグメニューから デバッグなしで開始 も同様に使わないこと！！

## プログラムの停止方法
- 実行中のウィンドウの×アイコンをクリック
- 赤い四角のデバッグ停止アイコンをクリック
- デバッグメニューからデバッグの禁止を選択
- Shift+F5キー

### 注意：プログラムを停止しておかないと、編集ができないので、必ず停止させる必要有

## ツールボックスの表示方法
表示メニュー>ツールボックス を選択


## ツールボックスを画面に固定するアイコン
📌のアイコンをクリックして、縦にする


## 演習1-1：ツールボックスからボタン(Button)を選択して、フォームに配置して実行してみよう
ボタンをクリック>プロパティウィンドウのtext欄を変更>Enterキー

## プロパティウィンドウの表示方法を以下に記せ



## ボタンの文字を「あいさつ」に変更する方法を記せ



## button1を押した時に実行するプログラム
以下の該当する行に、`// button1の処理` と書き込む。

```cs
using [...]

namespace test
{
    public partial class Form1 : Form
    {
        public Form1()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {

        }
    }
}
```

## メッセージボックスの表示
「こんにちは」というメッセージボックスを表示するプログラムを以下に記せ。

```cs

```

## 演習1-2：ボタンを押した時に表示されるメッセージを変更してみよう。



## 演習1-3：演習1-2で作ったプログラムの解説をプログラム内にコメントで書いてみよう。

//から行末まではプログラムとみなされない

メソッドの前の行に /// を書くとメソッドの解説が書ける・

## プロジェクトの保存をするためのアイコン

青い四角が二つ重なっているすべてを保存 アイコン


## プロジェクトの閉じ方

Visual Studioの右上の×をクリック

## 既存のプロジェクトを読み込んで、フォームを表示する方法
- スタートメニューからVisual Studio2019 を選択
- 最近開いた項目からプロジェクトを選択するか、プロジェクトやソリューションファイルをを開く を選択
- ドキュメント>自分のフォルダーをダブルクリック>プロジェクトのフォルダーをダブルクリック>slnファイルを開く

## フォームが表示されていない時の表示方法
表示メニュー>ソリューションエクスプローラ>Form1.csをダブルクリック


---

[前へ](01.md) | [次へ](03.md)

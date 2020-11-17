# テスト予想問題

## Unix 10問（1問1点）
***

<!-- シェル -->
Q.黒い画面の操作に使用するものの総称は？

<!-- pwd -->
Q.自分が現在いる場所をフルパスで表示するためのコマンドは？

<!-- ls -la -->
Q.現在いる場所にどのようなファイルやディレクトリがあるかを隠しファイルを含めて詳細表示をするコマンドは？

<!-- cd - -->
Q.一つ前にいた場所に戻るコマンドは？

<!-- リネームと移動-->
Q.コマンド`mv`で行える２つの操作は？

<!-- echo > -->
Q.既存のファイルに書き込みを行うコマンドは？

<!-- -r -->
Q.フォルダのコピー`(cp)`や削除`(rm)`の際に必要なオプションは？

<!-- touch -->
Q.`vi`を使用せずにファイルを作成するコマンドは？

<!-- mkdir -->
Q.フォルダを作成するコマンドは？

<!-- cat -->
Q.既存のファイルの内容を確認するコマンドは？

## vim 10問　2択のうち当てはまる方を選択してください（1問1点）
***

<!-- 2 -->
Q.行末に挿入する
1. a
1. A

<!-- 1 -->
Q.カーソル位置から行末まで削除する
1. d$
1. de

<!-- 1 -->
Q.一文字削除する
1. x
1. d

<!-- 2 -->
Q.複数の単語を削除する(今回は3つの単語)
1. dw3
1. d3w

<!-- 2 -->
Q.リドゥ(やり直しの取り消し)
1. Shift + r
1. Ctrl + r

<!-- 1 -->
Q.最下行とファイルの先頭に移動する
1. Shift + g と gg
1. Ctrl + g と gg

<!-- 1 -->
Q.対応する`),]`や`}`へ移動する
1. %
1. $

<!-- 2 -->
Q.ファイル全体の特定の文字を別の文字で置換する（今回は`old`を`new`へ）
1. :$s/old/new/g
1. :%s/old/new/g

<!-- 2 -->
Q.複数の文字を置き換える
1. Ctrl + r
1. Shift + r

<!-- 1 -->
Q.外部のファイルの中身を読み込む
1. :r ファイル名
1. ;r ファイル名

## Git 10問（1問1点）
***

<!-- git init -->
Q.作成したフォルダをGitで管理するために最初に打つコマンドは？

<!-- ステージングエリア -->
Q.変更したい情報`add`する場所のことを何というか

<!-- git branch dev -->
Q.ブランチを作成するコマンドは？(ブランチ名は`dev`とする)

<!-- ブランチdivへ移動する -->
Q.`git checkout dev`はどのような働きをするコマンドか（`dev`はブランチ名）

<!-- ブランチの削除 -->
Q.`git branch -d dev`はどのような働きをするコマンドか（`dev`はブランチ名）

<!-- ssh接続 -->
Q.GitHubに接続する際に使用するのは何接続か

<!-- リモートリポジトリの追加 -->
Q.`git remote add origin`はどのようなときに使用するのか

<!-- 追跡設定 -->
Q.`git push -u origin master`で`master`ブランチをプッシュする際、`-u`はどのような設定を追加しているのか

<!-- git merge dev -->
Q.ブランチをマージするときにはどのようなコマンドを使用するのか（現在のブランチは`master`で、マージするブランチ名は`dev`）

<!-- git pull -->
Q.最新のリモートリポジトリの状況をローカルに反映させるコマンドは何か

## html 10問 (1問1点)
***

<!-- 2 -->
Q.正しい文章宣言のタグはどれか
1. &lt;!DOCUTYPE html&gt;
1. &lt;!DOCTYPE html&gt;
1. &lt;DOCTYPE html&gt;
1. &lt;DOCUTYPE html&gt;

<!-- 3 -->
Q.正しい画像表現のタグはどれか
1. ing
1. image
1. img
1. imege

<!-- 1 -->
Q.画像を表示するタグに、横幅を指定するための属性はどれか
1. width
1. wibth
1. w
1. wide

<!-- 1 -->
Q.空白の実態参照はどれか
1. &amp;nbsp
1. &amp;ndsp
1. &amp;nsbp
1. &amp;nspb

<!-- 3 -->
Q.「行」と「列」の英単語の組み合わせとして正しいのはどれか
1. 行 → width、列 → height
1. 行 → column、列 → row
1. 行 → row、列 → column
1. 行 → height、列 → width

<!-- 4 -->
Q.文書中に水平線を引くためのタグはどれか
1. ho
1. her
1. hl
1. hr

<!-- 2 -->
Q.input要素が空のときに表示されるテキストを指定する属性はどれか
1. value
1. placeholder
1. text
1. word

<!-- 1 -->
Q.次のうち正しいマークアップはどれか
1. &lt;li&gt;&lt;a&gt;&lt;/a&gt;&lt;/li&gt;
1. &lt;a&gt;&lt;/a&gt;&lt;li&gt;&lt;/li&gt;
1. &lt;a&gt;&lt;li&gt;&lt;/li&gt;&lt;/a&gt;
1. &lt;li&gt;&lt;/li&gt;&lt;a&gt;&lt;/a&gt;

<!-- 3 -->
Q.HTML内でコメントを書く方法として正しいのはどれか
1. &lt;-  -&gt;
1. //!--  --//
1. &lt;!--  --&gt;
1. &lt;--  --&gt;

<!-- 1 -->
Q.文中で改行するためのタグはどれか
1. br
1. dr
1. scr
1. bleak

## css 10問 (1問1点)
***

<!-- 2 -->
Q.CSSは何の略か
1. Coding Style sheets
1. Cascading Style Sheets
1. Client Style Sheets
1. Creative Style Sheets

<!-- 1 -->
Q.positionプロパティの既定値はどれか
1. static
1. relative
1. fixed
1. absolute

<!-- 1 -->
Q.box-shadow: 0 2px 3px black;において0は何を表すか
1. 影のx方向へのずれ具合
1. 影のy方向へのずれ具合
1. 影の透明度
1. 影のボケ具合

<!-- 4 -->
Q.「相対」「絶対」を表す英単語の組み合わせとして正しいものはどれか
1. 相対 → absolute、絶対 → sticky
1. 相対 → sticky、絶対 → absolute
1. 相対 → absolute、絶対 → relative
1. 相対 → relative、絶対 → absolute

<!-- 2 -->
Q.リンクの下線を消すためのプロパティは何か
1. text-align
1. text-decoration
1. link
1. underline

<!-- 4 -->
Q.「その要素にカーソルがのったとき」にスタイルを適用できる擬似クラスはどれか
1. :on
1. :over
1. :above
1. :hover

<!-- 2 -->
Q.文字を右に寄せるための宣言はどれか
1. font-align: right
1. text-align: right
1. text-aling: right
1. font-align: rigth

<!-- 4 -->
Q.文字の間隔を指定するためのプロパティはどれか
1. letter-lead
1. letter-space
1. letter-leading
1. letter-spacing

<!-- 3 -->
Q.box-sizing: border-box;について正しい記述はどれか
1. widthにborderは含まれるがpaddingは含まれない。
1. widthにpaddingは含まれるがborderは含まれない。
1. widthにpaddingもborderも含まれる。
1. widthにpaddingもborderも含まれない。

<!-- 2 -->
Q.css内でコメントを書くときの記述方法はどれか
1. &lt;!-- --&gt;
1. /* */
1. &lt;/ /&gt;
1. /- -/

## Java 4問 (1答5点)
***

<!-- 3行目の変数名ｌ、11行目のprint（lnがないので改行されない） -->
Q.下記の記述で間違っている2か所はどこか(例：〇行目の〇〇)

```
 1  public class Sample{
 2    public static void main(String[] args){
 3      for(int l=0;l<5;l++){
 4        for(int j=0;j<5;j++){
 5          if(j<i){
 6            System.out.print(" ");
 7          }else{
 8            System.out.print("*");
 9          }
10        }
11        System.out.print();
12      }
13    }
14  }
```

<!-- ①String ②case ③break -->
Q.下記の記述の①、②、③に当てはまるものは何か

```
 1 import java.util.*;
 2 public class Sample{
 3   public static void main(String[] args){
 4     System.out.print("1つ目の整数xの値を入力してください>");
 5     int x=new Scanner(System.in).nextInt();
 6     System.out.print("2つ目の整数yの値を入力してください>");
 7     int y=new Scanner(System.in).nextInt();
 8     System.out.print("演算子(+,-,*,/,%)を半角記号で入力してください>");
 9     ① ope=new java.util.Scanner(System.in).nextLine();
10
11     switch (ope){
12       ② "+":
13         System.out.println("x+y="+(x+y));
14         ③;
15       ② "-":
16         System.out.println("x-y="+(x-y));
17         ③;
18       ② "*":
19         System.out.println("x*y="+(x*y));
20         ③;
21       ② "/":
22         System.out.println("x/y="+(x/y));
23         ③;
24       default:
25         System.out.println("x%y="+(x%y));
26         ③;
27   }
28 }
```

<!-- 4行目の[10,20,30,40,50] , 6行目のnums[5] -->
Q.下記の記述で間違っている2か所はどこか (例：〇行目の〇〇)

```
 1  public class Sample{  
 2    public static void main(String[] args)  
 3  
 4      int[] nums=[10,20,30,40,50];  
 5  
 6      nums[1]=nums[2]+nums[5];  
 7      nums[3]=nums[2]+nums[4];  
 8  
 9      System.out.println(nums[1]);  
10     System.out.println(nums[3]);  
11    }  
12  }
```

<!-- ①int ②? ③: -->
Q.下記の記述の①、②、③に当てはまるものは何か（7行目は3項演算子）

```
 1  public class Sample{
 2    public static void main(String[] args){
 3      System.out.print("整数A:");
 4      ① a=new Scanner(System.in).nextInt();
 5      System.out.print("整数B:");
 6      ① b=new Scanner(System.in).nextInt();
 7      ① min= a < b ② a ③ b;
 8      System.out.println("小さいほうの値は"+min+"です");
 9    }
10  }
```

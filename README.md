
四則演算プログラム(整数の範囲)

1．準備
　使用するソフト
 　TeraPad(テキストエディタ)
   cmd.exe(コマンドプロンプト)
  それぞれのショートカットをデスクトップに作る。
  
  TeraPadに　Balloon01.java　のコードを書き、Balloon01.java という名前を付けて保存する。
  Balloon01.java のショートカットをデスクトップに作る。
  
2.　使用
使える演算記号は5種類ある。
足し算：+　引き算：-　掛け算：*　割り算の商：/ 割り算の余り：%
例 7/3の答えは２　7％３の答えは１

TeraPadでBalloon01.javaを開く。
3～6行目の算用数字を任意の数字に変えることで、使う数字を指定できる。
より多くの数字を使うときは、3～6行目に倣ってアルファベットと算用数字を対応させる。
例  int s(もしくはまだ使っていないアルファベット1文字)=37(使う数字で、桁数は問わない。); 
7～11行目　System.out.println();　の()の中に計算式を書く。System.out.println();の行を増やすと、多くの計算を一度にできる。
TeraPadで上書き保存する。

cmd.exeを起動し、javac Balloon01.java　と入力する。続いて java Balloon01 と入力する。
計算結果はTeraPadで上に入力した計算式の結果から順に上から表示される。
例(githubにアップしたコードに書かれたアルファベット・数字を使用)
TeraPadで上から順にSystem.out.println(w/(y+A)-z);  System.out.println(z+w%y); と入力する。cmd.exeでは上から順に  -4  9  と表示される。

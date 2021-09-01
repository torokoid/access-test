# access-test
<html lang="ja">
 <head>
  <meta charset="utf-8" />
	 

<style type="text/css">

  p {
color: #fffafa;
font-size: 1.5em;
 }

 .red {color:#ff0000;}
 .grey {color:#999999;}
 .snow {color:#fffafa;}
 .yellow {color:#ff0000; background:#ffff00;}
 .blue {color:#0000ff;}
 .white {color:#ffffff; blinking;}
 .waku {border:2px dotted #99cc66;
　　　　　　line-height: 200%;
　　　　　　padding: 10px;}

	
 #preview{
	position: relative;
	border: 3px solid #333;
	background: #444;
	padding: 5px;
	display: none;
	color: #FFF;
	text-align: center;
}

@media	screen and (min-width: 540px),
	screen and (orientation: landscape) {
   p.note { display: none; }
}

#wrap {background:none} /*PC用の背景はオフ*/
body::before {
  content:"";
  display:block;
  position:fixed;
  top:0;
  left:0;
  z-index:-1;
  width:100%;
  height:100vh;
  background:url(https://torokoid.github.io/access-test/20210831_007.jpg) center/cover no-repeat; /*fixedをトル！*/
  -webkit-background-size:cover;/*Android4*/
  }
</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">
 
</head>
<body>

<p class="note">
  モバイル端末をお使いの場合は、画面を横向きにすると
  より見やすくご覧頂けます。
</p>
	
<h1><span class="yellow"><marquee behavior="alternate">!!! 2021年8月31日(火)栃木県宇都宮市~芳賀郡高根沢町でアンテナテスト !!!</marquee></span></h1>
	
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<h3><span class="white">JR宇都宮駅の西側にある、ハムショップのノード局にアクセスしやすいのはどちらのアンテナか、<br>実験しました。リグはFTM300Dで50Watt送信。<br>コースは宇都宮から１駅北上した岡本駅から東側の鬼怒川を渡って、南南東に進むルート。<br>東進、南下側で屋根上のアンテナ、Uターンして、北上、西進側でテールゲートのアンテナを試しました。</span></h3>
<a href="20210831_004.png" data-lightbox="abc"><img src="20210831_004.png" alt="サンプル画像" width="900" /></a>
<h3><span class="white">比較したのは、テールゲートのダイヤモンドSG7900と、最近見かける極太アンテナ。</span></h3>
<a href="20210831_001.jpg" data-lightbox="abc"><img src="20210831_001.jpg" alt="サンプル画像" width="900" /></a>
<h3><span class="white">SG7900はやけに長いので、走行中に揺れないように釣り糸で２方向に引っ張りました。</span></h3>
<a href="20210831_002.jpg" data-lightbox="abc"><img src="20210831_002.jpg" alt="サンプル画像" width="900" /></a>
<h3><span class="white">極太アンテナは、給電部高さ的には有利な位置にセット。</span></h3>
<a href="20210831_003.jpg" data-lightbox="abc"><img src="20210831_003.jpg" alt="サンプル画像" width="900" /></a>	
<h3><span class="white">SG7900のカタログデータ。</span></h3>
<a href="20210831_005.png" data-lightbox="abc"><img src="20210831_005.png" alt="サンプル画像" width="900" /></a>
<h3><span class="white">極太アンテナのカタログデータ。</span></h3>
<a href="20210831_006.png" data-lightbox="abc"><img src="20210831_006.png" alt="サンプル画像" width="900" /></a>
<br>
<h2><span class="yellow">結果はSG7900の圧勝でした。<br>極太アンテナは全域でノードにアクセス出来ず＆APRSの軌跡を残せずでした。<br>SG7900は基地局に対して車体の後ろに回った状態でもアクセス出来てました。<br>Amazonの口コミを見たら、極太アンテナは２mの波が出ないと書かれてます。</span></h2>
	<br>
<h2><span class="white">追加試験</span></h2>	
<h2><span class="yellow">自宅に上げたGPアンテナでハンディー機から波出せるかチェックしました。<br>物置から引っ張り出したGPはなんと1.2GHz対応で、N型接栓。セットの同軸もやけに太いものでしたが、ハンディー機の5Watt出力で宇都宮のノード局にすんなり接増。<br>現時点の結論は、車側の空中線が非力・・・給電点高さをなんとか確保すべき！</span></h2>
	<br><br>
<h3><span class="white">次のテストは、アンテナ角度変えられるマグネット基台で、屋根上に設置しアンテナを前に倒してみますかね〜自衛隊の車がよくやってるやつです。<br>基台の候補はこれ。</span></h3>
<a href="20210831_007.png" data-lightbox="abc"><img src="20210831_007.png" alt="サンプル画像" width="900" /></a>	


<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<p align="right"><marquee direction="left" scrollamount="5" width="85%">以上、ここまでご覧いただき、ありがとうございました！ (^_^)/~hada</marquee></p>

<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>


<br><br>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script> 

<!-- フッタ -->
 <footer><span class="white">
 Copyright 2021/08/31 S.Hada
	 </span></footer>

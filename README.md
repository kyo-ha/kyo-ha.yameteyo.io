#### kyo-ha.yameteyo.io
<html lang="ja">

<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<!-- Twitter -->
	<meta name="twitter:card" content="summary" />
	<meta name="twitter:site" content="@MUNKU_maple" />
	<meta property="og:url" content="https://htymfield.net" />
	<meta property="og:title" content="畑山畑" />
	<meta property="og:description" content="畑山えぬのホームページです。" />
	<meta property="og:image" content="https://htymfield.net/image/htymLogo_cube.png" />
	<style>
		iframe {
			/* iframeのサイズ調整 */
			/* 縦横はviewの80% */
			height: 80vh;
			width: 80vw;
			/* iframeの位置調整 */
			/* 左右中央寄せ */
			margin-left: auto;
			margin-right: auto;
			display: block;
			/* iframeの境界線を消す */
			border: none;
		}

		body {
			text-align: center;
		}

		.weaktext {
			color: silver;
		}

		.iteminfo {
			display: grid;
			grid-template-columns: 25% 75%;
			grid-template-areas: "lArea rArea";
			height: 100px;
			border: solid gray;
			border-radius: 10px;
			overflow: hidden;
			margin: 5px 0px 5px 0px;
			padding: 1%;
		}

		.iteminfo>svg {
			grid-area: lArea;
			margin: auto;
			display: block;
			max-width: 100%;
			max-height: 100%;
		}

		.infotext {
			grid-area: rArea;
			margin: 5px;
			text-align: left;
		}
	</style>
	<title>
		ブロック崩しのサンプル
	</title>
</head>

<body>
	ブロック崩しのページ
	<iframe src="./bb2021inline.html"></iframe>

  </body>

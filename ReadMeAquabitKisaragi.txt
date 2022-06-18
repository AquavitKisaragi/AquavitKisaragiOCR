プロジェクトのタイトル
	AquavitKisaragi
	
免責事項
	いかなる理由があってもこのソフトを利用して受けた損害や被害などの保証は行いません。
	利用する場合は自己責任でお願い致します。

プロジェクトの概要説明
	OCRで画面を読み込み文章を読み込んだタイミングとテキストのファイル及びJSONを出力します。
	音声再生ソフトと連携すれば録音（WAV出力）及び音声を出力することもできます。



必要条件
	windows10以上（だと思うよ！）

使用言語、環境、テクノロジー
	C#（一部Python）

使い方
	暫定版なので動画などを見てどのような機能なのか確認をお願い致します。

	スキャン座標取得ボタン
		OCRの位置指定
	モニタースキャン開始ボタン
		OCRの開始し、レコーディングデータのテキストファイルを出力します。
		同時に再生することも可能です。
	Recファイルを保存ボタン
		レコーディングデータのテキストファイルを保存する
	Recファイルを開くボタン
		レコーディングデータのテキストファイルを開く
	Recファイル再生ボタン
		現在の録音データを再生する
	再録音ボタン
		レコードファイルをもとにサウンドを再作成

	処理中終了
		現在溜まっている動画録音及び再生のキューを全削除します。

	ファイル
		Setting.xml
			音声再生する条件など細々と書いています。
		LinkAppList.xml
			音声再生ソフトの情報が記載されています。


インストール方法
  ZIPから展開して好きな場所に保存してください。


  その後必要に応じて以下のことを行ってください。
  ・VOICEVOXで録音再生する場合はVOICEVOXのインストール及び起動であることが条件です。
  　https://voicevox.hiroshiba.jp/


  ・AquesTalkで録音再生する場合はAquesTalk10とAqKanji2Koe-A Win両方のDLLが必要です。
  　https://www.a-quest.com/download.html
		上記のサイトからAquesTalk10及びAqKanji2Koe-A Winをダウンロードして展開した後に以下の通りに保存してください。
		本体のフォルダ直下
  　	-AquesTalk.dll　	#ダウンロードしたファイルのaqtk10_win_110\aqtk10_win\lib　配下
		-AquesTalk.lib　	#ダウンロードしたファイルのaqtk10_win_110\aqtk10_win\lib　配下

		-aq_dic				#aqk2k_win_412\aqk2k_win\配下（フォルダごと置く）
		-AqKanji2Koe.dll	#aqk2k_win_412\aqk2k_win\lib　配下
		-AqKanji2Koe.lib	#aqk2k_win_412\aqk2k_win\lib　配下
		-AqUsrDic.dll		#aqk2k_win_412\aqk2k_win\lib　配下
		-AqUsrDic.lib		#aqk2k_win_412\aqk2k_win\lib　配下

ライセンス情報
	アクアビット・キサラギ
	Twitter（@TMarunoko）
	

	録音及び再生に必要なソフトウェア
	AquesTalk10及びAqKanji2Koe（株式会社アクエスト様）
	https://www.a-quest.com/download.html

	VOICEVOX様
	https://voicevox.hiroshiba.jp/


	MouseHook.csを利用させていただいています。
	https://gist.github.com/tarukosu/e8b869cf700ac1c91901fc065731a3a3

今後の計画
	・株式会社アクエスト様のライセンスキーの登録方法の検討（ライセンス流出の被害をなくせるか検討中）
	・録音した音声の再生タイミングの調整する機能の検討
	・WAVファイルの連結機能の検討

	・VOICEVOX様から許可を取る！！！！！！！！！！！！

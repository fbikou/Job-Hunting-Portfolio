# GASによるGMail添付PDFファイル自動選別・アップロードツール
## 依頼背景
「GMailで送られてくる仕事のメールを毎回,確認し,印刷が必要なPDFファイルが添付されていた時はそれをダウンロードし印刷しています。この業務が大変なので,OCR(光学文字認識)技術を使って自動化して欲しいです。」とのご依頼を頂きました。
## 機能
設定したメールアドレスに届いたメールにPDFが添付されていた場合, そのPDFファイルにOCRを適用し, 予めスプレッドシート上で設定したキーワードがPDFファイル内の文章に含まれていたら, そのPDFファイルをGoogleDrive上にアップロードします。
## 本ツール実装で学んだこと
GAS内の関数によりOCR等の高度な機能を実装することが出来ることが分かりました。
# PDF自動印刷ツール
「GASによるGMail添付PDFファイル自動選別・アップロードツール」で保存された複数のPDFファイルをまとめて自動で印刷する為のツールです。
## 依頼背景(作成背景)
「GASによるGMail添付PDFファイル自動選別・アップロードツール」で保存された複数のPDFファイルを一つ一つ印刷するのはユーザーに大変, 負担がかかると考え, 本自動印刷ツールをお客様にご提案し,承諾して頂いた為,作成しました。
## 機能
PDFファイルが入っているフォルダを読み込み, そのフォルダに入っているPDFファイルを全て自動で印刷します。尚, 使用されるプリンターはPCで設定している既定のプリンターです。
## 本ツール実装で学んだこと
ご要望をお聞きするだけではなく,ご要望実現に伴い,あった方が良い機能・ツールを自ら思考し,ご提案することがお客様のご満足度を上げるのに繋がることが分かりました。

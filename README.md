# Dチャのプロジェクト構成
<font size="1">

| | カテゴリ | プロジェクト | 説明 | Mavenプロファイル<br>(ビルド対象プロジェクト) |
|:---|:---|:---|:---|:---|
| | Union | (Union) | Dチャ全体を管理するための統合プロジェクト | tool　(ローカルライブラリ),<br> common　(Commonカテゴリ),<br> online　(OnlineServiceカテゴリ),<br> ouen　(ParentalSiteカテゴリ),<br> manage　(ManagementSiteカテゴリ),<br> batch　(Batchカテゴリ) |
| | Common | Union-Common | Dチャ共通を管理するための統合プロジェクト | main　(dcha.common.constants, dcha.common.entities, dcha.common.interfaces, Libraries, Libraries_mail) |
| |  | dcha.common.constants | 定数クラスを管理する |  |
| |  | dcha.common.entities | エンティティクラスを管理する |  |
| |  | dcha.common.interfaces | インターフェースクラスを管理する |  |
| |  | Libraries | Dチャ共通ライブラリ |  |
| |  | Libraries_mail | Dチャ共通メールライブラリ |  |
| ★ | OnlineService | (OnlineService) | オンライン |  |
| | WebContentsAPI | (WebContentsAPI) | WebコンテンツAPI | ※gradleのため個別 |
| |  | dcha-webapi-common | WebコンテンツAPIの共通 |  |
| |  | dcha-webapi-core | WebコンテンツAPIのコア |  |
| ★ |  | dcha-webapi-main | WebコンテンツAPIのメイン |  |
| | ParentalSite | Union-ParentalSite | 保護者サイトを管理するための統合プロジェクト | main　(dcha.ouen, dcha.ouen.url),<br> tool　(stub-mycha-api) |
| ★ |  | dcha.ouen | 保護者サイト |  |
| |  | dcha.ouen.url | 保護者サイトURL生成ライブラリ |  |
| |  | stub-mycha-api | MyチャAPIのスタブ |  |
| ★ | ManagementSite | (ManagementSite) | 管理者サイト |  |
| | Batch | Union-Batch | バッチを管理するための統合プロジェクト | main　(Batch, CaBatch, KansuishaBatch, XmlBatch) |
| ★ |  | Batch | バッチ |  |
| ★ |  | CaBatch | 計算アプリバッチ |  |
| ★ |  | KansuishaBatch | 完遂者バッチ |  |
| ★ |  | XmlBatch | XMLバッチ |  |
| |  | Systemwalker | ジョブ定義 |  |
| |  | Odi | ODI連携 |  |

★　…　主要なプロジェクト

</font>

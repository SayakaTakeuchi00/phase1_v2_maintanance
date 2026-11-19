---
layout: page
title: AR ph1 運用フロー
permalink: /ar-ph1-operation/
---

AR ph1運用における依頼受付からデータ反映までの手順、担当、備考を整理しています。

| No. | 手順 | 担当 | 備考 | 参考リンク |
| --- | --- | --- | --- | --- |
| 1 | JIRAから起票 | 営業 |  | [Rakuten Analytics For Brandsの依頼 Form](https://confluence.rakuten-it.com/confluence/spaces/AIO/pages/6850294166/Rakuten+Analytics+For+Brands%E3%81%AE%E4%BE%9D%E9%A0%BC+Form) |
| 2 | Teamsでの連絡 | 営業 |  |  |
| 3 | 各依頼に応じて依頼フォーマットを整える、必要な情報を揃える | AIO（中原さん） |  |  |
| 4 | 3ができ次第、開発向けの依頼JIRAを起票する | AIO（中原さん） |  | [FBARBUプロジェクトの課題一覧](https://jira.rakuten-it.com/jira/projects/FBARBU/issues/) |
| 5 | 必要に応じてDKDにフィルターファイル作成依頼を行う | AIO（佐藤さん） |  |  |
| 6 | 依頼に応じたAIO側のマスタ更新を行う | AIO（佐藤さん、竹内） |  | [佐藤対応内容説明](https://confluence.rakuten-it.com/confluence/spaces/AIO/pages/6863144149/%E4%BD%90%E8%97%A4%E5%AF%BE%E5%BF%9C%E5%86%85%E5%AE%B9%E8%AA%AC%E6%98%8E) |
| 7 | マスタ確認を行う（validation check） | AIO（竹内）、GATD（大西さん） | 年内 | [AR Master Update Check](https://confluence.rakuten-it.com/confluence/spaces/MKDB/pages/6921663002/AR+Master+Update+Check) |
| 8 | 問題なければADED指定のBoxにマスタをtsvファイルにして、格納する。データ更新の反映日、クライアント指定を行う。 | AIO（竹内） | SS時期を避けるなど条件あり。指定日の2週間前にADED側で本番リリース申請が必要。 | [Brand Maintenance Delivery](https://confluence.rakuten-it.com/confluence/x/3DyqoQE) |
| 9 | 指定した反映日にデータの更新作業を行う。 | ADED |  |  |

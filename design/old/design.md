# 設計書

# 概要

本ドキュメントは、3D 都市モデル「Plateau」を使用したプログラミングと統計機械学習の学習用 Web サービスの開発についての設計書である。

# システム設計

## コンポーネント構成

本システムは、以下のコンポーネントから構成される。

| コンポーネント名       | 機能                                                                                       |
| ---------------------- | ------------------------------------------------------------------------------------------ |
| web サーバ             | ユーザーからのリクエストを受け取り、静的コンテンツを提供する。                             |
| アプリケーションサーバ | 学習コンテンツ管理、ユーザー管理、対話型コーディング環境の機能を実装する。                 |
| データベースサーバ     | ユーザー情報、学習コンテンツ、ユーザーの学習進捗、コーディング環境のデータなどを保存する。 |

## ネットワーク構成

<!-- AWSのアーキテクチャ記載する -->

## 使用する言語・ミドルウェアのバージョン

<!-- 仮おき。技術選定の際に詳細を決める。 -->

|      項目      |           技術            | バージョン | 詳細                                     |
| :------------: | :-----------------------: | :--------: | :--------------------------------------- |
| フロントエンド |         React.js          |   v18.0    | ユーザインターフェースの作成に使用する。 |
| フロントエンド |         Three.js          |    r130    | 3D モデルのレンダリングに使用する。      |
|  バックエンド  |          Python           |   v3.10    |                                          |
|  データベース  |                           |            | データストレージとして使用する。         |
| 3D 都市モデル  |          Plateau          |            |                                          |
|   コンテナ化   |          Docker           |            |                                          |
|    クラウド    | AWS (Amazon Web Services) |     -      | インフラとして使用する。                 |

# 機能設計

<!-- コンポーネントまたは機能毎に項目を分けて機能設計を行う。 -->

## 学習コンテンツ

## コーディング環境

## 学習進捗の可視化

## ユーザー管理

# 画面設計

## サイトマップ

[figma URL](https://www.figma.com/file/VJiOiy9VSHJai0a73iUv56/%E3%82%B5%E3%82%A4%E3%83%88%E3%83%9E%E3%83%83%E3%83%97?type=whiteboard&node-id=0-1&t=t6i4SRKVEOY0TC9F-0)

![サイトマップ](image/サイトマップ.png)

## ワイヤーフレーム

[figma URL](https://www.figma.com/file/UkDpYPAXCMK2xBxcXA1Hkf/%E3%83%AF%E3%82%A4%E3%83%A4%E3%83%BC%E3%83%95%E3%83%AC%E3%83%BC%E3%83%A0?type=design&node-id=13-140&mode=design&t=t6i4SRKVEOY0TC9F-0)

## システム概要図

<!-- システム概要を示す図(figma)が1枚以上あると、発表のときにも使えると思います -->

## UIデザイン

<!-- 各画面のデザインを作成したら, こちらにfigmaのURLを記載してください-->

# データ設計

## 論理設計

<!-- RDBかNoSQLか未定ですが, データモデリングについて記載します -->
<!-- 必要であれば, テーブル定義書やER図とかも書きます -->

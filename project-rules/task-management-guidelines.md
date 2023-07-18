# タスク管理ツール運用ドキュメント

## 1. 概要

本ドキュメントは、タスク管理ツール(github Projects)の運用方法について解説する。

## 2. ボードの各項目について

本プロジェクトはアジャイル方式を採用していることから、ボードに以下の項目を作成した。

- Product Backlog
- Sprint Backlog
- In Progress
- Sprint Complete

### 2.1 Product Backlog

プロジェクトで行われるべきすべてのタスクが一覧表示される。これらのタスクはまだスプリントに割り当てられていない。

### 2.2 Sprint Backlog

現在のスプリントで実行予定のタスクが表示される。各スプリント開始時に、そのスプリントで行うべきタスクを Product Backlog から Sprint Backlog へ移動させる。

### 2.3 In Progress

進行中のタスクが表示される。各メンバーが作業を開始するタスクを Sprint Backlog から In Progress へ移動させる。

### 2.4 Sprint Complete

そのスプリントで完了したタスクが表示される。タスクが完了次第 In Progress から Sprint Backlog へ移動させる。Sprint Complete は各 Sprint 毎に作成する。

## 3. ボードの使用方法

- 新しいタスクは Product Backlog に追加する。
  - タスクは基本的に issue から作成すること。
- スプリント開始時に担当タスクを Sprint Backlog へ移動する。
- タスク開始時にタスクを In Progress へ移動する
- タスク完了時にタスクを現在の Sprint Complete へ移動する。

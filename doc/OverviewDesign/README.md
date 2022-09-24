# NavigationApp/docs/OverviewDesign

| version | date      | description |
| ------- | --------- | ----------- |
| 1.0.0   | 2022/4/19 | 新規作成    |

[要件定義 doc](/doc/Requirements/README.md)

## 保存するログの通信概要

![system_overview](/img/OverviewDesign/system_overview.png)

## 保存するログの内容

![data_overview](/img/OverviewDesign/data_overview.png)

## 使用言語・フレームワーク

### Client

- 言語: dart
- フレームワーク: flutter
- ライブラリ: 未定

### Firebase functions

- 言語: Typescript
- ライブラリ:
  - express
  - fs
  - ini

### Database

- NoSQL
- Firestore Database

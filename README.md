<p align="center"><img src="https://raw.githubusercontent.com/propropg/musubi-sql/main/icon.png" width="128" alt=""></p>

<h1 align="center">Musubi SQL</h1>

<p align="center">無料のデータベースクライアント（Windows / Mac）<br>A free database client for Windows and macOS</p>

---

このリポジトリは **Musubi SQL の配布用**です。ソースコードは置いていません。
最新版は [Releases](https://github.com/propropg/musubi-sql/releases/latest) からダウンロードできます。

## 入手

| OS | 入手方法 |
|---|---|
| Windows 10（1809 以降）/ 11 | **[Microsoft Store](https://apps.microsoft.com/detail/9NW1F4WZ084R)**（おすすめ。自動で更新されます）<br>または [Releases](https://github.com/propropg/musubi-sql/releases/latest) のインストーラ（`MusubiSQL-Setup-<版>.exe`）・ポータブル版（`MusubiSQL-Portable-<版>-x64.zip`） |
| macOS 12 以降 | [Releases](https://github.com/propropg/musubi-sql/releases/latest) の dmg（Apple Silicon 用 `-arm64.dmg` / Intel 用 `-x64.dmg`） |

インストーラ・ポータブル版・dmg はコード署名をしていないため、初回の起動時に Windows SmartScreen や macOS Gatekeeper の確認が出ます。許可の手順は、配布ファイルに入っている「はじめにお読みください」をご覧ください。

## できること

- **9 種類の接続**：SQL Server・PostgreSQL・MySQL / MariaDB・Oracle・SQLite は追加のドライバなしで接続。SQL Server Compact・LocalDB・ODBC・JDBC にも対応。SSH トンネル・SSL / TLS
- **論理名の表示**：テーブル・カラムのコメントを論理名として、ツリー・表・SQL の結果・ER 図に表示
- **SQL の実行**：入力中のチェック、実行計画のツリー表示、変数、整形、実行履歴
- **表の編集**：Excel の感覚で編集して反映。CSV・Excel の取り込み、各種形式へのエクスポート
- **ER 図**：外部キーから自動で作成。設計・DDL の生成、PDF・SVG 出力
- **SQL ビルダ**：テーブルを並べて線でつなぐだけで SELECT などを作成
- **テストデータの生成**、**テーブル定義書**（Excel・HTML）、**サーバーの監視**
- 画面は日本語・英語

## 使用許諾条件・免責事項

- **無料**で使えます（個人・会社とも。業務での使用を含みます）
- 改変・他のソフトウェアへの組み込み、販売・有償での配布、改変したものの配布、リバースエンジニアリングは禁止です。配布されたファイルを改変せず、無償で他の人に渡すことはできます
- オープンソースではありません。詳しくは、アプリに同梱の「使用許諾条件」をご覧ください（初回起動時に同意を求めます）
- **Musubi SQL はデータベースの内容を直接変更・削除できるツールです。使用によって生じたデータの消失・破損などについて、作者は責任を負いません。** 本番環境で使う前に検証用の環境で確認し、必ずバックアップを取ってからお使いください

---

## English

This repository hosts the **downloads of Musubi SQL** (no source code).

- **Windows 10 (1809+) / 11**: [Microsoft Store](https://apps.microsoft.com/detail/9NW1F4WZ084R) (recommended, auto-updates), or the installer / portable zip on [Releases](https://github.com/propropg/musubi-sql/releases/latest)
- **macOS 12+**: dmg on [Releases](https://github.com/propropg/musubi-sql/releases/latest) (`-arm64` for Apple Silicon, `-x64` for Intel)

Free for personal and commercial use. Modification, resale, paid redistribution and reverse engineering are not permitted. This is not open source software. Musubi SQL can modify and delete database contents directly; the author accepts no responsibility for any data loss or damage. Always back up your data first.

© 2026 propropg

# TinyFileManager OhYeah! Custom

## 主旨
[TinyFileManager 2.6](https://github.com) をベースにした、日本語環境と安全性を強化したカスタム版です。

## 主な変更点
1. **日本語マルチコードページ対応**: 各種日本エンコーディングのファイルをテキストプレビューとエディタで表示・編集可能です。
2. **テキスト保存時の自動バックアップ**: エディタで保存する前に元ファイルをタイムスタンプ付きファイル名にリネームコピーします。
3. **アップロード時のサーバファイル自動バックアップ**: サーバに同名ファイルがある場合、サーバファイルをタイムスタンプ付きファイル名にリネームします(dropzone 使用時のみ)。
4. **アップロードファイルのタイムスタンプ同期**: アップロードされたファイルのタイムスタンプは元ファイルのタイムスタンプを引き継ぎます(dropzone 使用時のみ)。
5. **$root_path のユーザホーム自動設定**: TFM 本体をどこにおいてもユーザホームディレクトリまで遡れます。
6. **初期表示ディレクトリ設定**: TFM 本体をどこにおいても `p` パラメータ付き URL で呼べば指定したディレクトリが表示されます。

本プロジェクトには、オリジナル [TinyFileManager](https://github.com) リポジトリの `translation.json` を含みます。

---

## Description
This is a customized version of [TinyFileManager 2.6](https://github.com), enhanced for Japanese character encoding support and improved data safety.

## Key Changes
1. **Japanese Multi-Codepage Support**: Enhanced text preview and editor for Japanese character encodings.
2. **Auto-Backup on Save**: Automatically creates a timestamped backup of the original file before saving changes.
3. **Auto-Backup on Upload**: If a file with the same name exists on the server, it is renamed with a timestamp as a backup before the new file is uploaded (Ajax only).
4. **Timestamp Synchronization**: Preserves the original file's timestamp when uploading (Ajax only).
5. **Automatic $root_path Detection**: Automatically sets the root path to the user's home directory regardless of the script's location.
6. **Initial Directory via Parameter**: Supports the `p` parameter in the URL to open a specific directory on startup.

This project includes `translation.json` from the original [TinyFileManager](https://github.com) repository.

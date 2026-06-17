# git-practice

## Overview / 概要

`git-practice` は、GitとGitHubの基本操作を学ぶための練習用リポジトリです。

ローカルでファイルを編集し、コミットを作成し、ブランチを使って変更を管理する流れを確認することを目的としています。

## Purpose / 学習目的

- Gitリポジトリの作成と管理を練習する
- ファイル変更を `git status` で確認する
- `git add` と `git commit` の流れを理解する
- ブランチを作成して変更を分ける
- GitHub上でPull RequestとMergeの流れを確認する
- READMEに学習内容を記録する習慣をつける

## Tech Stack / 使用技術

| Category | Technology |
|----------|------------|
| Version Control | Git |
| Repository Hosting | GitHub |
| Documentation | Markdown |

## Project Structure / ファイル構成

```text
.
├── README.md  # プロジェクト説明
└── reade.md   # Git操作練習用のファイル
```

## Git Workflow / Git操作の流れ

このリポジトリでは、以下のような基本操作を練習します。

```bash
git status
git add README.md
git commit -m "Update README"
git branch
git push origin master
```

ブランチを使う場合は、以下のような流れで作業できます。

```bash
git checkout -b practice-branch
git add .
git commit -m "Practice branch update"
git push origin practice-branch
```

## What I Learned / 学んだこと

- `git status` で作業ツリーの状態を確認できる
- `git add` でコミット対象をステージできる
- `git commit` で変更履歴を残せる
- ブランチを使うと、作業内容を安全に分けて管理できる
- GitHub上でPull Requestを作成し、変更内容を確認してからMergeできる

## Status / 状態

このリポジトリはGit/GitHubの基本操作を確認するための学習用プロジェクトです。

今後追加できる内容:

- Gitコマンドの練習メモ
- Pull Request作成手順
- MergeやConflict解消の練習記録
- GitHub Flowのまとめ

## License / ライセンス

ライセンスファイルはまだ追加していません。

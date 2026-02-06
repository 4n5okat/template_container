# コンテナリポジトリのテンプレート

<!-- ![]() -->

---

## 概要

- Dockerコンテナ環境を構築するためのテンプレートリポジトリ
- アプリケーション等を構築する際に利用する

---

## 目次

- [コンテナリポジトリのテンプレート](#コンテナリポジトリのテンプレート)
  - [概要](#概要)
  - [目次](#目次)
  - [リポジトリ構成図](#リポジトリ構成図)
  - [開発手順](#開発手順)
  - [共通ドキュメント](#共通ドキュメント)
  - [参考リンク](#参考リンク)

---

## リポジトリ構成図

```md
.
├── .devcontainer/
│   └── devcontainer.json
├── .gitlab/
│   ├── issue_templates/
│   │   ├── BUG.md
│   │   ├── FEATURE.md
│   │   ├── IMPROVEMENT.md
│   │   ├── REFACTOR.md
│   │   ├── RESEARCH_SPIKE.md
│   │   └── TASK.md
│   └── merge_request_templates/
│       ├── DEVELOP.md
│       ├── MAIN.md
│       └── RELEASE.md
├── .vscode/
│   └── settings.json
├── docs/
│   ├── common/
│   │   ├── ENVIRONMENT-BUILDING.md
│   │   ├── GIT.md
│   │   └── MISE.md
│   └── scoop/
│       ├── PACKAGES.md
│       └── SCOOP.md
├── infrastructure/
│   └── service_name/
│       └── Dockerfile
├── .dockerignore
├── .env.example
├── .gitignore
├── API.rest
├── compose.yml
├── mise.toml
└── README.md
```

[Tree リンク](https://tree.nathanfriend.com/?s=(%27optiJs!(%27fancy7~fullPath!false~trailingSlash7~rootDot7)~8(%278%27.404.jsJXlab0issue5BUG6FEATURE6IMPROVEMENTYFACTORYSEARCH_SPIKE6TASK30mQge_request5DEVELOP6MAINYLEASE32.vscode0settings.jsJ2docs0commJ*ENVIRONMENT-BUILDING6GIT6MISE30scoop*PACKAGES6SCOOP32infrastructure0sQvice_name*DockQfile2.dockQ9.env.exampleX9API.rest2compose.yml2mise.toml2README3%27)~vQsiJ!%271%27)*0W02W2%5Cn3.md4devcJtainQ5_templates*63*7!true8source!9ignore2JonQerW%20%20X2.gitY6RE%01YXWQJ987654320*)

---

## 開発手順

---

## 共通ドキュメント

- [開発環境構築](/docs/common/ENVIRONMENT-BUILDING.md)
- [採用Gitの運用ルール](/docs/common/GIT.md)
- [Miseタスクランナー](/docs/common/MISE.md)

---

## 参考リンク

- [GitLab 公式ドキュメント](https://docs.gitlab.com/ja-jp/)

---

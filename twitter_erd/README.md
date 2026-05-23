## フォルダ構成(※)

```text
twitter_erd/
├── outputs/    # 成果物
│   ├── logical.er
│   ├── normalization-check.md # 正規化チェックの記録
│   └── out.pdf
├── postgre/
│   ├── 01_create_twitter.sql # outputs/をもとに定義したDDL
│   └── docker-compose.yml
└── reqirements/
    └── requirements.md # 要件からデータ抽出・エンティティ定義の実施(※)

    ※機能要件からデータ（モノ・イベント）を抽出し、エンティティ定義を実施したときの記録です。
```

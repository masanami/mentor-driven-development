# ナレッジガイドライン

MDDフレームワークで使用するプロジェクト文書作成のガイドラインです。

## 使用方法

### 1. プロジェクト開始時

```bash
# プロジェクトのdocsフォルダにコピー
mkdir your-project/docs
cp knowledge-guidelines/documentation-guidelines.md your-project/docs/
```

### 2. エージェントへの参照指示

```
# プロジェクト開始時
@management "docs/documentation-guidelines.mdを確認して、このプロジェクトの文書作成方針を理解してください"

# 各フェーズでの活用
@requirements "docs/documentation-guidelines.mdに従って要件定義書を作成してください"
@design "docs/documentation-guidelines.mdの品質基準に従って設計書を作成してください"
```

## ファイル構成

- `documentation-guidelines.md`: 核となる文書作成指針
  - AI最適化された文書構造の原則
  - 品質保証のチェックポイント
  - エージェント向け記載ルール

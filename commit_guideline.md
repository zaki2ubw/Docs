# Git Commit Message Convention

## Format

```
<type>(<scope>): <subject>
```

* **type**: 変更の種類（下記参照）
* **scope**: どの部分を変更したか（例：projection, draw, init）
* **subject**: 変更の要約（命令形、英語）

---

## Types

| type     | 説明                  |
| -------- | ------------------- |
| feat     | 新機能の追加              |
| fix      | バグ修正                |
| refactor | リファクタリング（動作は変えない）   |
| chore    | その他の雑務（GitやCIの設定など） |
| docs     | ドキュメントの変更           |
| style    | フォーマット修正（動作に影響しない）  |
| test     | テストの追加・変更           |

---

## Examples

```
feat(projection): add isometric projection logic and scaling
fix(init): resolve segmentation fault when map is NULL
refactor(draw): simplify draw_line loop with helper
docs(commit): add commit convention in markdown
```

---

## Notes

* `subject` はなるべく 50 文字以内
* 末尾に `.`（ピリオド）は付けない
* 英語で書く（読みやすく簡潔に）


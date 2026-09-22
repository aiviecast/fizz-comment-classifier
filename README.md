# fizz-comment-classifier

**Fizz** (AITuber system in [Almide](https://github.com/almide/almide)) — §3 brain 部品。

コメント文面 → リアクション感情 (キーワードルール、先勝ち)。`classify(text) -> Option[Emotion]`。

責務は一行で、入力 → 出力が型で言い切れる単位 (openaituber `docs/almide-component-breakdown.md` §3)。

## Install

```toml
[dependencies]
fizz_comment_classifier = { git = "https://github.com/aiviecast/fizz-comment-classifier", tag = "v0.1.0" }
```

## Tests

```bash
almide test
```

純ロジックなのでネットワーク・API キー不要でテストできる。

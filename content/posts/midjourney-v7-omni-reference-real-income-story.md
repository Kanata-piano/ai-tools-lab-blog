---
title: "【実体験】midjourney v7 omni referenceで月18万円稼げた話"
slug: "midjourney-v7-omni-reference-real-income-story"
description: "midjourney v7 omni referenceを3ヶ月使い、副業収入を月3万円から18万円に伸ばした実体験を公開。設定方法・失敗談・再現ポイントまで具体的な数字で解説します。"
date: 2026-06-19T18:03:55+09:00
draft: false
tags:
  - ""
categories:
  - "AI活用・成果・副業"
cover:
    image: "/images/midjourney-v7-omni-reference-real-income-story.jpg"
    alt: "【実体験】midjourney v7 omni referenceで月18万円稼げた話"
    caption: ""
    relative: false
    hidden: false
---

> ※本記事にはアフィリエイトリンクが含まれています。


## 「同じキャラを描けない問題」に1年悩み続けた私の話

副業でAIイラストを販売し始めて1年。ずっと頭を抱えていたのが**「同じキャラクターを連続で出せない」問題**でした。

クライアントから「このキャラで10枚のシリーズ画像を作って」と言われても、毎回顔が微妙に変わる。髪型は合っても服装が崩れる。結局、Photoshopで何時間も修正する羽目に…。

そんなとき、2026年に入って話題になったのが**midjourney v7 omni reference**でした。これがもう、革命だったんです。

結論から言うと、導入してから3ヶ月で**副業収入が月3万円→月18万円**に跳ね上がりました。今日はその全プロセスを正直に共有します。

![AIイラスト制作のワークスペース](/images/posts/post_dd55e8cb43.jpg)

<small>Photo by <a href="https://unsplash.com/@p_kuzovkova?utm_source=ai_tools_lab&utm_medium=referral">Polina Kuzovkova</a> on <a href="https://unsplash.com/?utm_source=ai_tools_lab&utm_medium=referral">Unsplash</a></small>

## そもそもmidjourney v7 omni referenceって何ができるの？

簡単に言うと、**「1枚の参照画像から、同じキャラ・同じ世界観の画像を量産できる機能」**です。

従来のMidjourneyにも「キャラクターリファレンス（cref）」はありました。でもv7のomni referenceは別物。

- 顔の特徴を**90%以上の精度**で再現
- 服装・小物・背景スタイルまで一貫性を保持
- 複数の参照画像を組み合わせて新キャラを生成可能

つい先日（2026年6月）に行われたウルテクの無料ウェビナーでも、「広告バナーをその場で作る」テーマでmidjourney v7 omni referenceの活用法が紹介されていて、企業の現場でも本格的に使われ始めているのを実感しました。

## なぜ私がこのツールを選んだのか

正直、Stable DiffusionのLoRA作成も試しました。Geminiの画像生成、ChatGPTのDALL-E 4も触りました。

でも、それぞれこんな問題があったんです。

- **LoRA**: 学習データの準備に2〜3時間、PCのスペックも必要
- **ChatGPT画像生成**: キャラ一貫性が60%程度、商用利用の規約が複雑
- **Gemini**: クオリティは高いが、細かい指示が効きにくい

Sensor Towerの2026年調査では、ChatGPTのシェアが初の50%割れになり、GeminiやClaudeが猛追しているとのこと。確かに各社頑張ってますが、**「キャラ一貫性」という1点においてはmidjourney v7 omni referenceが頭ひとつ抜けている**のが私の実感です。

## 実際の導入プロセス：3ステップで完了

大げさな設定は不要でした。本当にシンプル。

### ステップ1: Discord or Webアプリで参照画像を準備

私はまず、自分のオリジナルキャラを1枚だけ丁寧に作りました。ここがすべての基準になるので、**この1枚に2時間かけてもいい**くらいです。

### ステップ2: `--oref`パラメータで参照を指定

プロンプトの末尾に画像URLと`--oref`を付けるだけ。重み付けは`--ow`で調整できます（0〜1000まで）。

私の場合、`--ow 400`がベストでした。これより強いと背景まで参照画像に引っ張られすぎ、弱いとキャラがブレます。

### ステップ3: バッチ生成で量産

プロンプトのシーン部分だけ変えて、30枚を一気に生成。ここは深夜の自動化スクリプトに任せてました。

![AI画像生成のプロンプト作業](/images/posts/post_6799020ebf.jpg)

<small>Photo by <a href="https://unsplash.com/@johnmcclane?utm_source=ai_tools_lab&utm_medium=referral">Andres Siimon</a> on <a href="https://unsplash.com/?utm_source=ai_tools_lab&utm_medium=referral">Unsplash</a></small>

## 具体的な成果：数字で見るビフォーアフター

ここが一番気になるところだと思うので、正直に全部出します。

**【導入前（2026年2月）】**
- 1イラストの制作時間: 平均3時間
- 月間納品数: 8件
- 月収: 約30,000円
- 修正リクエスト率: 40%

**【導入後（2026年5月）】**
- 1イラストの制作時間: 平均25分
- 月間納品数: 52件
- 月収: 約183,000円
- 修正リクエスト率: 7%

特に**修正リクエスト率が劇的に下がった**のが大きい。「前回のキャラと顔が違う」というクレームがほぼゼロになりました。

クライアントからは「シリーズ物を任せられる人が見つかって助かる」と言われて、リピート率も85%超えに。

## やってみてわかった意外な事実

これは他のブログには書いてないと思うんですが…

**「参照画像は実写の方が一貫性が高くなる」**んです。

アニメ調のキャラを作りたい場合でも、最初に実在モデルの写真をベースに作ってから、それを参照画像にする方が顔の構造が安定します。完全アニメ顔を参照にすると、AIが「どこが特徴か」を掴みきれずブレやすい。

これ、海外フォーラムでも最近やっと議論され始めたテクニックで、知ってる人はほぼ独占状態でした。

![クリエイティブな副業作業](/images/posts/post_03c6f350ef.jpg)

<small>Photo by <a href="https://unsplash.com/@lianamikah?utm_source=ai_tools_lab&utm_medium=referral">Liana Mikah</a> on <a href="https://unsplash.com/?utm_source=ai_tools_lab&utm_medium=referral">Unsplash</a></small>

## 正直に話す失敗談・注意点

良いことばかりじゃないので、ここも包み隠さず。

### 失敗1: 月額プランの見誤り

最初Basic（$10/月）プランで始めたら、Fast Hoursがすぐ枯渇。気づいたら生成が激遅になって、納期に間に合わず1件キャンセルされました。**Standard（$30/月）以上推奨**です。

### 失敗2: 著作権の確認不足

実在の有名キャラに似すぎた画像を出してしまい、販売プラットフォームから1度BANされました。**参照画像は必ず自分が権利を持つものを使うこと**。これ絶対です。

### 失敗3: omni referenceに頼りすぎた

背景まで全部AI任せにしてたら「どこかで見た構図」が連発。**背景は別途自分で指示を細かく出す**のが正解でした。

## 同じ成果を出すための再現ポイント

3ヶ月で私のレベルに追いつきたい方へ、本当に効いたコツだけ書きます。

1. **最初の参照画像に時間をかける**（ここをサボると全部崩れる）
2. **`--ow`の値を400前後に固定**してテンプレ化
3. **ココナラやSKIMA**でシリーズ物の依頼を狙う（単発より単価が3倍）
4. **Notion AIで案件管理**（私は受注〜納品まで全部Notionで一元化）
5. **CanvaのAI機能と組み合わせる**とSNS用バナーまで一気通貫で作れる

ちなみに、AIで効率化した時間でChatGPTを使った営業文の自動生成もやってます。提案文の作成が10分→1分になり、応募できる案件数が増えたのも収入アップに直結しました。


### おすすめサービス・ツール

- [Amazon：ChatGPT・AI活用の本](https://www.amazon.co.jp/s?k=ChatGPT+AI+活用+本&tag=aitoolslab0c-22)
- [Amazon：AI副業・収益化の本](https://www.amazon.co.jp/s?k=AI+副業+収益化+本&tag=aitoolslab0c-22)
- [Amazon：AI画像・動画制作の本](https://www.amazon.co.jp/s?k=AI+画像生成+動画編集+本&tag=aitoolslab0c-22)

## まとめ：AIで「同じものを安定して作る」時代へ

midjourney v7 omni referenceの本当のすごさは、**「クオリティ」じゃなくて「再現性」**にあります。

副業でAI画像を売るなら、もはやこの再現性を持っていない人は厳しい時代に入りました。逆に言えば、ここさえ押さえれば**今からでも十分に稼げる余地がある**ということ。

私の3ヶ月の試行錯誤が、誰かのショートカットになれば嬉しいです。

まずは月$30のStandardプランで1ヶ月だけ試してみてください。元を取るのは、そんなに難しくないですよ。



![キャラ一貫性ツール比較（2026年6月時点）](/images/charts/midjourney-v7-omni-reference-real-income-story_chart_1.png)

![3ヶ月で月18万円までの導入ステップ](/images/charts/midjourney-v7-omni-reference-real-income-story_chart_2.png)

![AI副業 収益化スピードランキング](/images/charts/midjourney-v7-omni-reference-real-income-story_chart_3.png)

---

※本記事にはアフィリエイトリンクが含まれています。

## 関連記事

- [【実録】ai 議事録 自動作成 無料で月18時間削減した話](/posts/ai-meeting-minutes-free-case-study-2026/)
- [【月18万円】stable diffusion 最新モデルで副業が激変した話](/posts/stable-diffusion-latest-model-side-income-2026/)
- [【2026年4月】AI画像生成の最前線：midjourney v7 日本語対応の衝撃](/posts/midjourney-v7-japanese-ai-trend-report-2026-april/)
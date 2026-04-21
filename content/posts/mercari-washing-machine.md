+++
date = '2026-04-20T16:38:35+09:00'
draft = false
title = '売ってから買う！メルカリで洗濯機を45,000円で売ってドラム式に買い替えた話'
tags = ["暮らし"]
+++

## はじめに

洗濯機をメルカリで売って、ドラム式に買い替えました。結果的に**32,760円の利益**が出たので、その体験談をシェアします。

## 売却の流れ

3月は引越しシーズンで家電需要が高まります。このタイミングを狙って出品したところ、**45,000円**で売却できました。

配送はメルカリの配送サービスを活用したので、手間もほとんどかかりませんでした。

## 買い替えの流れ

売ってから買うことで、二重払いなし、資金に余裕を持って新しいドラム式洗濯機を購入できました。

## まとめ

- 売却価格：45,000円
- ドラム式購入価格との差額：32,760円の利益
- 3月の需要期を狙うのがポイント
- 配送サービスを使えば手間なし

**売ってから買う**という順番が、お得でスムーズな買い替えの秘訣でした！cat > ~/irofull/hugo.toml << 'EOF'
baseURL = "https://irofull.pages.dev/"
languageCode = "ja"
title = "イロフル"
theme = "PaperMod"

[params]
  author = "irofull"
  description = "人生のあれこれを、色とりどりに。"
  homeInfoParams = true

[params.homeInfoParams]
  Title = "イロフル / irofull"
  Content = """
人生のあれこれを、色とりどりに。

\\# 暮らし　\\# なぜだろう　\\# ずっと考えてること　\\# 気づき　\\# 好きなこと（旅行・編み物・食べ物 etc…)

*Colorful Stories from Everyday Life — big questions, small joys, everything in between.*
"""

[menu]
  [[menu.main]]
    name = "ホーム"
    url = "/"
    weight = 1
  [[menu.main]]
    name = "記事一覧"
    url = "/posts/"
    weight = 2
  [[menu.main]]
    name = "About"
    url = "/about/"
    weight = 3
EOF

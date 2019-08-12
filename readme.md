## About Me
ArgoCDの調査用のリポジトリです
### V1.4
+ staging, productionの２つのディレクトリを持つ状態
+ staging
    + masterにマージされたタイミングでデプロイ
+ production
    + applications/production.yaml の `targetRevision`をもとにデプロイ
        + masterの特定のコミットにtagをつける(ex. v2.0)
        + `targetRevision`を変更してpush

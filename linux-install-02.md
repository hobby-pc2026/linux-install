Markdown

```mermaid
flowchart LR
    subgraph フェーズ1 [認知フェーズ]
        subgraph サブ1 [SNS流入]
            A[広告を見る] --> B[サイトへ遷移]
        end
        subgraph サブ2 [検索行動]
            B --> C[キーワード検索]
        end
        subgraph サブ3 [検索行動]
            C --> D[キーワード検索]
        end
    subgraph フェーズ2 [認知フェーズ]
    end
        subgraph サブ1 [SNS流入]
            D[広告を見る] --> E[サイトへ遷移]
        end
        subgraph サブ2 [検索行動]
            E --> F[キーワード検索]
        end
        subgraph サブ3 [検索行動]
            F --> G[キーワード検索]
        end
    subgraph フェーズ3 [購入フェーズ]
        G --> H[カート追加] --> E[決済完了]
    end
```

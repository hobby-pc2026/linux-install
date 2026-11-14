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
    end
    subgraph フェーズ2 [認知フェーズ]
        subgraph サブ4 [SNS流入]
            C --> E[サイトへ遷移]
        end
        subgraph サブ5 [検索行動]
            E --> F[キー検索]
        end
        subgraph サブ6 [検索行動]
            F --> G[キーワ検索]
        end
    end
    subgraph フェーズ3 [購入フェーズ]
        G --> H[カート追加] --> I[決済完了]
    end
```

Markdown

```mermaid
flowchart LR
    subgraph フェーズ1 [インストール・メディアの準備]

            A[.iso のダウンロード] --> B[USBメモリに書き込む]
    end
    subgraph フェーズ2 [ハードウェアの準備]
 
            B --> C[起動、BIOS・UEFIを設定]

            C --> E[サイトへ遷移]
     end
    subgraph フェーズ3 [OS・アプリのインストール]
        subgraph サブ5 [検索行動]
            E --> F[ロケール]
            F --> G[パーティション]
            G --> H[ID・パスワード] 
        end
        subgraph サブ8 [SNS流入]
            H --> I[日本語化]
        end
        subgraph サブ9 [検索行動]
            I --> J[アプリのインストール]
        end
    end
```

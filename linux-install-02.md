Markdown
```flowchart TD
    subgraph インストールメディアの準備
        A1[.iso ダウンロード] --> A2[USBメモリに書き込み]
    end
    subgraph ハードウェアの確認
        B1[起動、BIOS・UEFI設定] --> B2[wi-fi の準備]
    end
    subgraph インストール作業
        subgraph インストール本体
            C1[ロケール] --> C2[パーティション]
        end
        C2 --> C3[日本語化]
        C3 --> C4[アプリのインストール]
    end

    A2 --> B1
    B2 --> C1
```

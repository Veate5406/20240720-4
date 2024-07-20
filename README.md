# 20240720

## 7/20(六)~7/21(日)
### 東臺灣高中職生資安盛會


### GenAI 生成式AI 
- [ChatGPT](https://chatgpt.com/)
- Google[GEMINI](https://gemini.google.com/app?hl=zh-TW)
- Copilot 

### [prompt提示詞1](prompt1.md)
```
CIA TRIAD:Confidentiality, Integrity, and Availability
你是專家,請用十頁簡報說明CIA TRIAD
```
### 文生圖[prompt提示詞2](prompt2.md)
```
請為李白將進酒畫四幅水墨畫
```
#### ChatGPT
```
頁面 1: 封面
標題: CIA TRIAD
副標題: 資訊安全的三大支柱
演講者: [你的名字]
日期: [日期]

頁面 2: 介紹
標題: 什麼是CIA TRIAD?
內容:
CIA TRIAD 是資訊安全領域的核心概念，代表機密性（Confidentiality）、完整性（Integrity）和可用性（Availability）。這三個要素共同保護信息的安全性和可靠性。

頁面 3: 機密性
標題: 機密性 (Confidentiality)
內容:
保護信息不被未經授權的訪問。
使用加密、存取控制等技術手段。
例子: 密碼保護、身份驗證系統。

頁面 4: 機密性技術
標題: 機密性技術
內容:
加密技術: 保護傳輸中的數據。
存取控制: 限制用戶對敏感信息的訪問。
多因素身份驗證: 提升安全性。

頁面 5: 完整性
標題: 完整性 (Integrity)
內容:
確保信息的準確性和一致性。
防止未經授權的修改。
例子: 數據校驗、數字簽名。

頁面 6: 完整性技術
標題: 完整性技術
內容:
哈希函數: 生成數據的唯一指紋。
數字簽名: 確認數據來源的真實性。
版本控制: 追蹤和管理數據變更。

頁面 7: 可用性
標題: 可用性 (Availability)
內容:
確保合法用戶可以隨時訪問信息。
防止系統中斷和服務不可用。
例子: 冗餘系統、備份與恢復計劃。

頁面 8: 可用性技術
標題: 可用性技術
內容:
負載平衡: 分配流量以提高性能。
備份與恢復: 防止數據丟失。
防火牆與入侵檢測系統: 保護系統不受攻擊。

頁面 9: CIA TRIAD 的重要性
標題: CIA TRIAD 的重要性
內容:
保護敏感信息，防止數據洩露。
確保數據的完整性和準確性。
提高系統的可用性，避免業務中斷。

頁面 10: 結論
標題: 結論
內容:
CIA TRIAD 是資訊安全的基礎。
機密性、完整性和可用性共同保護信息安全。
採用適當的技術和策略以確保系統的安全性。

```
#### GEMINI
```

```
#### Copilot 
```

```
### C
```C
#include <stdio.h>

int main() {
    printf("九九乘法表\n");
    for(int i = 1; i <= 9; i++) {
        for(int j = 1; j <= 9; j++) {
            printf("%d x %d = %2d\t", i, j, i * j);
        }
        printf("\n");
    }
    return 0;
}

```
### C++
```
#include <iostream>
using namespace std;

int main() {
    cout << "九九乘法表" << endl;
    for (int i = 1; i <= 9; ++i) {
        for (int j = 1; j <= 9; ++j) {
            cout << i << " x " << j << " = " << i * j << "\t";
        }
        cout << endl;
    }
    return 0;
}

```

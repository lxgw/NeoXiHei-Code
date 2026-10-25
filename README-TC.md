[简体中文](README.md) | 繁體中文

> [!IMPORTANT]
> 本倉庫為附屬專案，**現已封存（唯讀），不再跟隨主專案更新**。
>
> 主專案仍會不定期進行必要維護，但本倉庫將不再同步這些更新。
>
> 如需取得包含最新字元或修復的版本，請直接使用主專案：
> - [霞鶩晰黑 / LXGW XiHei](https://github.com/lxgw/LxgwXiHei)
> - [霞鶩新晰黑 / LXGW XiHei](https://github.com/lxgw/LxgwNeoXiHei)
>
> 歷史版本仍可在此倉庫的 Releases 中下載。感謝您一直以來的支援！
>
> 本專案衍生自 IPA 字型，遵循 IPA Font License 1.0。若計劃將本專案字型用於嵌入式用途，請務必仔細閱讀 [IPA Font License 1.0](https://moji.or.jp/ipafont/license/) 條款，並參考[「嵌入須知」](https://github.com/lxgw/lxgw/blob/main/documents/xizhi_embedding_instructions.md)自行評估合規成本（該文件為簡體中文，請自備簡繁轉換工具）

# 新晰黑 Code & 晰黑 Code</br>NeoXiHei Code & XiHei Code
「霞鶩晰黑」「霞鶩新晰黑」與舊版 M+ 等寬字體的合併字型，可用於程式設計用途。

## 字型簡介
本字型基於 M+ 1M 和 IPA Gothic 的合併字型 [Migu 1M](https://itouhiro.github.io/mixfont-mplus-ipa/migu/) 再衍生，將漢字部分更換為[「霞鶩晰黑」](https://github.com/lxgw/LxgwXiHei)或[「霞鶩新晰黑」](https://github.com/lxgw/LxgwNeoXiHei)並作出其他調整，可作為[「霞鶩晰黑」](https://github.com/lxgw/LxgwXiHei)或[「霞鶩新晰黑」](https://github.com/lxgw/LxgwNeoXiHei)用於程式設計用途的等寬版本。

### 製作與調整
- 在 [Migu 1M](https://itouhiro.github.io/mixfont-mplus-ipa/migu/) 基礎上修改；
- 修改 `&`、`3`、`＠` 等字元為 M+ 2M 格式；
- 將一些顯示為 IPA Gothic 的非 CJK 字元（如 `§`、希臘字母、西里爾字母等）替換為 M+ 1M 樣式；
- 將漢字部分替換為[「霞鶩晰黑」](https://github.com/lxgw/LxgwXiHei)或[「霞鶩新晰黑」](https://github.com/lxgw/LxgwNeoXiHei)，並刪除 `jp90` 特性，補充部分來自晰黑或新晰黑的全形字元；
- 假名和標點符號保留 Migu 1M 樣式，惟「新晰黑 Code」`：；！？` 調整為靠左形式，「晰黑 Code」`，。、．` 調整為「霞鶩晰黑」的置中形式；
- 根據 Unicode 16.0 標準化變體序列（Standardized Variation Sequences, SVS），新增蝌蚪引號 `“‘’”` `“︁‘︁’︁”︁` 寬度選擇。

## 取得字型
- [點擊此處直接下載「晰黑 Code」](https://github.com/lxgw/NeoXiHei-Code/raw/main/XiHeiCode-Regular.ttf)。
- [點擊此處直接下載「新晰黑 Code」](https://github.com/lxgw/NeoXiHei-Code/raw/main/NeoXiHeiCode-Regular.ttf)。
- 此外提供 FCP 格式工程檔（[晰黑 Code](https://github.com/lxgw/NeoXiHei-Code/blob/main/XiHeiCode-Regular.fcp) | [新晰黑 Code](https://github.com/lxgw/NeoXiHei-Code/blob/main/NeoXiHeiCode-Regular.fcp)），便於二次開發字型。需要 15.0.0.3048 及更高版本的 FontCreator。

## 注意事項
- 部分環境中可能會顯示英文名稱 `NeoXiHei Code` 或 `XiHei Code`，敬請留意。
- 本字型不適合直排，亦無計畫提供 `liga` 特性支援。

## 授權資訊

- 本字型在 IPA 所開發併發布的 [IPA 字型](https://moji.or.jp/ipafont)基礎上衍生，基於 itouhiro 開發並發佈的 [Migu 1M](https://itouhiro.github.io/mixfont-mplus-ipa/migu/) 再衍生，依照 [IPA開放字型授權條款 第1.0版（IPA Font License 1.0）](https://opensource.org/licenses/IPA/) 授權。
- 您可以將本字型用於印刷品、數字文件、影視內容、海報廣告、包裝、出版物設計以及其他各種設計用途，包括商業和非商業用途；
  也可在本字型基礎上繼續改作衍生，惟衍生字型名稱（包括程式名、檔名、字型名）不得包含「IPA」字樣，且衍生字型須繼承相同授權許可（IPA Font License 1.0 與 SIL OFL 1.1 互不相容）。
- 根據 IPA Font License 1.0 有關條款，在沒有郵費、儲存媒介費用和手續費的情況下，須免費提供字型檔案，不得將字型檔案單獨售賣。
- 如果您要將本字型替換回 IPA 原始授權字型，請從 [IPA 字型 Ver.003.03 下載頁面](https://moji.or.jp/ipafont/ipa00303)獲取原始授權字型「IPA ゴシック」和「IPA 明朝」。  
  對於涉及字型檔案再分發的嵌入式應用（如應用程式、硬體裝置、網頁等嵌入），需要滿足 IPA 許可中針對衍生字型再分發的限制條件，[請點選此處](https://github.com/lxgw/LxgwNeoXiHei/blob/main/documentation/embedding_instructions.md)瞭解（跳轉到「霞鶩新晰黑」repo）。
- 有關 IPA Font License 1.0 的其他常見問題，請參閱 [FAQ（日語）](https://moji.or.jp/ipafont/faq)，需自備翻譯工具。
- 任何個人、企業、團隊等對本字型進行使用、複製、修改、分發等任意用途即視為您已完全閱讀、充分理解並同意 IPA Font License 1.0 授權協議。  
  「IPA 字型（IPA Font，IPAフォント）」為日本「獨立行政法人　資訊處理推進機構」（The Information-Technology Promotion Agency, “IPA”）的註冊商標。
  
### 字型授權相容性說明
- 舊版「M+ 1M」「M+ 2M」採用 [M+ FONTS 自有授權方式](https://spdx.org/licenses/mplus)（舊版 M+ 自有授權條款實質等效於 [0BSD](https://opensource.org/license/0BSD)；[新版 M+ 字型](https://mplusfonts.github.io)遵循 SIL OFL 1.1 開源授權，與 IPA 字型授權不相容）；
- 「IPA Gothic」「霞鶩新晰黑」「霞鶩晰黑」採用 [IPA Font License v1.0](IPA_Font_License_Agreement_v1.0.txt) 授權方式。

根據授權的相容性與傳染性，本字型採用 [IPA Font License v1.0](IPA_Font_License_Agreement_v1.0.txt) 授權。

## 參考資料

- [Migu 1M](https://itouhiro.github.io/mixfont-mplus-ipa/migu/)

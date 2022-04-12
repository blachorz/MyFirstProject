# [規劃] 虛幣應用

備註: 需要升級底層軟體，耗費約8個人天
2022/02/25 交付 Spec
排程走期: 2022/01/13 → 2022/03/31
狀態: Doing 🔨
重要性: ★★★★

<aside>
🧩 Spac：[https://cnyesrd.atlassian.net/wiki/spaces/PS/pages/1926627332](https://cnyesrd.atlassian.net/wiki/spaces/PS/pages/1926627332)

</aside>

# ＊**虛幣看盤**

# Product Story

## 目標 Objective

- **提升體驗**：提供虛擬貨幣彙整式的行情報價介面
- **掌握話題**：熱門區塊分類呈現，快速掌握話題幣種
- **互動推廣**：聚合多家合作廠商及實體課程活動，推廣虛擬貨幣知識點

## 關鍵結果 Key Result

- **PV 增加**：豐富內容創造話題與關注
- **停留時間增加**：友善且全面的內容增加使用者黏著度
- **推升轉換率**：透過互動引導促成點擊

# Pre-procedure

## 網址設定 URL

- 路徑
    
    
    | 專案 | 路徑 | 備註 |
    | --- | --- | --- |
    | fe_Crypto | crypto.cnyes.com/quote | 在完整版首頁推出前，暫代虛幣首頁也就是http://crypto.cnyes.com/ 也會導入此頁 |

## 搜尋引擎 SEO

- Sitemap.xml
    
    
    | Item | Content |
    | --- | --- |
    | title
    og:title | 虛擬貨幣看盤室 - Anue 鉅亨網 |
    | description
    og:description | 鉅亨虛擬貨幣，滿足您對新聞、知識與交易的需求。網羅國內數大虛擬／加密貨幣交易所，提供優質知識分享與開戶交易優惠等豐富資訊，協助投資人快速掌握虛擬貨幣的投資小撇步。 |
    | keywords | BTC, ETH, Defi, NFT, Polkadot, Solana, BSC, Meta, Game, 比特幣、以太幣、去中心化、非同質、波卡、元宇宙、遊戲、網格交易、虛擬貨幣、加密貨幣 |
    | og:type | website |
    | og:url | crypto.cnyes.com/quote |
    | og:site_name | Anue 鉅亨網 |
    | og:image | www.cnyes.com/static/anue-og-image.png |

## 網站數據 GA Tracking

- 相關設定
    
    
    | 項目 | ID | PV | Event |
    | --- | --- | --- | --- |
    | 全網 | UA-145056278-1 | V | 全網通用元件 |
    | 虛擬貨幣 | UA-145056278-7 | V |   |

## 問券調查 Survey

- 相關設定
    
    N/a
    

# Spacs

## 廣告規格 Ad spac

- 配置設定
    
    
    | 裝置 | 編號 | 版位／名稱 | 廣告代碼 | 規格 |
    | --- | --- | --- | --- | --- |
    | Desktop | 1 | 小圖走勢右方／右側方塊A | cnyes_crypto_300*250_1 | 300*250 |
    | Desktop | 2 | 新聞右方／右側全幅 | cnyes_crypto_300*250_2 | 300*250 |
    | Desktop | 3 | 新聞右方／右側全幅 | cnyes_crypto_300*600 | 300*600 |
    | Desktop | 4 | Footer正上方／下方橫幅 | cnyes_crypto_B_970*250 | 970*250 |
    | Mobile | 1 | Header正下方，置頂廣告 | mobile_crypto_300*120_1 | 300*120 |
    | Mobile | 2 | Header正下方，置頂廣告 | mobile_crypto_300*250_1 | 300*250 |
    | Mobile | 3 | Header正下方，置頂廣告 | mobile_crypto_300*250_2 | 300*250 |
    | Mobile | 4 | Footer正上方／下方橫幅 | mobile_crypto_300*120_2 | 300*120 |

## 畫面規格 UI Spac

- 各版型連結
    
    
    | 項目 | 網址 | 備註 |
    | --- | --- | --- |
    | OverView | https://zpl.io/llJMZ5z | 總覽頁面 |
    | GUI | https://zpl.io/RMgEZAv | 圖形使用元件 |
    | 1280-1440 | https://zpl.io/z8514pG | Desktop |
    | 375 | https://zpl.io/Q0A9Zgm | Mobile |
    | 768 | https://zpl.io/g8qrw7Z | Tablet |
- 快速預覽_Ｄ版
    
    ![虛幣看盤室_首頁 ver.0.5_1440.png](%5B%E8%A6%8F%E5%8A%83%5D%20%E8%99%9B%E5%B9%A3%E6%87%89%E7%94%A8%2017f64/%E8%99%9B%E5%B9%A3%E7%9C%8B%E7%9B%A4%E5%AE%A4_%E9%A6%96%E9%A0%81_ver.0.5_1440.png)
    
- 快速預覽_Ｍ版
    
    ![虛幣看盤室_首頁 ver.0.5_375.png](%5B%E8%A6%8F%E5%8A%83%5D%20%E8%99%9B%E5%B9%A3%E6%87%89%E7%94%A8%2017f64/%E8%99%9B%E5%B9%A3%E7%9C%8B%E7%9B%A4%E5%AE%A4_%E9%A6%96%E9%A0%81_ver.0.5_375.png)
    

## 表格規格 Table Spac

- 全域適用
    
    
    | 規則別 | 欄位樣貌 | 規則描述 | 備註 |
    | --- | --- | --- | --- |
    | Ｎ | 名稱 | 空間足夠，格式：全部顯示
    空間不足，格式：中文６字，超過... | 向左對齊
    點擊後，開新頁至：invest.cnyes.com/{商品類別}/{市場}/{代碼}
    未來台股內頁回歸 www.cnyes.com/twstock/{市場}/{代碼} 底下，是否在判斷區分時，需做調整？ |
    | Ｐ | 最新價 | 格式：依商品位數，不足補０ | 向右對齊，可參考萬用API FORMAT_V2 |
    | Ｃ | 漲跌 | 格式：±依商品位數，不足補０ | 向右對齊，可參考萬用API FORMAT_V2 |
    | Ｃ％ | 漲跌％ | 經單位換算後：
    空間足夠，格式：±換算機制.00％
    空間不足，格式：±換算機制％ | 向右對齊，換算機制的基準如下：
    常態：1.00~0,000.00%
    萬　：0,000萬%
    億　：0,000億%
    兆　：0,000兆% |
    | Ｖ | 金額／張數（量類別） | 經單位換算後：
    空間足夠，格式：換算機制.00 單位
    空間不足，格式：換算機制 單位 | 向右對齊，換算機制的基準如下：
    常態：1~999,999 整數
    百萬：100.00萬~9,999.00萬 小數２位
    億　：1.00億~9,999.00億 小數２位
    兆　：1.00兆~9,999.00兆 小數２位 |
    | Ａ | 一般揭露 | 經單位換算後：
    空間足夠，格式：換算機制.00
    空間不足，格式：換算機制 | 向右對齊，換算機制的基準如下：
    常態：1.00~999,999.00 資料小數位數
    百萬：100.00萬~9,999.00萬 小數２位
    億　：1.00億~9,999.00億 小數２位
    兆　：1.00兆~9,999.00兆 小數２位 |
- 規格化表格
    
    Table：分類連動報價表
    
    | 名稱 | 最新價 | 漲跌％ | 變動欄（隨項目變動） |
    | --- | --- | --- | --- |
    | 規則Ｎ | 規則Ｐ | 規則Ｃ％ | 規則Ｖ
    規則Ｃ％ |

## 物件規格 Item Spac

### 頁面更新

<aside>
⚠️ １、區塊進入可視範圍在 Send API Request
２、可視範圍內每 1 min 刷新資料
３、可視範圍只包含 active 的 tab
４、區塊資料載入中需要加上 skeleton screen 避免畫面 reflow

</aside>

### **架構說明**

> 復刻參照：[https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
新建頁面為的是提供互動看盤，由上依序往下區分三個區塊，會暫時頂替虛擬貨幣首頁
> 
> 
> <aside>
> ⚠️ **看盤區**：復刻路透外匯即時的樣式，將虛擬貨幣依照區塊呈現
> **廣告區**：Broker導轉元件、鉅亨熱門貼文（虛幣）、講座公告
> **新聞區**：虛幣新聞＆廣告
> 
> </aside>
> 
> - **內容架構圖**
>     
>     ![Untitled](%5B%E8%A6%8F%E5%8A%83%5D%20%E8%99%9B%E5%B9%A3%E6%87%89%E7%94%A8%2017f64/Untitled.png)
>     
- **內容框架**
    - **看盤區**
        - 看盤線圖：TradingView `Ｄ版`
            
            **畫面＆動作**
            
            - **比照設定**：路透即時外匯頁面 [https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
                - **元件使用**：Tradiing View 元件（即時、日、週、月）
                - **點擊互動**： 點擊「連動報表」內的整列，會切換至不同商品的線圖
                - 預設顯示
                    - 商品：CC:BTC:FOREX
                    - 週期：即時
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑
                    - 即時
                        - [https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=1&symbols={`商品代碼`}&from=1645677922&to=1630391689&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=1&symbols=CC:BTC:FOREX&from=1645677922&to=1630391689&quote=1) （正常顯示）
                        - [https://ws.api.cnyes.com/ws/api/v1/charting/history?resolution=1&symbol={`商品代碼`}&from=1630478089&to=1630391689&compress=1](https://ws.api.cnyes.com/ws/api/v1/charting/history?resolution=1&symbol=CC:BTC:FOREX&from=1630478089&to=1630391689&compress=1) （壓縮僅顯示一天）
                    - 日：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=D&symbols={`商品代碼`}&from=1645677922&to=1619863392&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=D&symbols=CC:BTC:FOREX&from=1645677922&to=1619863392&quote=1)
                    - 週：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=W&symbols{`商品代碼`}&from=1645677922&to=1619863392&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=W&symbols=CC:BTC:FOREX&from=1645677922&to=1619863392&quote=1)
                    - 月：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=M&symbols={`商品代碼`}&from=1645677922&to=1619863392&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=M&symbols=CC:BTC:FOREX&from=1645677922&to=1619863392&quote=1)
        - **連動列表** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **分類**
                - **項　　目**：行情、績效
                - **區　　塊**：主要、Defi、NFT、元宇宙、Polkadot、Solana、遊戲、BSC
                - **更新時間**：區塊右上角 **`格式：YYYY-MM-DD`**
                - **點擊互動**
                    - 項目區塊：點擊切換
                    - 商品列　：點選列可切換線圖、引導按鈕看內頁
            - 複合式欄位 **`FORMAT_V2`**
                - **行情報價**：[規則Ｐ](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
                - **常態欄位**：[規則Ａ](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
                - **百分比**　：[規則Ｃ％](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
                - **成交量／額／市值／發行股**：[規則Ｖ](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑
                    - 幣種：[https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&`column`=CC_K&page=1&limit=10&param=`rank`=700005;`order`=DESC;`type`={分類}](https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&column=CC_K&page=1&limit=10&param=rank=700005;order=DESC;type=metaverse)
                    - 績效：[https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&`column`=CC_P&page=1&limit=10&param=`rank`=700005;`order`=DESC;`type`={分類}](https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&column=CC_P&page=1&limit=10&param=rank=700005;order=DESC;type=metaverse)
                    - 參數
                        - `coulmn`：[幣種] CC_K、[績效] CC_P
                        - `rank`：[預設為市值] 700005
                        - 末端的`type`：
                            - 全部：all
                            - DeFi：defi
                            - NFT：nft
                            - 元宇宙：metaverse
                            - Polkadot：polkadot
                            - Solona：solana
                            - 遊戲：gaming
                            - BSC：binance-smart-chain
                        - `order`：DESC、ASC
                - **行情欄位**
                    - 代碼：`0`
                    - **名稱：`200009`**
                    - **最新價：`220026`**
                    - **漲跌：`220027`**
                    - **漲跌％：`200044`**
                    - **市值：`700005`**
                    - 成交量：`800001`
                - **績效欄位**
                    - **名稱：`200009`**
                    - **最新價：`220026`**
                    - 漲跌％：`56` 、**`200044`**
                    - **１週％：`200045`**
                    - **１月％：`200040`**
                    - **３月％：`200038`**
                    - **１年％：`200041`**
                    - ３年％：**`200047`**
                    - 年至今：**`200051`**
        - **走勢小圖** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁走勢小圖相關細節
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：[https://ws.api.beta.cnyes.cool/ws/api/v1/universal/charting?type=CCTOP5&page=1&limiit=4&resolution=1](https://ws.api.beta.cnyes.cool/ws/api/v1/universal/charting?type=CCTOP5&page=1&limiit=4&resolution=1)
    - ****廣告區****
        - **Broker導轉元件** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：iFrame崁入 [https://campaign.cnyes.com/topics/cryptov2/](https://campaign.cnyes.com/topics/cryptov2/)
        - **鉅亨專屬投資Line群** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - `Ｄ版` **點擊互動：**點擊QRcode 後，開新頁至*相關網址*
            - `Ｍ版` **點擊互動**：為Broker導轉元件的子頁籤，點擊公司 Logo 後，開新頁至*相關網址*
            - ***相關網址***：
                - **派網**：[https://line.me/ti/g2/hjqw64MjCvlfbLdON1TVZQ](https://line.me/ti/g2/hjqw64MjCvlfbLdON1TVZQ)
                - **ACE投資群**：[https://line.me/ti/g2/1XLRVNHebhBcO8n5R8PCsQ](https://line.me/ti/g2/1XLRVNHebhBcO8n5R8PCsQ)
                - 幣**安投資群**：[https://line.me/ti/g2/dpr6DEDNHQHYxkb4sqCPtQ](https://line.me/ti/g2/dpr6DEDNHQHYxkb4sqCPtQ)
                - **Bincentive投資群**：[https://line.me/ti/g2/fZhzlNsuORetY-U-C12-Dg](https://line.me/ti/g2/fZhzlNsuORetY-U-C12-Dg)
                - **POKKET投資群**：[https://line.me/ti/g2/cRPho3uzCwtAzwYrjRWPPXp-G9gqF0YOHzm8hA](https://line.me/ti/g2/cRPho3uzCwtAzwYrjRWPPXp-G9gqF0YOHzm8hA)
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
        - **鉅亨號熱門貼文** `Ｄ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁鉅亨號熱門貼文，但讀取內容改成虛擬貨幣（類別為：17）
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
        - **講座公告** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁講座公告
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
        - **最新優惠活動** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：虛擬貨幣推廣頁 [https://campaign.cnyes.com/topics/anuecrypto/](https://campaign.cnyes.com/topics/anuecrypto/)
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
    - ****新聞區****
        - **相關新聞** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：商品內頁的相關新聞
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：[https://api.beta.cnyes.cool/media/api/v1/newslist/category/bc](https://api.beta.cnyes.cool/media/api/v1/newslist/category/bc)
        - **新手村** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：商品內頁的相關新聞
            
            **資料＆欄位**
            
            - API&對應欄位
                - 。**路徑**：[https://api.cnyes.com/media/api/v1/newslist/category/bc_tutorial?page=1&limit=5](https://api.cnyes.com/media/api/v1/newslist/category/bc_tutorial?page=1&limit=5)
        - **影音節目** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：鉅亨早報影音節目
            
            **資料＆欄位**
            
            - API&對應欄位
                - **路徑**：[https://api.cnyes.com/video/api/v1/video/category/anue_cryptocurrency_world,cryptocurrency_beginner?page=1&limit=5](https://api.cnyes.com/video/api/v1/video/category/anue_cryptocurrency_world,cryptocurrency_beginner?page=1&limit=5)
- **表頭表尾**
    
    <aside>
    ⚠️ 若有更新 Header/ Footer 的最新版本，以最新版本為主（因為全站共用元件）
    
    </aside>
    
    **Header**
    
    - **Logo**：點擊回首頁
    - **畫面捲動**：時同現況，只有menu列會被置頂
    - **會員登入**
        - 尚未登入前顯示「登入/註冊」，點擊後原頁面跳轉導向登入頁[https://login.cnyes.com/](https://login.cnyes.com/)
        - 登入後轉跳回首頁，顯示用戶頭像＆用戶名稱
        - 全站搜尋同現況
    
    **Footer**
    
    - 揭露資訊源警語
    - 全站通用desktop footer
- **裝飾區**
    - **鉅亨買幣** `Ｄ版`
        
        **畫面＆動作**
        
        - 點擊互動：點擊後，開新頁面至 [https://campaign.cnyes.com/topics/anuecrypto/](https://campaign.cnyes.com/topics/anuecrypto/)
        
        **資料＆欄位**
        
        - API&對應欄位
            - 路徑：N/a
    - **下載鉅亨ＡＰＰ** `Ｄ版`
        
        **畫面＆動作**
        
        - **比照設定**：總首頁
        
        **資料＆欄位**
        
        - API&對應欄位
            - 路徑：N/a

# －－－－－－－－－－－

# ＊**虛幣內頁**

# Product Story

## 目標 Objective

- **提升體驗**：提供虛擬貨幣彙整式的行情報價介面
- **掌握話題**：熱門區塊分類呈現，快速掌握話題幣種
- **互動推廣**：聚合多家合作廠商及實體課程活動，推廣虛擬貨幣知識點

## 關鍵結果 Key Result

- **PV 增加**：豐富內容創造話題與關注
- **停留時間增加**：友善且全面的內容增加使用者黏著度
- **推升轉換率**：透過互動引導促成點擊

# Pre-procedure

## 網址設定 URL

- 路徑
- 頁籤

## 搜尋引擎 SEO

- Sitemap.xml
- 不同頁籤描述

## 網站數據 GA Tracking

- 相關設定

## 問券調查 Survey

- 相關設定

# Spacs

## 廣告規格 Ad spac

- 配置設定

## 介面規格 UI Spac

- 各版型連結
    
    

## 表格規格 Table Spac

- 全域適用
    
    
    | 規則別 | 欄位樣貌 | 規則描述 | 備註 |
    | --- | --- | --- | --- |
    | Ｎ | 名稱 | 空間足夠，格式：全部顯示
    空間不足，格式：中文６字，超過... | 向左對齊
    點擊後，開新頁至：invest.cnyes.com/{商品類別}/{市場}/{代碼}
    未來台股內頁回歸 www.cnyes.com/twstock/{市場}/{代碼} 底下，是否在判斷區分時，需做調整？ |
    | Ｐ | 最新價 | 格式：依商品位數，不足補０ | 向右對齊，可參考萬用API FORMAT_V2 |
    | Ｃ | 漲跌 | 格式：±依商品位數，不足補０ | 向右對齊，可參考萬用API FORMAT_V2 |
    | Ｃ％ | 漲跌％ | 經單位換算後：
    空間足夠，格式：±換算機制.00％
    空間不足，格式：±換算機制％ | 向右對齊，換算機制的基準如下：
    常態：1.00~0,000.00%
    萬　：0,000萬%
    億　：0,000億%
    兆　：0,000兆% |
    | Ｖ | 金額／張數（量類別） | 經單位換算後：
    空間足夠，格式：換算機制.00 單位
    空間不足，格式：換算機制 單位 | 向右對齊，換算機制的基準如下：
    常態：1~999,999 整數
    百萬：100.00萬~9,999.00萬 小數２位
    億　：1.00億~9,999.00億 小數２位
    兆　：1.00兆~9,999.00兆 小數２位 |
    | Ａ | 一般揭露 | 經單位換算後：
    空間足夠，格式：換算機制.00
    空間不足，格式：換算機制 | 向右對齊，換算機制的基準如下：
    常態：1.00~999,999.00 資料小數位數
    百萬：100.00萬~9,999.00萬 小數２位
    億　：1.00億~9,999.00億 小數２位
    兆　：1.00兆~9,999.00兆 小數２位 |
- 規格化表格
    
    Table：產業鏈關係、產業表現排行、產業財務排行
    
    | 名稱 | 最新價 | 漲跌％ | 變動欄（隨項目變動） |
    | --- | --- | --- | --- |
    | 規則Ｎ | 規則Ｐ | 規則Ｃ％ | 規則Ｖ
    規則Ｃ％ |

## 物件規格 Item Spac

### *頁面更新*

<aside>
⚠️ １、區塊進入可視範圍在 Send API Request
２、可視範圍內每 1 min 刷新資料
３、可視範圍只包含 active 的 tab
４、區塊資料載入中需要加上 skeleton screen 避免畫面 reflow

</aside>

### ***架構說明***

> ㄑ
> 
> 
> <aside>
> ⚠️ **看盤區**：復刻路透外匯即時的樣式，將虛擬貨幣依照區塊呈現
> **廣告區**：Broker導轉元件、鉅亨熱門貼文（虛幣）、講座公告
> **新聞區**：虛幣新聞＆廣告
> 
> </aside>
> 
> - **內容架構圖**
>     
>     ![Untitled](%5B%E8%A6%8F%E5%8A%83%5D%20%E8%99%9B%E5%B9%A3%E6%87%89%E7%94%A8%2017f64/Untitled.png)
>     
- **內容框架**
    - **看盤區**
        - 看盤線圖：TradingView `Ｄ版`
            
            **畫面＆動作**
            
            - **比照設定**：路透即時外匯頁面 [https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
                - **元件使用**：Tradiing View 元件（即時、日、週、月）
                - **點擊互動**： 點擊「連動報表」內的整列，會切換至不同商品的線圖
                - **預設顯示**
                    - **商品**：CC:BTC:FOREX
                    - **週期**：即時 ⋯⋯預設顯示的資料長度討論一下
                    - **線圖**：主圖與輔圖的比例需要調整一下 ⋯⋯討論一下
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑
                    - **即時** ⋯⋯看看之前設定為何，一起討論一下
                        
                        。正常顯示：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=1&symbols={`商品代碼`}&from=1645677922&to=1630391689&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=1&symbols=%7B%60%E5%95%86%E5%93%81%E4%BB%A3%E7%A2%BC%60%7D&from=1645677922&to=1630391689&quote=1)
                        
                        。壓縮一天：[https://ws.api.cnyes.com/ws/api/v1/charting/history?resolution=1&symbol={`商品代碼`}&from=1630478089&to=1630391689&compress=1](https://ws.api.cnyes.com/ws/api/v1/charting/history?resolution=1&symbol=%7B%60%E5%95%86%E5%93%81%E4%BB%A3%E7%A2%BC%60%7D&from=1630478089&to=1630391689&compress=1)
                        
                    - **日**：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=D&symbols={`商品代碼`}&from=1645677922&to=1619863392&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=D&symbols=%7B%60%E5%95%86%E5%93%81%E4%BB%A3%E7%A2%BC%60%7D&from=1645677922&to=1619863392&quote=1)
                    - **週**：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=W&symbols{`商品代碼`}&from=1645677922&to=1619863392&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=W&symbols%7B%60%E5%95%86%E5%93%81%E4%BB%A3%E7%A2%BC%60%7D&from=1645677922&to=1619863392&quote=1)
                    - **月**：[https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=M&symbols={`商品代碼`}&from=1645677922&to=1619863392&quote=1](https://ws.api.cnyes.com/ws/api/v1/charting/histories?resolution=M&symbols=%7B%60%E5%95%86%E5%93%81%E4%BB%A3%E7%A2%BC%60%7D&from=1645677922&to=1619863392&quote=1)
        - **連動列表** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **分類**
                - **項　　目**：行情、績效
                - **區　　塊**：主要、Defi、NFT、元宇宙、Polkadot、Solana、遊戲、BSC
                - **更新時間**：區塊右上角 **`格式：YYYY-MM-DD`**
                - **商品數量**：單頁最多１２項商品，超過以分頁切換表示
                - **點擊互動**
                    - **項目區塊**
                        - 點擊切換對應區塊的相關商品
                    - **商品列**
                        - 點選列（含空白處）可切換線圖
                        - 點選引導按鈕，開新頁面至該商品內頁
            - 複合式欄位 **`FORMAT_V2`**
                - **行情報價**：[規則Ｐ](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
                - **常態欄位**：[規則Ａ](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
                - **百分比**　：[規則Ｃ％](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
                - **成交量／額／市值／發行股**：[規則Ｖ](https://www.notion.so/1831595ede9049d29d5678a27a1bbefe)
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑
                    - **行情**：[https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&***column***=CC_K&page=1&limit=12&param=***rank***=700005;***order***=DESC;***type***=metaverse](https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&column=CC_K&page=1&limit=10&param=rank=700005;order=DESC;type=metaverse)
                    - **績效**：[https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&***column***=CC_P&page=1&limit=12&param=***rank***=700005;***order***=DESC;***type***=metaverse](https://ws.api.beta.cnyes.cool/ws/api/v4/universal/quote?type=CC_SELECTED_COLUMN.RANK&column=CC_P&page=1&limit=10&param=rank=700005;order=DESC;type=metaverse)
                    - **參數**
                        - `coulmn`：[幣種] CC_K、[績效] CC_P
                        - `rank`：[預設為市值] 700005
                        - `order`：DESC、ASC
                        - `末端的type`
                            - 全部：all
                            - DeFi：defi
                            - NFT：nft
                            - 元宇宙：metaverse
                            - Polkadot：polkadot
                            - Solana：solana
                            - 遊戲：gaming
                            - BSC：binance-smart-chain
                - **行情欄位**
                    - 代碼　：`0`
                    - 名稱　：`200009`
                    - 最新價：`220026`
                    - 漲跌　：`220027`
                    - 漲跌％：`200044`
                    - 市值　：`700005`
                    - 成交量：`800001`
                - **績效欄位**
                    - 代碼　：`0`
                    - 名稱　：`200009`
                    - 最新價：`56`、`200044`
                    - １週％：`200045`
                    - １月％：`200040`
                    - ３月％：`200038`
                    - １年％：`200041`
                    - ３年％：`200047`
                    - 年至今：`200051`
        - **走勢小圖** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁走勢小圖相關細節
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：[https://ws.api.beta.cnyes.cool/ws/api/v1/universal/charting?type=CCTOP5&page=1&limiit=4&resolution=1](https://ws.api.beta.cnyes.cool/ws/api/v1/universal/charting?type=CCTOP5&page=1&limiit=4&resolution=1)
    - ****廣告區****
        - **Broker導轉元件** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：[https://campaign.cnyes.com/topics/cryptov2/](https://campaign.cnyes.com/topics/cryptov2/)
        - **鉅亨專屬投資Line群** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **點擊互動：**點擊QRcode後，開新頁至
                - **派網**：[https://line.me/ti/g2/hjqw64MjCvlfbLdON1TVZQ](https://line.me/ti/g2/hjqw64MjCvlfbLdON1TVZQ)
                - **ACE投資群**：[https://line.me/ti/g2/1XLRVNHebhBcO8n5R8PCsQ](https://line.me/ti/g2/1XLRVNHebhBcO8n5R8PCsQ)
                - 幣**安投資群**：[https://line.me/ti/g2/dpr6DEDNHQHYxkb4sqCPtQ](https://line.me/ti/g2/dpr6DEDNHQHYxkb4sqCPtQ)
                - **Bincentive投資群**：[https://line.me/ti/g2/fZhzlNsuORetY-U-C12-Dg](https://line.me/ti/g2/fZhzlNsuORetY-U-C12-Dg)
                - **POKKET投資群**：[https://line.me/ti/g2/cRPho3uzCwtAzwYrjRWPPXp-G9gqF0YOHzm8hA](https://line.me/ti/g2/cRPho3uzCwtAzwYrjRWPPXp-G9gqF0YOHzm8hA)
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
        - **鉅亨號熱門貼文** `Ｄ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁鉅亨號熱門貼文，但讀取內容改成虛擬貨幣（類別為：17）
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
        - **講座公告** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：總首頁講座公告
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
        - **最新優惠活動** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：虛擬貨幣推廣頁 [https://campaign.cnyes.com/topics/anuecrypto/](https://campaign.cnyes.com/topics/anuecrypto/)
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：N/a
    - ****新聞區****
        - **相關新聞** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：商品內頁的相關新聞
            
            **資料＆欄位**
            
            - API&對應欄位
                - 路徑：[https://api.beta.cnyes.cool/media/api/v1/newslist/category/bc](https://api.beta.cnyes.cool/media/api/v1/newslist/category/bc)
        - **新手村** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：商品內頁的相關新聞
            
            **資料＆欄位**
            
            - API&對應欄位
                - 。**路徑**：[https://api.cnyes.com/media/api/v1/newslist/category/bc_tutorial?page=1&limit=5](https://api.cnyes.com/media/api/v1/newslist/category/bc_tutorial?page=1&limit=5)
        - **影音節目** `Ｄ版` `Ｍ版`
            
            **畫面＆動作**
            
            - **比照設定**：鉅亨早報影音節目
            
            **資料＆欄位**
            
            - API&對應欄位
                - **路徑**：[https://api.cnyes.com/video/api/v1/video/category/anue_cryptocurrency_world,cryptocurrency_beginner?page=1&limit=5](https://api.cnyes.com/video/api/v1/video/category/anue_cryptocurrency_world,cryptocurrency_beginner?page=1&limit=5)
- **表頭表尾**
    
    <aside>
    ⚠️ 若有更新 Header/ Footer 的最新版本，以最新版本為主（因為全站共用元件）
    
    </aside>
    
    **Header**
    
    - **Logo**：點擊回首頁
    - **畫面捲動**：時同現況，只有menu列會被置頂
    - **會員登入**
        - 尚未登入前顯示「登入/註冊」，點擊後原頁面跳轉導向登入頁[https://login.cnyes.com/](https://login.cnyes.com/)
        - 登入後轉跳回首頁，顯示用戶頭像＆用戶名稱
        - 全站搜尋同現況
    
    **Footer**
    
    - 揭露資訊源警語
    - 全站通用desktop footer
- **裝飾區**

Spec 架構 

- **比照設定**：路透即時外匯頁面 [https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
    - **元件使用**：Tradiing View 元件（即時、日、週、月）
    - **點擊互動**： 點擊「連動報表」內的整列，會切換至不同商品的線圖

- **比照設定**：路透即時外匯頁面 [https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
    - **元件使用**：Tradiing View 元件（即時、日、週、月）
    - **點擊互動**： 點擊「連動報表」內的整列，會切換至不同商品的線圖

- **比照設定**：路透即時外匯頁面 [https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
    - **元件使用**：Tradiing View 元件（即時、日、週、月）
    - **點擊互動**： 點擊「連動報表」內的整列，會切換至不同商品的線圖

- **比照設定**：路透即時外匯頁面 [https://www.cnyes.com/forex/reuters](https://www.cnyes.com/forex/reuters)
    - **元件使用**：Tradiing View 元件（即時、日、週、月）
    - **點擊互動**： 點擊「連動報表」內的整列，會切換至不同商品的線圖
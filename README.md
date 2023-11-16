# 臺灣健保藥價

將健保藥品給付資訊以手機App呈現

提供簡易查詢、價格走勢、許可證內容查詢、藥品供應資訊等功能

<a href='https://play.google.com/store/apps/details?id=org.lewispharmtech.drug_price_search'>
  <img alt='Get it on Google Play' src='https://play.google.com/intl/en_us/badges/images/generic/en_badge_web_generic.png' height="100"/>
</a>

## 螢幕截圖
<table>
  <tr>
    <td><img src="assets/screenshot_1.png" width=270 height=570></td>
    <td><img src="assets/screenshot_2.png" width=270 height=570></td>
    <td><img src="assets/screenshot_3.png" width=270 height=570></td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="assets/screenshot_4.png" width=270 height=570></td>
    <td><img src="assets/screenshot_5.png" width=270 height=570></td>
  </tr>
</table>

## 技術採用
- Flutter
- Bloc
- Isolate
- HTML parse
- third party packages:
  - archive (解壓縮)
  - shared_preferences (本地快取儲存)
  - drift (本地SQLite儲存)
  - fl_chart (價格圖表呈現)
  - url_launcher (網頁跳轉)

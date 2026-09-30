# china-gdp-per-capita

中国の一人当たりGDP（名目・米ドル建て）の時系列グラフです。
Time series chart of China's GDP per capita (current US$).

- **期間 / Coverage**: 1960–2025
- **指標 / Indicator**: GDP per capita (current US$) — World Bank, World Development Indicators `NY.GDP.PCAP.CD`
- **出典 / Source**: https://data.worldbank.org/indicator/NY.GDP.PCAP.CD?locations=CN （2026-10-01 取得 / retrieved）
- **実装 / Implementation**: 外部ライブラリ不使用の自己完結型HTML（vanilla JS + SVG）。リニア／対数スケール切替・期間切替・ホバーでの値表示に対応

## 公開ページ / Live page

GitHub Pages: https://katzkawai.github.io/china-gdp-per-capita/

## ファイル / Files

- `index.html` — グラフページ本体（この1ファイルだけで動作します）

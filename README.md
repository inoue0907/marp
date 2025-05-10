# marp

sited from 
https://github.com/kaisugi/marp-theme-academic
https://briboo-pc.hatenablog.jp/entry/2023/11/05/%E3%80%90Marp%E3%80%91%E3%82%B3%E3%83%94%E3%83%9A%E3%81%A7%E7%B0%A1%E5%8D%98%EF%BC%81%E5%A4%9A%E6%AE%B5%E7%B5%84%E3%81%BF%E3%82%B7%E3%83%B3%E3%83%97%E3%83%AB%E3%83%AC%E3%82%A4%E3%82%A2%E3%82%A6#Marp%E3%81%AE%E3%83%AC%E3%82%A4%E3%82%A2%E3%82%A6%E3%83%88%E3%81%AE%E4%BB%95%E7%B5%84%E3%81%BF

## usage
Add following item in the SettingsJSON of VScode
```
{
"markdown.marp.themes": [
    "https://raw.githubusercontent.com/inoue0907/marp/refs/heads/main/academic.css"
    ]
}
```
Start to write like this
```
---
marp: true
theme: academic
paginate: true
math: katex
---

<!-- _class: lead -->

---

<!-- _header: 3.1 差分スキームの精度 -->
```

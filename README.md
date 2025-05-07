# marp
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

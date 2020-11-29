---
title: Raw Identifiers
ddate: 2020-11-29 19:16 
tags: rust
categories:
- rust lang
toc: true
cover: /images/raw_indentifier_01.png
---

การระบบชื่อของ functions, variables, parameters, struct fields, modules, crates, constants, macros, static values, attributes, types, traits, or lifetimes. ใน rust บาง keywords จะไม่สามารถใช้ในการเขียนได้ ผมเรียกว่าคำสงวน
<!-- more -->
ดังภาพ ระบุชื่อฟังก์ชัน `match` rust-analyzer เเจ้งว่า fn match error ไม่สามารถใช้ระบุเป็นชื่อฟังก์ชันได้ 

![Raw Identifiers](/images/raw_indentifier_01.png)

วิธีที่เราจะสามารถใช้ keyword ได้ โดยการระบุ `r#` ตามด้วยคำสงวน เช่น `r#match` เพราะอาจจะมี library ที่ใช้คำสงวนเขียนจาก rust 2015 edition

![Raw Identifiers](/images/raw_indentifier_02.png)

อ่านเเล้วงงไหมล่ะ ผมก้งง
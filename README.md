# ตั้งค่าทีม Monokai Non-Italic สำหรับ vscode 
> Monokai theme ฟอนค์จะ`เอียง`
> Monokai Non-Italic theme ฟอนต์`ไม่เอียง` สามารถดาวโหลดและติดตั้งได้ที่ - [non-italic-monokai, By Neos21](https://marketplace.visualstudio.com/items?itemName=Neos21.non-italic-monokai)

# สามารถตั้งค่าเพิ่มเติมได้ในไฟล์ *.json
- เข้าไปที่โฟลเดอร์ `extensions/neos21.non-italic-monokai-0.0.2/themes`
- เปิดไฟล์ `non-italic-monokai.json`

## ในที่นี้ผมทำการตั้งค่าสองที่ ดังนี้
```sh
    "colors": {
        "editor.background": "#272822", //พื้นหลังตามสีพื้น monokai ของ sublime text3
    },
    "tokenColors": [
        {
            "name": "Comment",
            "scope": "comment",
            "settings": {
                "fontStyle": "italic", //ข้อความที่ถูกคอมเมนต์ให้ตัวอักษรเอียง
                "foreground": "#717270" 
            }
        },
    ]
```


<br>
<br>

---
<p align="center"> จัดทำโปรแกรมคอมพิวเตอร์พัฒนาระบบงานธุรกิจส่วนตัวและหน่วยงาน ใส่ใจคุณภาพ คุ้มราคา ส่งงานตรงเวลา<br>ติดต่อ 086-288-7987 (ท็อป) หรืออีเมล์    nakomah.web@gmail.com<br>ติดตามผลงานได้ที่ <a href="https://nakomah.com" target="_blank">www.nakomah.com</a></p>
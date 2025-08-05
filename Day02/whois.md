# Day 02 - [whois]

## 🔧 Tool: whois  
أداة whois تُستخدم لجمع معلومات تسجيل النطاقات (Domain Registration Info) مثل اسم المالك، الشركة، تاريخ الانتهاء، والخوادم المرتبطة بالنطاق.

## 📥 Installation:
```bash
sudo apt install whois
```

## ⚙️ Common Commands:
```bash
# البحث عن معلومات دومين
whois example.com

# حفظ النتائج في ملف
whois example.com > output.txt
```

## 🧠 Common uses:
- جمع معلومات عن المواقع المستهدفة في مرحلة الاستطلاع (Reconnaissance)
- التعرف على الشركة أو الأفراد خلف موقع معين
- التأكد من صلاحية الدومين وتاريخ انتهائه

## 📝 My Notes:
- الأداة سهلة وبسيطة، ما تحتاج إعدادات مسبقة.
- سويت فحص على نطاق (مثلاً: google.com)، وطلعت لي معلومات مثل:
  - اسم الشركة المسجلة (Google LLC)
  - تاريخ انتهاء الدومين
  - الـ Registrar (مثل: MarkMonitor أو GoDaddy)
- أحيانًا تطلع معلومات محجوبة (خاصة لو النطاق فيه حماية خصوصية)
- جربت أوامر مثل:
  ```bash
  whois example.com
  whois google.com


## 🔗 References:
- https://linux.die.net/man/1/whois
- https://www.geeksforgeeks.org/whois-command-in-linux-with-examples/

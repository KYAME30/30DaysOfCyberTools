# Day 03 - [theHarvester]

## 🔧 Tool: theHarvester  
أداة theHarvester تُستخدم لجمع معلومات عامة (OSINT) عن نطاق أو جهة مستهدفة، باستخدام محركات البحث ومصادر عامة للحصول على إيميلات، نطاقات فرعية، عناوين IP، إلخ.

## 📥 Installation:
```bash
sudo apt install theharvester
```

## ⚙️ Common Commands:
```bash
# جمع إيميلات ونطاقات فرعية باستخدام محرك Bing
theHarvester -d example.com -b bing

# استخدام محرك Google مع نتائج أكثر
theHarvester -d example.com -b google -l 100

# حفظ النتائج بصيغة HTML
theHarvester -d example.com -b bing -f output.html
```

## 🧠 Common uses:
- جمع معلومات أولية قبل تنفيذ اختبارات الاختراق
- اكتشاف الإيميلات المسربة
- تحديد البنية العامة للمجال المستهدف

## 📝 My Notes:
- جربت الأداة على نطاق مثل: `example.com`
- استخدمت محرك `bing`، وطلعت لي عدة إيميلات مرتبطة بالنطاق
- جربت كمان محرك `google` باستخدام:
  ```bash
  theHarvester -d example.com -b google -l 100


## 🔗 References:
- https://github.com/laramies/theHarvester
- https://tools.kali.org/information-gathering/theharvester

# Day 01 - [netdiscover]

## 🔧 Tool: [netdiscover]  
Netdiscover هي أداة تعتمد على ARP Requests لاكتشاف الأجهزة المتصلة بالشبكة المحلية (LAN) دون الحاجة إلى بروتوكولات مثل DHCP أو DNS.

## 📥 Installation:
```bash
sudo apt install netdiscover
```

## ⚙️ Common Commands:
```bash
## الوضع النشط (Active Scan)
sudo netdiscover -i eth0

## الوضع الصامت (Passive Mode)
sudo netdiscover -p

## تحديد الرينج (مثلاً شبكة 192.168.1.0/24)
sudo netdiscover -r 192.168.1.0/24

## فحص واجهات الشبكة
netdiscover -i <interface>
```

## 🧠 Common uses:
- معرفة الأجهزة المتصلة بالشبكة
- اكتشاف عناوين MAC
- معرفة الـ IP الداخلي للأجهزة
- تحليل الشبكة في بيئات بدون DHCP

## 📝 My Notes:
- اكتشف لي 5 أجهزة في الشبكة الداخلية.
- كانت النتائج واضحة وسريعة.
- لاحظت إن لازم أستخدم sudo عشان يشتغل تمام.
- لما جربت الوضع الصامت، ما ظهر شيء لأنه يحتاج وقت أطول.

## 🔗 References:
- https://tools.kali.org/information-gathering/netdiscover
- man netdiscover

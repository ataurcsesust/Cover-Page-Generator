# 🎓 DIU Cover Page Generator - Installation Guide

## 📋 যা যা প্রয়োজন:
- আপনার DIU Logo ছবি (PNG, JPG, SVG যেকোনো format)
- একটি Web Browser (Chrome, Firefox, Edge)
- একটি Text Editor (Notepad, VS Code, Sublime Text)

---

## 🚀 Installation Steps (ধাপে ধাপে):

### ধাপ ১: HTML File Save করুন
1. উপরের `index.html` এর সম্পূর্ণ code টি **copy** করুন
2. আপনার computer এ একটি folder তৈরি করুন: `DIU_Cover_Generator`
3. একটি text editor open করুন (Notepad)
4. Code টি paste করুন
5. File টি **Save As** করুন নাম দিয়ে: `index.html`
   - **Important:** নিশ্চিত করুন file extension `.html` আছে
   - "Save as type" এ **"All Files"** select করুন

---

### ধাপ ২: Logo Upload Feature ব্যবহার করুন

**সহজ পদ্ধতি (Recommended):**
1. `index.html` file টি browser এ open করুন (double click)
2. Page এ "🖼️ Logo Select করুন" button এ click করুন
3. আপনার DIU logo image টি select করুন
4. Logo automatically preview তে show হবে
5. এখন আপনার সব information fill করুন
6. "📥 PDF Download" button এ click করে PDF download করুন

**এটাই সবচেয়ে সহজ পদ্ধতি!** কোনো code edit করার দরকার নেই।

---

### ধাপ ৩: (Optional) Manual Logo Replacement

যদি আপনি চান logo permanently replace করতে:

1. আপনার DIU logo টি এই website এ যান: https://www.base64-image.de/
2. আপনার logo image upload করুন
3. "Copy image" তে click করে base64 code copy করুন
4. `index.html` file টি text editor দিয়ে open করুন
5. Line যেখানে লেখা আছে:
```html
   <img id="displayLogo" src="data:image/svg+xml,..." alt="DIU Logo">
```
6. `src="..."` এই part টি replace করুন আপনার copy করা base64 code দিয়ে
7. File টি save করুন (Ctrl+S)

---

## 📦 ZIP File তৈরি করুন:

### Windows এ:
1. `DIU_Cover_Generator` folder এ right click করুন
2. "Send to" → "Compressed (zipped) folder" select করুন
3. Zip file ready!

### Mac এ:
1. `DIU_Cover_Generator` folder এ right click করুন
2. "Compress" select করুন
3. Zip file ready!

---

## ✨ Features:

### ✅ যা যা করতে পারবেন:
- ✔️ **Custom Logo Upload** - আপনার নিজের DIU logo ব্যবহার করুন
- ✔️ **Live Preview** - লিখার সাথে সাথে cover page দেখুন
- ✔️ **PDF Download** - High quality PDF তৈরি করুন
- ✔️ **Direct Print** - সরাসরি print করুন
- ✔️ **Bangla Support** - বাংলা text support
- ✔️ **Professional Design** - University standard maintain করে
- ✔️ **No Internet Required** - Offline কাজ করে (শুধু প্রথমবার internet লাগবে libraries load করার জন্য)

---

## 📝 কিভাবে ব্যবহার করবেন:

1. **index.html** file টি browser এ open করুন
2. যদি logo change করতে চান, "Logo Select করুন" button এ click করে upload করুন
3. সব field fill করুন:
   - Department name
   - Course title & code
   - Assignment/Lab report title
   - আপনার name ও ID
   - Semester & section
   - Teacher এর name & designation
   - Submission date
4. Right side এ live preview দেখুন
5. **"📥 PDF Download"** button এ click করে PDF download করুন
   অথবা
   **"🖨️ Print করুন"** button এ click করে সরাসরি print করুন

---

## 🎨 Color Scheme:
- **Primary Color:** Dark Blue (#0c4a6e)
- **Secondary Color:** Blue (#1e40af)
- **Accent:** Purple gradient
- DIU brand colors maintain করা হয়েছে

---

## 🔧 Troubleshooting:

### সমস্যা: Logo show করছে না
**সমাধান:** 
- Browser refresh করুন (F5)
- Logo file size 2MB এর কম কিনা check করুন
- Image format PNG বা JPG কিনা নিশ্চিত করুন

### সমস্যা: PDF download হচ্ছে না
**সমাধান:**
- Internet connection আছে কিনা check করুন (প্রথমবার library download হবে)
- Pop-up blocker disable করুন
- আবার try করুন

### সমস্যা: Print এ logo আসছে না
**সমাধান:**
- Print settings এ "Background graphics" enable করুন
- "Print backgrounds" option টি check করুন

---

## 📱 Device Compatibility:
- ✅ Desktop/Laptop (Windows, Mac, Linux)
- ✅ Tablet
- ✅ Mobile (responsive design)
- ✅ সব modern browsers (Chrome, Firefox, Edge, Safari)

---

## 🎯 Tips & Tricks:

1. **Best Logo Size:** 500x500 pixels বা তার উপরে
2. **Logo Format:** PNG (transparent background) সবচেয়ে ভালো
3. **Quick Fill:** একবার information fill করলে browser cache এ save থাকবে
4. **Multiple Versions:** Different assignments এর জন্য শুধু title change করে multiple PDF generate করুন
5. **Backup:** ZIP file টি cloud এ save করে রাখুন (Google Drive, Dropbox)

---

## 📞 Support:

কোনো সমস্যা হলে:
1. Browser console check করুন (F12 press করুন)
2. Error message screenshot নিন
3. নতুন browser এ try করুন

---

## 🚀 Future Updates:

Upcoming features:
- [ ] Multiple page support
- [ ] Table of contents generator
- [ ] QR code integration
- [ ] Signature field
- [ ] Multiple template options
- [ ] Dark mode

---

## 📄 License:
Free to use for DIU students

---

## ⭐ Created by:
Modified SUST Cover Page Generator for Daffodil International University

**Version:** 1.0  
**Last Updated:** December 2024

---

## 🎓 আরো Help প্রয়োজন?

এই file এর সাথে `index.html` একসাথে রাখুন এবং যেকোনো সময় reference হিসেবে ব্যবহার করুন।

**Happy Cover Page Creating! 🎉**

---

### Quick Start Summary:
```
1. index.html browser এ open করুন
2. "Logo Select করুন" দিয়ে আপনার logo upload করুন
3. Information fill করুন
4. "PDF Download" এ click করুন
5. Done! ✅
```

এত সহজ! 😊

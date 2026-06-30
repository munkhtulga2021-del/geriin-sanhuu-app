ГЭРИЙН САНХҮҮ — IPHONE / ANDROID PWA
=====================================

Энэ хувилбар нь iPhone, Android дээр тусдаа app шиг суух PWA юм.
App Store хэрэггүй, Apple Developer account хэрэггүй.

1. Vercel дээр байршуулах
-------------------------
A. vercel.com руу орж Login хийнэ.
B. Add New -> Project -> энэ folder-ийг GitHub-д upload хийсэн repo-оосоо сонго.
   Эсвэл Vercel-ийн upload/deploy сонголтоор энэ folder-ийн contents-ийг upload хийнэ.
C. Deploy дараад гарсан https://...vercel.app линкээ авна.

2. iPhone дээр суулгах
----------------------
A. iPhone-ийн Safari-аар өөрийн Vercel линкээ нээ.
B. Share товч дар.
C. Add to Home Screen дар.
D. Нэр нь "Гэрийн санхүү" гарна -> Add дар.

Home Screen дээр тусдаа icon гарна. Тэндээс нээхэд browser-ийн address bar-гүй, апп шиг ажиллана.

3. Android дээр суулгах
-----------------------
Chrome-оор линкээ нээ. Menu дээр "Install app" эсвэл "Add to Home screen" гарвал сонго.

АНХААР:
- Орлого, зарлага, зээлийн бүртгэл тухайн утасны browser/app storage-д хадгалагдана.
- Өөр iPhone, Android, browser руу автоматаар sync хийхгүй.
- Ханш, цаг агаар, шатахууны live мэдээлэл интернеттэй үед шинэчлэгдэнэ.
- Аппын үндсэн дэлгэц өмнө нь нээгдсэн бол сүлжээгүй үед ч ажиллаж чадна.

Хэрэв жинхэнэ App Store-д тавих .ipa хувилбар хэрэгтэй бол Mac + Xcode + Apple Developer account шаардлагатай.

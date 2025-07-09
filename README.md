# Messenger

project/
│
├── main.cpp                ← نقطه شروع
├── managers/
│   ├── UserManager.hpp     ← ورود، ثبت‌نام، لاگین، هش رمز
│   ├── ChatManager.hpp     ← ساخت چت‌روم، دعوت و ترک
│   └── MessageManager.hpp  ← ارسال/ویرایش/ذخیره پیام
│
├── models/
│   ├── User.hpp            ← کلاس اطلاعات کاربر
│   ├── Message.hpp         ← ساختار پیام
│   └── ChatRoom.hpp        ← گروه و اعضا
│
├── data/
│   ├── users.json
│   ├── messages.json
│   └── rooms.json
│
└── ui/
    ├── cli.cpp             ← رابط متنی
    └── gui.cpp             ← اگر خواستی Qt اضافه کن

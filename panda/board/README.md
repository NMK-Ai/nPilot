Dependencies
--------

**ماك**

```
xcode-select --install
./get_sdk_mac.sh
```

**دبيان / يوبينتو**

```
./get_sdk.sh
```


برمجة
----

**الباندا**

```
scons -u -j$(nproc)  # Compile
./flash_h7.sh        # for red panda
./flash.sh           # for other pandas
```

استكشاف الأخطاء وإصلاحها
----

إذا لم تومض الباندا الخاصة بك وتومض بسرعة بمؤشر LED باللون الأخضر ، فاستخدم:
```
./recover_h7.sh  # for red panda
./recover.sh     # for other pandas
```

إعادة برمجة الباندا(https://comma.ai/shop/products/panda-paw) يمكن استخدامها لوضع الباندا في وضع DFU.


[إدخل على الرابط](http://github.com/dsigma/dfu-util.git) لإعادة تنزيل البرنامج

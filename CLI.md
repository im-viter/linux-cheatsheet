## Command Line Interface ##


```bash

for example this commands:
l	# list
ls	# list
ll	# list + long 
ls -l   # list with details
ls -ltrh    # list with long + time modify + reverse order + human readable



101-1 Configure hardware settings

/sys/   # یک فایل سیستم که به ما اطلاعات سخت افزاری سیستم رو میده و گاهی هم میشه تغییر داد
/proc/  # این دستور که در واقع مخفف process هستش ُ اطلاعاتی در مورد سیستم عامل در خودش داره مثل ورژن لینوکس ُ اطلاعات cpu و...
/proc/filesystem    # فایل سیستم هایی که پشتیبانی می کنه رو نشون میده
/proc/cpuinfo   # information about CPU
/proc/version   # show version of your linux
/proc/meminfo   # show your memory system
/dev/   # این دایرکتوری هم مخفف device هست که دیوایس هایی که به سیستم وصل هستن رو میشه چک کنی و یه سری کار های دیگه مثل گرفتن اعداد تصادفی
/dev/urandom    # get random number
/dev/random     # again get random number
/dev/null   # فضای سیاه چاله که توش هرچی بندازی نیست و نابود میشه
/dev/sda    # برسی هارد دیسک حقیقی
/dev/vda    # virtual hard disk
lsmod   # for check modules in your system
modprobe    # remove or load a modules
lsusb   # check your USB devices

101-2 Boot the system

dmesg   # نشون دادن لاگ های کرنل و سخت افزاری که از ring buffer میخونه
ring buffer # یک حافظه موقتی و چرخشی در RAM هستش که پیام ها و لاگ های کرنل رو به صورت موقتی نگهمیداره
journalctl  # لاگ های سیستم رو به صورت جزئی تر نگهداری می کنه همراه با تایم و دیگر لاگ ها مانند کرش و سرویس ها
BIOS/UEFI   # دوتا firmware هستن که یکیش قدیمی تره و یکی دیگه جدیده و الان همه رو اونن 
Bootloader  # firmware که ران شد یک bootloader ران میکنه مثل گراب تا بعدش بره سراغ ران کردن کرنل
Kernel  # کرنل هسته سیستم عامل هستش که کارش واسطه گری بین سخت افزار و نرم افزار هستش و میشه گفت که قلب لینوکسه
sysVinit    # یک اینیت قدیمی هستش که الان دیگه کاربرد آنچنانی نداره
systemd     # اینم یک نوع اینیت هست که باعث میشه در تارگت های مختلف جا به جا بشی و همچنین وظیفه میدریت سرویس های سیستم رو به عهده داره مثل محیط کاربران و Networkmanager
init    # پدر همه پروسه های سیستم هستش و بعد از کرنل اجرا میشه . اجرا کردن cron , network , sshd بخشیاز پروسه هایی است که اینیت ران میکنه  

101-3 change runlevels and boot targets



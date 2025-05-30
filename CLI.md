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


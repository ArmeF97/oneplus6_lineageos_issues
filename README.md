## LineageOS
* 16.0 => XDA Thread: https://forum.xda-developers.com/oneplus-6/development/rom-lineageos-16-0-t3839750

## Instructions
* Download the latest build and gapps
* Boot to recovery
* Flash the latest build
* Boot to recovery again
* Flash gapps
* Reboot

## Downloads - Builds
* https://www.androidfilehost.com/?w=files&flid=282035
* https://sourceforge.net/projects/luk...a/lineage-16.0

## Reporting Bugs

DO NOT Report bugs if you're running a custom kernel or you installed Xposed.

Grab a logcat right after the problem has occurred. (Please include at least a few pages of the log, not just the last few lines, unless you know what you're doing.)

If it is a random reboot, grab /sys/fs/pstore/console-ramoops and /sys/fs/pstore/dmesg-ramoops-0. (Do not bother getting a logcat unless you can get it just before the reboot. A logcat after a reboot is useless)

If the problem disappears after running "setenforce 0" from a root shell, grab /data/misc/audit/audit.log

## Remember to provide as much info as possible. The more info you provide, the more likely that the bug will be solved. Please also do not report known issues. Any bug not reported in the bug report format below may be ignored.

* Submit issues here https://github.com/ArmeF97/oneplus6_lineageos_issues/issues

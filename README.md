Modified veewee definition of CentOS-6.4-minimal.

- Use jp106 keyboard
- Set timezone to Asia/Tokyo
- Use the exact version 6.4 instead of $releasever in /etc/yum.repos.d/*.repo. This ensures the system is built with RPM versions included in CentOS 6.4, and guest additions is properly built.

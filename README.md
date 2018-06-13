# android_sysinit_afterboot
Run scripts after android has boot completely(like sysinit,but sysinit is excuted during boot and it has defects)

On Android third-party Roms like LOS,RR,AICP,there's a service called sysinit which runs user-supplied scripts during the booting process.But it runs too early and some modification done by scripts may be changed by any Android Daemons(or intergrated tweak lines in .rc file)
This mechanism runs scripts after Android has boot.
Note:This mechanism is still based on sysinit!
The repo content is based on android 8.1 but it uses a general way to achieve it.

# b0xx-joycondroid (idea 4 now)

i couldnt get https://github.com/toshinari123/b0xx-joycontrol this working so i have devised a devious scheme

1. use https://play.google.com/store/apps/details?id=com.rdapps.bluetoothhidtester to check if ur android good (it not available in playstore or me tho)
2. if not linux, buy a bluetooth dongle and use virtualbox (usb select bluetooth radio or smth similar)
3. change your Linux device's Bluetooth MAC address to your phone's Bluetooth MAC address (https://joycondroid.gitbook.io/joycondroid/other-guides/joycon-droid-with-non-rooted-phone, research todo on how)
4. use https://github.com/Poohl/joycontrol this in vm / linux to connect to switch
5. open joycondroid and pro controller
6. connect android to pc via usb and run script written in https://github.com/barry-ran/QtScrcpy (said script will convert key combinations to touchscreen touches)
7. looks like qtscrcpy don support key combinations so i just have to write a ahk that press another key once a specific key combination is met

wow very simple and elegant

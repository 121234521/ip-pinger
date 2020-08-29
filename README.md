@echo off
mode con lines=40 cols=60
cls
title Nuclear IP Pinger - Nando - V7
echo [43;37m__________________________________________________
echo _________________________[41;31mI[43;37m________________________
echo ________________________[41;31mIII[43;37m_______________________
echo _______________________[41;31mIIIII[43;37m______________________
echo ______________________[41;31mIIIIIII[43;37m_____________________
echo _____________________[41;31mIIIIIIIII[43;37m____________________
echo ____________________[41;31mIIIIIIIIIII[43;37m___________________
echo ___________________[41;31mIIIIIIIIIIIII[43;37m__________________
echo __________________[41;31mIIIIIIIIIIIIIII[43;37m_________________
echo __________________[41;31mIIIIIIIIIIIIIIII[43;37m________________
echo ____________________[41;31mIIIIIIIIIIIII[43;37m_________________
echo _____________________[41;31mIIIIIIIIIII[43;37m__________________
echo ______________________[41;31mIIIIIIIII[43;37m___________________
echo _______________________[41;31mIIIIII[43;37m_____________________
echo ________________________[41;31mIIIII[43;37m_____________________
echo _________________________[41;31mIII[43;37m______________________
echo __________[41;31mIIIIIIIIIIIIIII[43;37m__[41;31mIIIIIIIIIIIIIIII[43;37m_______
echo _________[41;31mIIIIIIIIIIIIIIII[43;37m__[41;31mIIIIIIIIIIIIIIIII[43;37m______
echo ________[41;31mIIIIIIIIIIIIIIIII[43;37m___[41;31mIIIIIIIIIIIIIIIII[43;37m_____
echo _______[41;31mIIIIIIIIIIIIIIIII[43;37m______[41;31mIIIIIIIIIIIIIIII[43;37m____
echo ______[41;31mIIIIIIIIIIIIIIIII[43;37m________[41;31mIIIIIIIIIIIIIIII[43;37m___
echo _____[41;31mIIIIIIIIIIIIIIIII[43;37m__________[41;31mIIIIIIIIIIIIIIII[43;37m__
echo ___[41;31mIIIIIIIIIIIIIIIIII[43;37m____________[41;31mIIIIIIIIIIIIIIII[43;37m_
echo __[41;31mIIIIIIIIIIIIIIIIII[43;37m______________[41;31mIIIIIIIIIIIIIII[43;37m_
echo __________________________________________________
echo.
echo [40;37m        [41;37mNUKE THE IP / MADE BY NANDO[40;37m
echo.
set /p IP=[40;30m [40;37mWHICH [40;33mIP ADDRESS[40;37m IS BEING [40;31mBOMBED[40;37m: 
echo.
:main
PING -n 1 %IP% | FIND "TTL=">nul
IF ERRORLEVEL 1 goto fail
IF NOT ERRORLEVEL 1 goto soon
:soon
echo [40;34m/-/-/[40;37m  [41;37m%IP%[40;30m [40;37mIS [42;37mONLINE[40;30m [40;35m-+- [40;36mNUKE IN AIR [40;34m/-/-/[40;37m
echo.
goto main
:fail
echo [40;34m/-/-/[40;37m  [41;33m%IP%[40;31m IS OFFLINE [40;36m-+- [40;33mTHE BOMB DROPPED [40;34m/-/-/[40;37m
echo.
goto main

@echo off
title Made by Nando -- IP Pinger (TV Edition) - V1
mode con cols=77 lines=25
rem I didn't do the tv design. i just made from it ip pinger
cls
color f
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m          
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[47m                       [40m          Welcome User         [47m                       
echo.[43m                             [41m                   [43m                             
ping localhost -n 2 >nul
cls
color f
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[47m                       [40m     Made by Nando     [47m                       
echo.[43m                             [41m                   [43m                             
ping localhost -n 2 >nul
cls
color f
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[47m           [43m           [46m           [42m           [45m           [41m           [44m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[44m           [40m           [45m           [43m           [46m           [40m           [47m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[41m              [47m             [44m             [47m               [46m           [42m           
echo.[47m                       [40m   Press any key to Continue   [47m                       
echo.[43m                             [41m                   [43m                             
pause >nul
color 6
cls     
echo                                         o
echo                                o       /
echo                                 \     /
echo                                  \   /
echo                                   \ /
echo                     +--------------v-------------+
echo                     !  __________________      @ !
echo                     ! /           ,  ooo  \      !
echo                     ! !  ---=====!#O#### !  (\)  !
echo                     ! !          `  \ )  !       !
echo                     ! !   ,;`,      ! !  !  (-)  !
echo                     ! !  // o ',    ! !  !       !
echo                     ! \  ' o \ /,   ! !  / :!!!: !
echo                     !  -ooo--------------  :!!!: !
echo                     +----------------------------+
echo                       []                    []
echo.
set /p IP=Enter URL/IP: 
title Made by RavelCros_Cro -- Pinging from: %IP%
echo.
:iploop
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
color 02
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 03
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 04
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
color 05
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 06
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 07
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 08
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 09
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
color 0a
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
color 0b
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 0c
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...) 
ping localhost -n 2 >nul
color 0d
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
color 0e
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
color 0f
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping localhost -n 2 >nul
goto iploop








@echo off
color 08
title (MADE BY @NANDO)
cls
echo               ...
echo             ;::::;
echo           ;::::; :;
echo         ;:::::'   :;
echo        ;:::::;     ;.
echo       ,:::::'       ;           OOO\
echo       ::::::;       ;          OOOOO\
echo       ;:::::;       ;         OOOOOOOO
echo      ,;::::::;     ;'         / OOOOOOO
echo    ;:::::::::`. ,,,;.        /  / DOOOOOO
echo  .';:::::::::::::::::;,     /  /     DOOOO
echo ,::::::;::::::;;;;::::;,   /  /        DOOO
echo;`::::::`'::::::;;;::::: ,#/  /          DOOO
echo:`:::::::`;::::::;;::: ;::#  /            DOOO
echo::`:::::::`;:::::::: ;::::# /              DOO
echo :`:::::::`;:::::: ;::::::#/               DOO
echo :::`:::::::`;; ;:::::::::##                OO
echo ::::`:::::::`;::::::::;:::#                OO
echo `:::::`::::::::::::;'`:;::#                O
echo  `:::::`::::::::;' /  / `:#
echo   ::::::`:::::;'  /  /   `#    BY NANDO
echo ----------------------------------------------
@echo off 
color 10
:reboot
echo off
color 08
set /p IP=ENTER IP:
:top
PING  -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 echo ungv SLAMED %IP% 
color 08
ping -t 2 0 1 127.0.0.1 >nul
color 03
ping -t 2 0 1 127.0.0.1 >nul
color 07
ping -t 2 0 1 127.0.0.1 >nul
color 02
ping -t 2 0 1 127.0.0.1 >nul
color 03
ping -t 2 0 1 127.0.0.1 >nul
color 07 
ping -t 2 0 1 127.0.0.1 >nul
color 02
GoTo top


@echo off
Title IP Pinger - PC Edition - Made by Nando - V5
mode con lines=30 cols=80
color 8
cls
echo [40;36m             ____________________________________________________
echo             /                                                    \
echo            !    _____________________________________________     !
echo            !   !                                             !    !
echo            !   !                  [40;37mEnter IP[40;36m                   !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !  [40;37mInput Type: IP or URL[40;36m                      !    !
echo            !   !                                             !    !
echo            !   !  [40;37mStatus: Waiting For Input . . .[40;36m            !    !
echo            !   !                                             !    !
echo            !   !  [40;37mMessage: Please Enter Valid Input Below[40;36m    !    !
echo            !   !           [40;37mTo Start Ping[40;36m                     !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !_____________________________________________!    !
echo            !                                                      !
echo            !      [40;31m=====     [40;32mMade by Nando     [40;36m[40;31m=====[40;36m       !
echo            \_____________________________________________________/
echo                    \_______________________________________/
echo                 _______________________________________________
echo              _-'    .-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.  --- `-_
echo           _-'.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.--.  .-.-.`-_
echo        _-'.-.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-`__`. .-.-.-.`-_
echo     _-'.-.-.-.-. .-----.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-----. .-.-.-.-.`-_
echo  _-'.-.-.-.-.-. .---.-. .-----------------------------. .-.---. .---.-.-.-.`-_
echo :-----------------------------------------------------------------------------:
echo `---._.-----------------------------------------------------------------._.---'
echo.
set /p IP=IP or URL: 
:rep
PING -n 1 %IP% | FIND "TTL=">nul
IF ERRORLEVEL 1 goto off
IF NOT ERRORLEVEL 1 goto on
:on
set /a ran=(%Random%%%9)+1
color %ran%
cls
Title -==== Pinging form %IP% ====-
echo              ____________________________________________________
echo             /                                                    \
echo            !    _____________________________________________     !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !       ___  _   _ _     ___ _   _ _____      !    !
echo            !   !      / _ \! \ ! ! !   !_ _! \ ! ! ____!     !    !
echo            !   !     ! ! ! !  \! ! !    ! !!  \! !  _!       !    !
echo            !   !     ! !_! ! !\  ! !___ ! !! !\  ! !___      !    !
echo            !   !      \___/!_! \_!_____!___!_! \_!_____!     !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !_____________________________________________!    !
echo            !                                                      !
echo            !      =====     Made by Nando     =====       !
echo            \_____________________________________________________/
echo                    \_______________________________________/
echo                 _______________________________________________
echo              _-'    .-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.  --- `-_
echo           _-'.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.--.  .-.-.`-_
echo        _-'.-.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-`__`. .-.-.-.`-_
echo     _-'.-.-.-.-. .-----.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-----. .-.-.-.-.`-_
echo  _-'.-.-.-.-.-. .---.-. .-----------------------------. .-.---. .---.-.-.-.`-_
echo :-----------------------------------------------------------------------------:
echo `---._.-----------------------------------------------------------------._.---'
goto rep
:off
set /a ran=(%Random%%%9)+1
color %ran%
cls
Title -==== Pinging form %IP% ====-
echo              ____________________________________________________
echo             /                                                    \
echo            !    _____________________________________________     !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !    ___  _____ _____ _     ___ _   _ _____   !    !
echo            !   !   / _ \!  ___!  ___! !   !_ _! \ ! ! ____!  !    !
echo            !   !  ! ! ! ! !_  ! !_  ! !    ! !!  \! !  _!    !    !
echo            !   !  ! !_! !  _! !  _! ! !___ ! !! !\  ! !___   !    !
echo            !   !   \___/! !   ! !   !_____!___!_! \_!_____!  !    !
echo            !   !        !_!   !_!                            !    !
echo            !   !                                             !    !
echo            !   !                                             !    !
echo            !   !_____________________________________________!    !
echo            !                                                      !
echo            !      =====     Made by Nando    =====       !
echo            \_____________________________________________________/
echo                    \_______________________________________/
echo                 _______________________________________________
echo              _-'    .-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.  --- `-_
echo           _-'.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.--.  .-.-.`-_
echo        _-'.-.-.-. .---.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-`__`. .-.-.-.`-_
echo     _-'.-.-.-.-. .-----.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-.-----. .-.-.-.-.`-_
echo  _-'.-.-.-.-.-. .---.-. .-----------------------------. .-.---. .---.-.-.-.`-_
echo :-----------------------------------------------------------------------------:
echo `---._.-----------------------------------------------------------------._.---'
goto rep
title IP Rainbow Pinger - Nando - V2
echo off & cls
color E
mode con lines=20 cols=70
echo ooooo      ooo       .o.       ooooo      ooo oooooooooo.     .oooooo.   
echo `888b.     `8'      .888.      `888b.     `8' `888'   `Y8b   d8P'  `Y8b  
echo  8 `88b.    8      .8"888.      8 `88b.    8   888      888 888      888 
echo  8   `88b.  8     .8' `888.     8   `88b.  8   888      888 888      888 
echo  8     `88b.8    .88ooo8888.    8     `88b.8   888      888 888      888 
echo  8       `888   .8'     `888.   8       `888   888     d88' `88b    d88' 
echo o8o        `8  o88o     o8888o o8o        `8  o888bood8P'    `Y8bood8P' 
echo.                                                                                             
set /p IP=Enter IP:
echo.
:rainbow
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
color 01
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
color 02
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 03
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 04
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
color 05
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 06
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 07
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 08
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 09
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
color 0b
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 0c
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...) 
ping -t 2 0 10 127.0.0.1 >nul
color 0d
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
color 0e
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
color 0f
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo Skid %IP% IS OFFLINE...)
ping -t 2 0 10 127.0.0.1 >nul
goto rainbow

@echo off
color 3
title nando
echo ooooo      ooo       .o.       ooooo      ooo oooooooooo.     .oooooo.   
echo `888b.     `8'      .888.      `888b.     `8' `888'   `Y8b   d8P'  `Y8b  
echo 8 `88b.    8      .8"888.      8 `88b.    8   888      888 888      888 
echo 8   `88b.  8     .8' `888.     8   `88b.  8   888      888 888      888 
echo 8     `88b.8    .88ooo8888.    8     `88b.8   888      888 888      888 
echo 8       `888   .8'     `888.   8       `888   888     d88' `88b    d88' 
echo 8        `8  o88o     o8888o o8o        `8  o888bood8P'    `Y8bood8P' 
set /p IP=Enter IP to Ping:
:top
PING - 1 %IP% | FIND "TTL="
title : : Pinging: %IP% : :
IF ERRORLEVEL 1 (Echo IP DOWNED BY NANDO)
Set /a num=(%Random%%%9)+1
color %num%
ping -t 1 0 10 127.0.0.1 >nul
GoTo top

title IP Pinger V3 - Nando
echo off
cls
color 0b
mode con lines=24 cols=82                                                                                          
@echo off
set /p IP=[40;36mBy nando :) enter ip:~#[40;31m 
echo.
echo [40;33mNando is smacking %IP%![40;37m
:main
echo. [40;32m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo [41;37mRequest timed out.[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo. [40;33m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo [41;37mRequest timed out.[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo. [40;34m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo [41;37mRequest timed out.[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo. [40;35m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo [41;37mRequest timed out.[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo. [40;36m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo [41;37mRequest timed out.[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo. [40;37m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo [41;37mRequest timed out.[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
goto main

@echo off
title Fuck Up All The SKID's
mode 73,20
color 4  

echo _///     _//      _/       _///     _//_/////        _////     
echo _/ _//   _//     _/ //     _/ _//   _//_//   _//   _//    _//  
echo _// _//  _//    _/  _//    _// _//  _//_//    _//_//        _//
echo _//  _// _//   _//   _//   _//  _// _//_//    _//_//        _//
echo _//   _/ _//  _////// _//  _//   _/ _//_//    _//_//        _//
echo _//    _/ // _//       _// _//    _/ //_//   _//   _//     _// 
echo _//      _//_//         _//_//      _//_/////        _////     

set /p IP=Enter Whos About to Get Hit IP:
:rainbow
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul

color a
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
color 02
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 03
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 04
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
color 05
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 06
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 07
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 08
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 09
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
color 0a
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
color 0b
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 0c
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...) 
ping -t 2 0 10 127.0.0.1 >nul
color 0d
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
color 0e
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
color 0f
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=c & echo offline...)
ping -t 2 0 10 127.0.0.1 >nul
goto rainbow
title IP Pinger V4 - Nando
echo off
cls
mode con lines=26 cols=70
echo [40;32m
echo                       .
echo                       00
echo                       000
echo                      00000                  .
echo                      000000                00
echo       .             0000000              0000
echo       0000          0000000            00000
echo       00000         00000000          000000
echo        000000       00000000        0000000
echo         0000000     00000000      000000000
echo         0000000      0000000     000000000
echo          0000000     00000000   000000000
echo           000000000  0000000   00000000
echo             0000000   000000  0000000            .
echo               000000  00000  0000000        000000
echo    .           000000  0000  000000    000000000
echo     0000000     000000 000   0000   00000000000
echo      0000000000   0000  00  0000  00000000000
echo        00000000000  000 00 000  0000000000
echo           00000000000 00 0 0  000000000
echo              00000000000000 0000
echo                       000000000
echo                     000     000000
echo.                                                                                         
set /p IP=[40;37mWhich Enter IP to ping: 
:v6
echo [47;30m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (echo [41;37m-------------------------- %IP% IS HIGH --------------------[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo [42;37m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (echo [41;37m-------------------------- %IP% IS HIGH --------------------[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo [43;37m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (echo [41;37m-------------------------- %IP% IS HIGH --------------------[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo [44;37m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (echo [41;37m-------------------------- %IP% IS HIGH --------------------[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo [45;37m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (echo [41;37m-------------------------- %IP% IS HIGH --------------------[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
echo [46;37m
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (echo [41;37m-------------------------- %IP% IS HIGH --------------------[40;37m)
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
ping localhost -n 1 >nul
goto v6

@echo off
title IP Logs - V4  // User: %USERNAME%  //  Time: %TIME%  //  Date: %DATE%
mode con lines=24 cols=78
:reset
cls
set /a color=(%Random%%%7)+1
echo [40;3%color%m
echo.
echo         8888888               888                                
echo           888                 888                                
echo           888                 888                                
echo           888   88888b.       888      .d88b.   .d88b.  .d8888b  
echo           888   888 "88b      888     d88""88b d88P"88b 88K      
echo           888   888  888      888     888  888 888  888 "Y8888b. 
echo           888   888 d88P      888     Y88..88P Y88b 888      X88 
echo         8888888 88888P"       88888888 "Y88P"   "Y88888  88888P' 
echo                 888                                 888          
echo                 888                            Y8b d88P          
echo                 888                             "Y88P"   
echo.
echo       [40;37m^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>^>[40;30m
echo       [40;37m^<^>[40;33m Press 1 to open IP Logs Database [40;37m~[40;33m Made by Nando [40;37m^<^>
echo       [40;37m^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<^<[40;30m
echo.[40;37m
set /p name=[40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;36mPRESS 1 OR ENTER TARGET NAME:[40;31m 
echo.
if %name% == 1 goto open
set /p IP=[40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;36mENTER %name%'s IP:[40;31m 
echo -  %name%  //  %IP%  -  %date% %time%>> IPLogs.txt
echo.
echo [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;37m[40;37m{+}- [40;33m%name%'s Info Saved in Your Database [40;37m-{+}
echo [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;30m [40;37m[40;37m{+}- [40;33mPress Any Key to Restart IP Logs [40;37m-{+}
pause >nul
goto reset
:open
cls
start IPLogs.txt
goto reset


@echo off
mode con lines=30 cols=70
color 02
cls
title IP Pinger - Nando - V6
echo.
echo   [40;37m          /-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-\
echo             +                                       +
echo             +             [40;36mIP Pinger V6[40;37m              +
echo             +                                       +
echo             +        [40;33mMade by Nando[40;37m          +
echo             +                                       +
echo             \-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-+-/
echo.
echo.
set /p IP=[40;30m [40;31mDrown the IP Address:[40;35m 
echo.
:cros
PING -n 1 %IP% | FIND "TTL=">nul
IF ERRORLEVEL 1 goto sub
IF NOT ERRORLEVEL 1 goto rcc
:sub
echo  [40;31m[[40;32m%USERNAME%[40;31m] [40;37m([41;37m%IP%[40;37m) IS [40;33mOFFLINE  [40;37m::  [40;31mDROWNED 
echo.
goto cros
:rcc
echo  [40;32m[%USERNAME%] [40;37m([40;36m%IP%[40;37m) IS [40;32mONLINE  [40;37m::  [40;34mWAITING 
echo.
goto cros
@echo off
color 4

title Made by Nando :)

:greeting
cls

echo ooo      ooo       .o.       ooooo      ooo oooooooooo.     .oooooo.   
echo `888b.     `8'      .888.      `888b.     `8' `888'   `Y8b   d8P'  `Y8b  
echo 8 `88b.    8      .8"888.      8 `88b.    8   888      888 888      888 
echo 8   `88b.  8     .8' `888.     8   `88b.  8   888      888 888      888 
echo 8     `88b.8    .88ooo8888.    8     `88b.8   888      888 888      888 
echo 8       `888   .8'     `888.   8       `888   888     d88' `88b    d88' 
echo 8o        `8  o88o     o8888o o8o        `8  o888bood8P'    `Y8bood8P' 


set /p IP=IP: :
:top
PING -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 (SET in=0b & echo Slammed.) 
color %in%
ping -t 2 0 10 127.0.0.1 >nul
GoTo top 
@echo off
color 3
title nando
echo ooooo      ooo       .o.       ooooo      ooo oooooooooo.     .oooooo.   
echo `888b.     `8'      .888.      `888b.     `8' `888'   `Y8b   d8P'  `Y8b  
echo 8 `88b.    8      .8"888.      8 `88b.    8   888      888 888      888 
echo 8   `88b.  8     .8' `888.     8   `88b.  8   888      888 888      888 
echo 8     `88b.8    .88ooo8888.    8     `88b.8   888      888 888      888 
echo 8       `888   .8'     `888.   8       `888   888     d88' `88b    d88' 
echo 8        `8  o88o     o8888o o8o        `8  o888bood8P'    `Y8bood8P' 
set /p IP=Enter IP to Ping:
:top
PING - 1 %IP% | FIND "TTL="
title : : Pinging: %IP% : :
IF ERRORLEVEL 1 (Echo IP DOWNED BY NANDO)
Set /a num=(%Random%%%9)+1
color %num%
ping -t 1 0 10 127.0.0.1 >nul
GoTo top

title ::Xbox GT: @Nando::
echo off & cls
color c                                   
echo                `.:+sshdmmmdhy+:.`                
echo             `-ossshs+oymmmmmdddss+:`             
echo           `:+s+hdhoyhdhdmmdsyyysssss+.           
echo         `-:://+ddddddddmdhdhshssssssss+`         
echo        .::+oyyhdddddddddhyso+ooooyhyyhss.        
echo       :/ohddddddddddddddhho+sssysyhyssyss-       
echo      `hhddddddddddddddddo:+ddhdhddhdhssyyy`      
echo      /yddhhhhhhhhhddddddy+o//+oyhyyysyssyhs      
echo      yhhhhhhhhhyhhhhhdds::/://++++oosshsshm      
echo      yshhhhhyyysyyyhhy/::::/:/++++ooosshydN      
echo      o.:yhhyyssossyyys--::::////+++ooossshm      
echo      :..-ohyyssoossyyo:::::////++++ooossyms      
echo      `.``.shyyssssyyhhy/::::++//+++ooossmm.      
echo       .-``.-+syyyyyhhhddhhdddddo+++++sshd:       
echo        ..````.:hhhhhhddddddddddh++ooosyy-        
echo         `..``.shhhdddddddddddddd++ooshs`         
echo           `.:ohddddddddddddddddy+ooys-           
echo             `+sdddddddddddddddmdso/`             
echo                `:/oyhddddddhyo+-`     
echo ============================== 
echo Made by Nando :D
echo ==============================
set /p IP=Enter IP:
:top
PING -n 1 %IP% | FIND "TTL="
title ::Made By GT:@Nando:: ~Pinging:%IP%~                
IF ERRORLEVEL 1 (SET in=0a & echo Off.....) ELSE (SET in=0e)
color %in%
ping -t 2 0 10 127.0.0.1 >nul
GoTo top
@echo off
color 0c
title (Von nando)
echo off & cls
color 5
type Dontopen.py
echo.
ping localhost >nul
color 02
set /p IP=[+]-SKIDS IP:
echo @nando IS ON TOP%Ip%
echo ===========================================
:top
PING  -n 1 %IP% | FIND "TTL="
IF ERRORLEVEL 1 echo %IP% Your IP has been hit Offline By @Nando
color 01
ping -t 2 0 1 127.0.0.1 >nul
color 02
ping -t 2 0 1 127.0.0.1 >nul
color 03
ping -t 2 0 1 127.0.0.1 >nul
color 04
ping -t 2 0 1 127.0.0.1 >nul
color 05
ping -t 2 0 1 127.0.0.1 >nul
color 06 
ping -t 2 0 1 127.0.0.1 >nul
color 07
ping -t 2 0 1 127.0.0.1 >nul
color 08
ping -t 2 0 1 127.0.0.1 >nul
color 09
ping -t 2 0 1 127.0.0.1 >nul
color 0A 
ping -t 2 0 1 127.0.0.1 >nul
color 0B
ping -t 2 0 1 127.0.0.1 >nul
color 0C
ping -t 2 0 1 127.0.0.1 >nul
color 0D
ping -t 2 0 1 127.0.0.1 >nul
color 0F
ping -t 2 0 1 127.0.0.1 >nul
GoTo top


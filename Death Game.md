Batch-Scripts
=============

Death Game 


;This is a simple short MS-DOS prompt, game !
;You have 10 sec until the Death Skull will be  completed. 
;After 10 sec a spcific Folder will be created on your Desktop whos not
;enable to delete without specific commands in prompt "cmd".
;#
;#
;We will Create 2 batch files.
;First one who contains the time count. "<File>.bat
;Second one will be the answer and request file. "Question.bat"
;Please dont judge.. You can easy spin this further by your self to
;a really incredible game. Enjoy



@echo off
cd %HOMEPATH%
title Blue Flame Terminal
color 0a
mode con cols=50 lines=15
cls
goto 45673546fy45vby5

:45673546fy45vby5
echo off
cls
echo    #############################################
echo    #                 Greetings                 #
echo              %date% - %time%             
echo    #                                           #
echo    # Let's play a game..  you have 10 seconds  #
echo    # to answer the question, if you fail..     #
echo    # A specific Folder who contains a deadly   #
echo    # virus for your personal computer will     #
echo    # execute and destroy all stored data       #
echo    # information.                              #
echo    # Let the game begin...                     #
echo    #############################################
pause
start Question.bat
goto v456y345fyw4

:v456y345fyw4
mode con cols=100 lines=40
color 0c
set load=%load%++
cls
echo.
echo                                                                               -/oo+-        
echo                .%load%dy:                                                    /%load%MMNy       
echo             `y%load%MMMh.                                                  oM%load%M%load%N`      
echo               %load%M%load%M                                                 :MM%load%MMMMM      
echo                MMMMMsoMM.                                                sMs:MMMMMM     
echo          `h%load%MM%load%mM-                                                %load%%load%%load%   
echo          h%load%%load%%load%sdf                                              .smh- sM%load%NMMN    
echo          %load%ffdh%load%yds-                                            `%load%Nms%load%M%load%y    
echo          `sNMM%load%MN%load%hmh:`                `````````` `          sdd%load%MNo%load%dy/`    
echo            .:%load%/y%load%Mm%load%o`            `::::-::::::-:  ``      .m%load%Ns.  ````       
echo                    .sN%load%NhmN.       ``.-..:::::::::::-```::``    `NMMNh-               
echo                      .om%load%MNN`      .::::.`.-::--::-...::::--::`   mMd:                 
echo                        .o%load%m     :--:::::---::--::--:--:::--:::.  o/`                  
echo                          .omMy    -:.```  ```::::::::::::-`````` `-.                     
echo                                 --: `       `-::::::::::-`        `-.                    
echo                               `-:`          `-::::::::.           `:-                   
echo                                `:-            `--:::::.            `::                   
echo                                `--..`````````.--:.-..--.`..```````..::                   
echo                                 `.::::::::::::::` . `.--::::::::::-..`                   
echo                                   `-.......---:.  .   .----........                      
echo                                            `:::```.```.:::`                              
echo                                            `:::::::::::::::                              
echo                                            .:::::::::::::::                              
echo                                           `::-:::-:::::--::                              
echo                                 `....`    .:-  ::` .:.  `::   -yy-                       
echo                               `+m%load%do`  .:-  :-`  .:. `-:  `NMMNs-                     
echo                              %load%dM%load%My  .:-  ::`  -.  `::  .MM%load%Ns-                   
echo                           `:%load%No%load%s.  `:-  ::`   `  `::  `%load%M%load%.                 
echo                          -hM%load%MNdMNh-     ``  ``    '   ``   /%load%MMMMNy%load%fys-`       
echo                       `:h%load%ysmMNy-                            :ydmM%load%MMM%load%M%load%      
echo                 `-/+o%load%M%load%%load%o.                                -%load%NhMMM%load%MMM   
echo                `dMM%load%MMMMN/o/-                                     .+s+yhMM%load%MMMM-     
echo                :M%load%mMM%load%d`.                                      `yo%load%%load%M      
echo                `m%load%`d%load%MooN-                                     +MmM%load%y`       
echo                  .`   :M%load%MMMN.                                     /MM%load%MM.          
echo                       hM%load%ms.                                      `dM%load%MMd          
echo                      `/+/:.                                           g%load%Mmy          
echo.
ping localhost -n 10 >nul
set/a loadnum=%loadnum% +1
if %loadnum%==2 goto 9573
goto v456y345fyw4

:9573
mode con cols=50 lines=15
echo.
echo.
echo.
echo.
echo         The Time has end...
echo.
echo.
echo.
pause
cd desktop
md con\
md lpt1\
exit



;#
;#
;#
;Now lets Create a Batch file who contains the Question and Answer.
;You have to save it as "Question.bat" or edit the script above here by your self.


@echo off
cd %HOMEPATH%
title Blue Flame Terminal
color 0a
mode con cols=50 lines=15
cls
goto 45673546fy45vby5

:45673546fy45vby5
echo off
cls
echo    #############################################
echo    #                 Greetings                 #
echo              %date% - %time%             
echo    #                                           #
echo    # Who created this Game?                    #
echo    #                                           #
echo    # 1. Dj Saitto                              #
echo    # 2. Echo St@r                              #
echo    # 3. Bill Gates                             #
echo    # 4. Iron Man                               #
echo    #                                           #
echo    #############################################
pause
set /p stepp= Answer: 
if %stepp%==1 goto 34b6456
if %stepp%==2 goto 45673546fy45vby5
if %stepp%==3 goto 45673546fy45vby5
if %stepp%==4 goto 45673546fy45vby5
goto 45673546fy45vby5

:34b6456
echo.
echo Correct!
echo.
pause
cd %HOMEPATH%
cd Desktop
rd con\
exit


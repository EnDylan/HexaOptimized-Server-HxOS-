# HexaOptimized-Server-HxOS-
A great application for server owners who want to smoother experience or wanting to get the most out of their Minecraft Server. 

#How-does-it-work?-
The application is coded in Windows cmd Syntax and then compiled as an .exe file.
Pratically it works like this:

Windows (handles exe files) -> Kernel (HexagonOS/HxOS) -> Code (Win cmd syntax) -> HIDDEN Code -> User.

###Windows:
You operating system handles and allocates the ammount of RAM needed to run the application.

###Kernel:
Base code. Technically all the important stuff that you dont have to know. The kernel allows input & output from the user.

###Code:
Command from kernel activates the code and transfer the "activity" to it. The code then starts initialising the server's core files and making sure none of them are missing. Afterwards the "activity" is then transfered over to the Server Starter to start the server.

###HIDDEN Code:
Just the extra code added by the exe compiler. Not used for any functions.

#Copyright:
 * Copyright (C) HexagonMC Networks Systems - All Rights Reserved
 * Unauthorized copying of this file, via any medium is strictly prohibited
 * Proprietary and confidential
 * Written by Dylan Kok <dylankjy@yahoo.co.jp>, August 2016
 *

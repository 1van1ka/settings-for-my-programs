To install gcc or clang packages you need to download msys2 from the installer `MSYS.cmd`. Next are commands in the packages file `packages.txt`. Open `msys2 msys` to insert commands in `packages.txt`.
Add the path of your MinGW-w64 bin folder to the Windows PATH environment variable by using the following steps:
1. In the Windows search bar, type Settings to open your Windows Settings.
2. Search for Edit environment variables for your account.
3. In your User variables, select the Path variable and then select Edit.
4. Select New and add the MinGW-w64 destination folder you recorded during the installation process to the list. If you used the default settings above, then this will be the path: `C:\msys64\mingw64\bin\`.
5. Select OK, and then select OK again in the Environment Variables window to update the PATH environment variable. You have to reopen any console windows for the updated PATH environment variable to be available.

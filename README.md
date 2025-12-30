# Nteg.Studio
Scripting-first video editor primarily written in the Rust Programming Language.


Coming soon. Created on December 29, 2025.


Building instructions are currently Windows-only.

You also need Git.

Here are the commands to be able to use rust-ffmpeg.

git clone https://github.com/microsoft/vcpkg.git
cd vcpkg
.\bootstrap-vcpkg.bat
.\vcpkg install ffmpeg[avcodec,avformat]:x64-windows
.\vcpkg integrate install

After all of the commands are complete, go to the search bar, type "Environment" and  "Edit the system environment variables" should appear, launch it.
Click "Environment Variables..." and click one of the two buttons saying "New"
Set the variable name to "VCPKG_ROOT" and set the variable value to your vcpkg's folder's location, you can check by looking at the left of your terminal.
If the only time you used the cd command was the second command, then the path would be something like:

C:\Users\YOURUSERNAME\vcpkg

Press OK on the pop-up window when you are done, then OK on the Environment Variables window.

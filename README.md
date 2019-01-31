# Git archive of 7-zip releases

Because 7-zip [doesn't](https://github.com/7z) have a public repository, and their code is released only as archives on SourceForge, I maintain a git-ified copy here.

The [tagged releases](https://github.com/pornel/7z/releases) and the [original branch](https://github.com/pornel/7z/tree/original) contain pure 7-zip releases, without any modifications like this readme.


# Compiling 7-zip with Visual Studio
  ```
  start with "VS2015 x86 Native Tools Command Prompt" / "VS2015 x64 Native Tools Command Prompt"
  cd CPP\7zip\UI\FileManager
  nmake 
  ```
# Prebuild 7zFM.exe which fix 7zFM diff folder of 7zip file
  use prebuild 7zFm.exe[[x86]](https://github.com/bin601/7z/blob/master/CPP/7zip/UI/FileManager/o/7zFM.exe) to overwrite C:\Program Files (x86)\7-Zip\7zFM.exe
  
  use prebuild 7zFm.exe[[x64]](https://github.com/bin601/7z/blob/master/CPP/7zip/UI/FileManager/x64/7zFM.exe) to overwrite C:\Program Files\7-Zip\7zFM.exe
  
# Update BeyondCompare3 for 7zip diff
  
  extract 7z920_extra.7z to get 7zxa.dll, and then overwrite 7zxa.dll to C:\Program Files (x86)\Beyond Compare 3\7zxa.dll


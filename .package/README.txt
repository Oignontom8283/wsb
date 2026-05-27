
Wallpaper Setter Bypass


USAGE (GUI):

1. Unzip this package to a desired location on your computer.
2. Double-click the "launcher.bat" file to run the program.
3. GUI will appear.
4. Select an image file from your computer.
5. Choose your wallpaper applying options.
6. Click the "Apply" button to set the selected image as your wallpaper.
7. Congratulations! Your wallpaper has been successfully changed.

USAGE (Command Line):
1. Open Command Prompt or PowerShell.
2. Navigate to the directory where you unzipped the package using the "cd" command.
3. Run the following command:
   powershell -NoProfile -ExecutionPolicy Bypass -File "wallpaper_setter.ps1" -Path "C:\path\to\image.jpg" [Options]
4. Available options:
   -ScaleUp          : Scale up small images to screen resolution
   -Stretch          : Stretch image to fill screen
   -CloseAfter       : Close after applying wallpaper
   -UseRegistryMethod: Use registry method instead of native API
   -Help             : Display help message
5. Congratulations! Your wallpaper has been successfully changed.


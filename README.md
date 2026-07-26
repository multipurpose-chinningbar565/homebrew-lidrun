# 💻 homebrew-lidrun - Keep Mac jobs running while closed

[![](https://img.shields.io/badge/Download-LidRun-blue.svg)](https://github.com/multipurpose-chinningbar565/homebrew-lidrun/releases)

## What is LidRun?

LidRun manages your Mac computer while the lid stays closed. Usually, a Mac goes to sleep when you shut the lid. This stops your work, ends your network tasks, and pauses your background processes. LidRun prevents this sleep mode. It keeps your computer awake so your programs continue to run. You can process heavy data, run artificial intelligence agents, or maintain long development tasks without concern. 

The software monitors your battery levels and internal temperatures. It pauses its work if the computer gets too hot. This protects your hardware from heat damage. It also prevents your battery from draining when you are away from a power source.

## 🛠️ System Requirements

- A Mac computer running macOS Monterey or later.
- An active internet connection for the initial download.
- Sufficient disk space for the small application footprint.
- A power adapter if you plan to run tasks for several hours.

## 📥 How to Install

Follow these steps to set up LidRun on your machine:

1. Visit the [releases page](https://github.com/multipurpose-chinningbar565/homebrew-lidrun/releases) to view current versions.
2. Look for the latest release at the top of the list.
3. Click the link that matches your system architecture.
4. Open the downloaded file once the transfer completes.
5. Move the application into your Applications folder.

After you move the file, open the app from your Applications folder or use Spotlight search. You will see a small icon appear in your menu bar at the top of your screen.

## ⚙️ Using the App

The app interface lives in your top menu bar. Click the icon to see the control panel. 

- **Enable Keep Awake:** Check this box to prevent your Mac from sleeping when the lid shuts.
- **Thermal Guard:** Keep this enabled to ensure the app watches your system temperature. The app will deactivate if your system hits a danger zone to prevent overheating.
- **Battery Guard:** This feature stops the app from running if your battery drops below 20 percent. This ensures your computer remains ready for mobile use when you return.

## 🛡️ Safety and Protection

We built this tool with safety in mind. Running a Mac with the lid closed requires careful management of heat. The app follows strict logic to monitor these conditions:

1. **CPU Throttling:** If the processor reaches a temperature limit, the app will stop forcing the system awake. This allows the system to sleep and cool down.
2. **Battery Health:** Keeping a system running on battery with the lid closed can cause high discharge rates. The app prioritizes power safety by shutting down operations when the battery runs thin.
3. **Emergency Exit:** If the system fan reaches maximum speed, the app will exit automatically to prevent hardware strain.

## 📋 Frequently Asked Questions

**Does this work with external monitors?**
Yes. Use this app if you want to use an external keyboard and mouse with your Mac while the display remains closed.

**Will this damage my Mac?**
Computers manage heat well with internal sensors. By monitoring these sensor values, LidRun prevents conditions that lead to hardware stress.

**Do I need to leave my charger plugged in?**
It is better to keep your charger plugged in during long tasks. This prevents the app from pausing due to low battery settings.

**Can I stop the app at any time?**
Yes. Click the menu bar icon and select Quit. Your Mac will then return to its normal sleep behavior.

## 🧩 Troubleshooting

If the computer goes to sleep while the app is active, check these items:

1. **Permissions:** Ensure the app has permission to control your system. Check System Settings under Privacy and Security.
2. **Display Settings:** Open your Mac system settings and make sure no other conflicting "sleep" timers exist.
3. **App Version:** Always ensure you use the version linked on the official release page. Old versions may contain bugs or missing safety updates.
4. **Restart:** If the menu bar icon disappears or freezes, simply quit the app and relaunch it from the Applications folder.

## 🚀 Maintaining Performance

LidRun operates with minimal impact on your system resources. It uses very little memory and almost no processor time. Most of the process involves reading sensor values every few seconds. You should see no impact on your normal workflow speed.

Keywords: caffeinate, clamshell, claud-code, claude, closed-lid, homebrew, homebrew-cask, homebrew-formula, keep-awake, keepingyouawake, mac, macos-app, menubar, menubar-app
# Camera Storage Calculator

A free Windows app for sizing CCTV / video surveillance storage in minutes.

Enter your cameras once and get the answer in either direction:

- **I know the retention** -> how much storage (TB) and how many disks do I need?
- **I know the storage I have** -> how many days can I keep the recordings?

## Features

- Animated welcome screen, then straight to your projects
- Camera groups with quantity, resolution, codec (H.264 / H.265), FPS and **scene activity** (quiet, normal, busy)
- Estimated bitrate shown for every camera group, with an optional **bitrate override** when you know the real value
- Recording modes: **continuous**, **motion only**, and **continuous + motion boost**
- Editable motion percentage and idle quality
- RAID 5 / RAID 6 / RAID 10 and a safety reserve
- Total bandwidth, storage per day, and a retention table (7 to 180 days)
- **Projects:** every site is saved as its own project, with its cameras and storage settings. Start a new project or open an existing one from the left side of the app
- Works offline. Your projects are stored on your own computer
- Export and import a backup of your projects to move them to another computer

## Download

1. Go to the [**Releases**](../../releases/latest) page.
2. Download `Camera-Storage-Calculator-v1.1.0-Windows.zip`.
3. Right-click the zip, choose **Extract All**, open the folder and double-click **Camera Storage Calculator.exe**.

Keep the .exe inside its folder. It needs the other files next to it.

**Requirements:** Windows 10 or 11 (64-bit). No installation and no internet connection needed.

If Windows SmartScreen shows a warning (the app is not code-signed), click **More info** and then **Run anyway**.

## How to use

1. Click **Start a new project** and give it a name.
2. Add your camera groups (resolution, codec, FPS, scene activity, recording mode).
3. Choose what to calculate: retention known, or storage known.
4. Read the results. Everything is saved automatically.

## Important

All figures are **estimates**. Real bitrates change with scene content, lighting, night noise, VBR/CBR mode and smart-codec settings. For final design, use the real bitrate from your cameras or VMS in the *Bitrate override* box and confirm sizing with your VMS vendor's tools.

This is an independent tool and is not affiliated with or endorsed by any camera, VMS or storage manufacturer.

## Feedback

Found a bug or have an idea? Please open an [issue](../../issues). Feedback from integrators and security engineers is very welcome.

## License

Free to use for personal and commercial work. See [LICENSE](LICENSE) for the full terms.

## Author

Mahmoud Ahmed - physical security and systems integration.
LinkedIn: www.linkedin.com/in/mahmoud-ahmed-034b001b2



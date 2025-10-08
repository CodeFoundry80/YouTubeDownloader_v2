# 🎬 YouTube Video Downloader

---

TotalVirus detects 2 false positive viruses. Reason being it downloads FFMPEG and YT-DLP to fully function.
<img width="860" height="1376" alt="image" src="https://github.com/user-attachments/assets/84c792a5-c24c-4df0-9496-b1bd8d0b2d41" />


## ⚙️ Features

- 🎥 **Download YouTube videos (MP4)**
- 🎧 **Extract audio as MP3**
- 🗂️ **Choose custom download folder**
- 🌓 **Switch between Dark, Light, or System themes**
- 🪄 **Smooth fade-in animations and polished UI**
- 💬 **Real-time progress and console output**

---

## 🧭 How to Use

1. Launch **YouTube Downloader**  
2. Paste a valid **YouTube video link** into the text box  
3. Choose the **format** (MP4 for video or MP3 for audio)  
4. Select an **output folder** using the *Browse* button  
5. Click **Download**  
6. Watch progress in the console area as the file is fetched and converted  

> ⚠️ **Tip:** This app supports single video URLs only (not playlists).

---

## 🪪 Legal Disclaimer

This application is intended **for personal, lawful use only**.

By using this software, you agree that:

- You will only download content that **you own the rights to**  
  or that is **freely available for download** by the copyright holder.  
- You are **solely responsible** for ensuring compliance with YouTube’s Terms of Service and applicable copyright laws.  
- The developer(s) of this software **cannot be held liable** for any misuse, copyright infringement, or violation of third-party rights.  
- This project is provided **“as-is” without warranty** of any kind.  

---

## 🧰 Requirements

- Windows 10 or 11  
- [.NET 8.0 Runtime](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)  
- Internet connection  

---

## 🛠️ Developer Notes


The backend download logic uses standard process calls to `yt-dlp` and `ffmpeg.` for fetching content. These files will be downloaded one time 
(unless you delete them from the %temp%\YouTubeDownloader\ folder. This makes it easier so that you dont have to download the files each time.
This version auto fetches, the version I made that precompiles these utilities in it, comes out to about 300mb file. This one is less than 2mb.

---

## 🧑‍💻 Credits

Developed by **uɐꟽǝɓpoᗡ.  (CodeFoundry80)**  
- GitHub: [https://github.com/CodeFoundry80](https://github.com/CodeFoundry80)  

---

## 📜 License

This project is released under a **customized MIT-style license**.  

You are free to **use and distribute** this software **as-is**, provided that:  
- The application remains **fully intact and unmodified** in both content and functionality.  
- You **do not alter, remove, or obscure** any part of the code, branding, or credits.  
- Redistribution must occur **in its original, unmodified form**.  

Modification, repackaging, or redistribution of altered versions of this software is **strictly prohibited**.  



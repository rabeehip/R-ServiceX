## Google-Drive Index

Combining the power of [Cloudflare Workers](https://workers.cloudflare.com/) and [Google Drive](https://www.google.com/drive/) will allow you to index your files on the browser on Cloudflare Workers.

</details></h2>

## ✨ Unique Features

- 🔎 Search function also works for folder root type
- 🗂️ Support for duplicated file and folder names
   - 🔤 Files and folders with the same name
   - 🔠 Files and folders with the same name but different cases
- ⌛ Ability to force index to load (can be disabled)
- 🚀 Quick actions tab (can be disabled):
   - 📥 Direct Download
   - ↗️ Open link in a new tab
   - 📋 Copy link to the clipboard
- 🔐 File id encryption
- 🔢 File size in 1024 bytes system
- 👥 Support for multiple (unlimited) username/password pairs
- 📚 Ability to download files of Google Workspace apps in all available formats:
   - 📘 Google Documents - ( docx | odt | rtf | pdf | plain text | html | html/zipped | epub )
   - 📊 Google Spreadsheets - ( xlsx | ods | csv | pdf | html/zipped )
   - 👨‍🏫 Google Presentations - ( pptx | odp | pdf | plain text )
   - 🖌 Google Drawings - ( pdf | jpg | png | svg )
   - ✍ Google Jamboards - ( pdf )
   - 📜 Google Apps Scripts - ( json )
   - 📃Google Forms - ( html/zipped )
- 🗃️ Ability to change the order which files are listed in
- 📂 Ability to access/download shortcuts of files and folders
- 🦠 Ability to download files which Google has flagged as a virus (can be disabled)
- 🗑️ Ability to download trashed files (can be disabled)
- 🔡 Support for all characters including slashes('/', '\\') and emojies in file/folder names
- 📅 Shows modified date & time in your local time
- 🕒 Modified time displaying issue on Safari browser and browsers on iOS has been fixed

## ⚡ Features

- 🖥 Video Player - ( mp4 | webm | avi | mpg | mpeg | mkv | rm | rmvb | mov | wmv | asf | ts | flv )
- 🎧 Music Player - ( mp3 | flac | wav | ogg | m4a )
- 📚 Document Viewer - ( html | php | css | go | java | js | json | txt | sh | md | pdf )
- 🖼️ Image Viewer - ( bmp | jpg | jpeg | png | gif )
- 🔎 Multi-level Search
- 🔐 Multi drive encryption
- 📱 Mobile Friendly
- 💾 Page-level caching, browser forward and backward without reloading
- 🧥 Dark Theme
- 🎨 Main Color:
   - red | pink | purple | deep-purple | indigo | blue | light-blue |
     cyan | teal | green | light-green | lime | yellow | amber | orange |
     deep-orange | brown | greyblue-grey
- 🖌 Accent Color:
   - red | pink | purple | deep-purple | indigo | blue | light-blue | cyan | teal | green | light-green | lime | yellow | amber | orange | deep-orange

## 📖 Wiki

### Refresh Token

```The Refresh Token is obtained by the successful Authorization made with the client id and secret id. ex. x/xxxxxxxx```

### Search Function limitation ⚠️

```If you perhaps put a folder in the field rather than just "root", then the search function does not work. ```

### Deploy

1. Configure the values such as client id & secret. 
2. Generate an authorisation token using these credentials.
3. Copy that token and configure the refresh token.
4. Required vars are set; now, the deployment to Cloudflare is ready. 

__**Note:** Use rclone or other engine to generate an authorisation token.__

## 🤝 Special Thanks & Credits

### Source:
- **[donwa](https://github.com/donwa)** : for writing such a great script
- **[yanzai](https://github.com/yanzai) & all initial contributors** : for contributing to the project
- **[5MayRain](https://github.com/5MayRain)** : for implementing Nexmoe theme

## ⚖ LICENSE

**_[Google-DriveIndex - Extended](https://github.com/rabeehip/Google-DriveIndex)
) by [Rabeeh IP](https://github.com/rabeehip/Google-DriveIndex) is licensed under the [MIT License](https://opensource.org/licenses/MIT), which you can find in the [Google-DriveIndex/LICENSE](https://github.com/rabeehip/Google-DriveIndex/blob/main/LICENSE) file._**

### 
# R-ServiceX (Google Drive Index) 🔥

R-ServiceX harnesses the synergy of [Cloudflare Workers](https://workers.cloudflare.com/) and [Google Drive](https://www.google.com/drive/) to provide a browser-based file indexing platform—secure, scalable, and seamless.

</details></h2>

## 💡 Key Capabilities

- **Intelligent Search Functionality**
  - Fully operational at the root folder level
- **Duplicate Name Resolution**
  - Supports identical file and folder names
  - Handles case-sensitive naming distinctions
- **Index Control**
  - Option to forcefully reload index (configurable)
- **Quick Actions Panel** _(optional)_
  - Direct download access
  - Open links in a new tab
  - Copy links to clipboard
- **Secure Identifier Encryption**
- **File Size Accuracy**
  - Displayed using the 1024-byte system
- **Multi-User Authentication**
  - Unlimited username/password pairs supported
- **Comprehensive Export Options for Google Workspace Files**
  - _Google Docs_: docx, odt, rtf, pdf, txt, html, zipped HTML, epub
  - _Google Sheets_: xlsx, ods, csv, pdf, zipped HTML
  - _Google Slides_: pptx, odp, pdf, txt
  - _Google Drawings_: pdf, jpg, png, svg
  - _Google Jamboard_: pdf
  - _Google Apps Script_: json
  - _Google Forms_: zipped HTML
- **Custom File Ordering**
- **Shortcut Resolution**
  - Access and download shortcut links to files and folders
- **Override Options** _(optional)_
  - Download files flagged by Google as unsafe
  - Access trashed files
- **Full Character Set Compatibility**
  - Supports slashes, Unicode, and special symbols in file/folder names
- **Localized Time Stamps**
  - Modified dates/times shown in the user's timezone
- **Safari and iOS Compatibility Fixes**

## ✨ Feature Highlights

- **Video Support**: mp4, webm, avi, mpg, mpeg, mkv, rm, rmvb, mov, wmv, asf, ts, flv
- **Audio Support**: mp3, flac, wav, ogg, m4a, opus
- **Document Rendering**: html, php, css, go, java, js, json, txt, sh, md, pdf
- **Image Display**: bmp, jpg, jpeg, png, gif
- **Advanced Search Capability**: Supports multi-level traversal
- **Multi-Drive Encryption Support**
- **Responsive Mobile Design**
- **Optimized Performance**
  - Page-level caching
  - Forward/backward navigation without reload
- **Dark Mode**: Aesthetic and user-friendly night theme
- **Color Customization**
  - **Primary Colors**: red, pink, purple, deep-purple, indigo, blue, light-blue, cyan, teal, green, light-green, lime, yellow, amber, orange, deep-orange, brown, grey, blue-grey
  - **Accent Colors**: Same as above

## 📖 Deployment Guide

### Refresh Token Generation

`A refresh token is obtained upon successful OAuth2 authorization using a valid Client ID and Secret. Format: x/xxxxxxxx`

### Search Limitations

`Search only functions if 'root' is specified. Providing a folder path will disable this feature.`

### Deployment Steps

1. Configure the Client ID and Secret.
2. Generate an authorization token using a utility like `rclone`.
3. Extract and configure the refresh token.
4. Set the necessary environment variables.
5. Deploy the project using Cloudflare.

## 📜 Acknowledgments

- Special thanks to the original module authors
- Developed and maintained by [Rabeeh IP](https://github.com/rabeehip)

## 📄 License

**R-ServiceX** is licensed under the [MIT License](https://opensource.org/licenses/MIT).  
Please refer to the [LICENSE](https://github.com/rabeehip/R-ServiceX/blob/X/LICENSE) file for details.

---

Thank you for choosing **R-ServiceX** — a streamlined, professional solution for advanced Google Drive indexing ♥️.

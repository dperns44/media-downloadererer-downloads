Download **Media-Downloaderererer-1.8.0-beta.8-Setup.exe** and run it to update the Windows app. Existing projects and downloads stay in place.

- Adds FrameRate watch links and embedded FrameRate videos on studio project pages, including Giant Ant.
- Uses the page's declared main video, title and thumbnail before incidental media in scripts.
- Lite carries the studio page referrer into embedded downloads.
- Access-denied responses now explain that the host refused the connection, instead of displaying a raw downloader error.
- Keeps the circular logo, looping cuts, projects, concurrent downloads and existing exports.

Verified on 11 November: the supplied OpenTable FrameRate video (30 seconds) and Giant Ant HoYoverse trailer (47 seconds) downloaded as playable MP4s in desktop and Lite. Lite thumbnail, download, trim/export and replacement-video flows passed. Resolver tests cover unrelated background media, malformed domains and recursive embeds.

Known limitation: Giant Ant's Right Now Vimeo embed returned HTTP 401 and an access-restricted page from the test connection. This release does not claim to fix that restriction or all intermittent Instagram/Vimeo failures. Private, removed, sign-in-only and protected sources may remain unavailable.

Windows x64 beta. Unsigned; clean coworker-PC installation and every creative-app integration remain unverified.
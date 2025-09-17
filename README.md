# MiniGuinea
<img width="128" height="128" alt="17558778127483925235314353808994" src="https://github.com/user-attachments/assets/6cb72e00-cf3a-4d79-a7b6-14bc73c39ded" />

MiniGuinea is a simple Chromium extension that:
- Stops dozens of ad providers from serving their ads; including but not limited to Google Doubleclick, Amazon Advertising, and CoinZilla
- Defeats several different analytics providers, most notably Google Analytics (not fully functional at the moment), Cloudflare Insights, and the United States Digital Analytics Program
- Uses Manifest v3 (if you don't know what this means, don't worry about it)
- Avoids interfering with the user experience as much as possible

MiniGuinea is known to work in Chromium, Google Chrome, and Microsoft Edge. It should function properly in most other Chromium browsers too.

MiniGuinea does not officially support Firefox-based browsers (Firefox, Tor Browser, etc.) at the moment. Firefox support is not planned for the foreseeable future.
 
# Comparison to other ad blockers
## Tracker blocking ability
| Tracker     | Blocked by MiniGuinea? | Blocked by AdBlock? | Blocked by Ghostery? |
| ----------- | ----------- | ----------- | ----------- |
| Google Analytics      | Yes*       | No        | Yes**        |
| Qualtrics   | Yes         | No        | Yes       |
| Digital Analytics Program   | Yes        | No       | Yes        |
| Cloudflare Insights   | Yes        | No       | Yes        |
| Jetpack Analytics   | Yes       | No       | Yes        |
| Wikitide Analytics (based on Matomo)   | Coming soon in 0.3.0       | No       | Yes        |****

## Ad blocking ability
| Tracker     | Blocked by MiniGuinea? | Blocked by AdBlock? | Blocked by Ghostery? |
| ----------- | ----------- | ----------- | ----------- |
| DoubleClick      | Yes       | No        | Yes**        |
| Qualtrics   | Yes         | Yes        | Yes       |
| Wikitide Analytics (based on Matomo)   | Coming soon in 0.3.0       | No       | Yes        |********

*MiniGuinea may fail to block some instances of this tracker, but it stops it most of the time.

** Ghostery appears to be injecting its own script here. More information is needed.

# How to Get IPA

1. Download the YT IPA from [here](https://27man-my.sharepoint.com/personal/qn____27man_onmicrosoft_com/_layouts/15/onedrive.aspx?ga=1&id=%2Fpersonal%2Fqn____27man_onmicrosoft_com%2FDocuments%2FDecrypted+IPAs)
2. Upload it to Google Drive
3. On GDrive, select file > Share. Set General Access to "Anyone with the link" and copy link
4. Modify link from the shareable version to direct download version
```
Original shareable link: https://drive.google.com/file/d/FILE_ID/view?usp=sharing
Direct download link:   https://drive.google.com/uc?id=FILE_ID
```
5. Test `wget "LINK" -O yt.ipa` locally. It will PROBABLY download a webpage instead of the IPA
6. If it succeeds, skip this step. </br>
If it fails:
   1. Open the direct download link on your browser.
   2. Open the Dev console with cmd+shift+c and go to the Network tab
   4. On the web page, press the "Download" button and cancel
   5. On your Network console, you should see a new request appear (and be cancelled, in red)
   6. Click the aforementioned request and copy the address of the `GET` request
7. Follow the build instructions from [here](https://github.com/qnblackcat/uYouPlus/wiki/Building)

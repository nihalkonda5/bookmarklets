# bookmarklets

## Dropdown TV Picture-In-Picture
When you are on the page of dropout where the video is playing, Click on the bookmarklet. It will then open the embedded page in new tab. Once the video starts playing in the new tab, Click the bookmarklet again.

[DropoutTvPiP](javascript:\(\(\)=>{const vid = document.getElementsByTagName\("video"\)[0];if\(vid\){vid.disablePictureInPicture=false;vid.requestPictureInPicture\(\);}else{window.open\(document.getElementById\("watch-embed"\).src,"_blank"\);}}\)\(\))

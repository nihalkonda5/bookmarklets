# bookmarklets

## Dropdown TV Picture-In-Picture
When you are on the page of dropout where the video is playing, Click on the bookmarklet. It will then open the embedded page in new tab. Once the video starts playing in the new tab, Click the bookmarklet again.

[DropoutTvPiP][1]

[1]: javascript:(()%3D%3E%7Bconst%20vid%20%3D%20document.getElementsByTagName(%22video%22)%5B0%5D%3Bif(vid)%7Bvid.disablePictureInPicture%3Dfalse%3Bvid.requestPictureInPicture()%3B%7Delse%7Bwindow.open(document.getElementById(%22watch-embed%22).src%2C%22_blank%22)%3B%7D%7D)()

[Hello Bookmarklet](javascript:void%20function%28%29{var%20a=prompt%28%22What%20is%20your%20name%3F%22,%22Your%20Name%22%29;null!=a%26%26alert%28%22Hello%20%22+a%29}%28%29;)



### 关于 professional-technology-manual
```
个人的专业技术体系，学习的记录
```

```javaScript
document.getElementById()

console.log(document.querySelector('选择器'))
console.log(document.getElementById('qqqq'))

document.getElementsByTagName('iframe')[1].contentDocument;

// 目标
document.getElementsByTagName('iframe')[0].contentDocument;

// 定位到了目标div
document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument;
// 定位到视频
document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api');


document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').play();

document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').pause();

// 调整倍数
document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').defaultPlaybackRate=8;

document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').playbackRate

document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').pause();
document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').playbackRate=3;
document.getElementsByTagName('iframe')[0].contentDocument.getElementsByTagName('iframe')[0].contentDocument.getElementById('video_html5_api').play();
```
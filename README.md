# videojs-relatedCarousel

Display a carousel of related content plugin for video.js

## Getting Started
Download [videojs](http://www.videojs.com/)

In your web page:
```html
<video id="video" src="movie.mp4" controls></video>
<script src="video.js"></script>
<script src="videojs-relatedCarousel.js"></script>
<link href="videojs-relatedCarousel.css" rel="stylesheet">
<script>
videojs('video', {}, function() {
    var player = this;
    player.relatedCarousel([
      { imageSrc: 'video1-image.jpg', url: '/video1-url.html', title: 'video 1 title' },
      { imageSrc: 'video2-image.jpg', url: '/video2-url.html', title: 'video 2 title' }
    ]);
});
</script>



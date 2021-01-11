The HTML5 <audio> and <video> tags make it simple to add media to a website. You need to set src attribute to identify the media source and include a controls attribute so the user can play and pause the media.

Embedding Video
<video src = ""  width = "" height = "" controls> h</video>

You can use <source> tag to specify media along with media type and many other attributes.
1) controls

If this attribute is present, it will allow the user to control video playback, including volume, seeking, and pause/resume playback.

2)autoplay

This Boolean attribute if specified, the video will automatically begin to play back as soon as it can do so without stopping to finish loading the data.

3)height

This attribute specifies the height of the video's display area, in CSS pixels.

4)width

This attribute specifies the width of the video's display area, in CSS pixels.

Embedding Audio
<audio src = "foo.wav" controls autoplay>  </audio>


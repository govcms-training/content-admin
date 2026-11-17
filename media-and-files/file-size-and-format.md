# File size and format

GovCMS includes a number of restrictions regarding file types and sizes for all websites on the platform.

Singular files can't be any larger than **256 MB**.

If you absolutely MUST upload a larger media (and it can't be reduced in size via file compression), you can contact the GovCMS Service Desk, who can upload it for you.

There are also some file types that are blocked from being uploaded. These mainly relate to executable files that could be used as attack vectors against the platform and its users. There's an article on the [GovCMS Knowledge Base about these limitations](https://www.govcms.support/support/solutions/articles/51000041330).

It should also be noted that legacy formats are also blocked, such as:

* .doc
* .ppt
* .xls
* .rtf

You can find out more about [legacy formats](https://www.govcms.support/support/solutions/articles/51000362819) on the GovCMS Knowledge Base.

### Optimising images and video

One major culprit for large files on websites is images and videos that haven't been optimised (reduced in size).

Images taken directly from digital cameras can be thousands of pixels in width and height, but when shown on a website they're probably no larger than 1900 pixels wide. This means your website visitors download the full-sized image, despite getting no benefit from the larger size.

To optimise your images for the web, ensure they're scaled down before being uploaded, and saved in a compressed format such as WebP or PNG. Additionally, you should use **image styles** to dynamically resize the images before they're rendered. Image styles is something your developers or advanced content editors need to implement.

Videos should be hosted externally, on platforms that specialise in hosting and serving compressed video. However you may have video that's used as a motion background on your website. In these cases, you should ensure the videos are not encoded with audio, as a video that has audio that's muted (such as for a background element) still contains the audio in the file, thus increasing the file size.

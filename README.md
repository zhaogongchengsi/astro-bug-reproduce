# Image path error and style loss

When you put the image in the public images folder, and then use'url (images/xxx.png) 'to use the image through the url in css, it is correct at development time, but the path will be wrong after the build is completed, because the generated css is in the assets folder. If you use preview, you can't see the picture in the preview. 

And it will delete some seemingly meaningless but useful css code, such as`width: 100%`, `left: 0`... .

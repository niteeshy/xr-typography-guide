# Resolution and Refresh Rate

The **resolution** of the display is the crucial component that affects the level of details perceived by human eyes. In AR headsets, the useful metric for resolution is pixels per degree (PPD). It is the number of pixels per degree it present to the eye, the number of pixels in the horizontal display line has to be divided by the horizontal field of view provided by the optics of the headset (lens). E.g. In a display with 1280 x 800 px, the pixels per eye are 640 x 800 px, and with a FOV of 90 degrees the PPD comes out to be 7.1 (640/90). This is way too low as compared to the retina resolution of the eye, the PPD of the human fovea is approximately 60 PPD.&#x20;

A lower pixel density can cause blurring of text, pixelation and screen door effect (the visible fine lines between pixels on a display when seen up close). A higher PPD results in sharper and more realistic images, however, the higher pixel density of the display is not necessarily the same because the pixels on the screen are magnified through optics. The pixel magnification can be different for different devices with varying optics resulting in different pixel densities presented to the eye.

Another related component is **refresh rate** which means the number of times per second the display grabs a new image from the GPU and shows it to the viewer.

{% hint style="info" %}
The refresh rate influences how the display renders motion and becomes crucial for text rendering in the scene where the text is not stationary. A higher refresh rate produces better text.
{% endhint %}

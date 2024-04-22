Repository to reproduce an issue discovered in MAUI where the Stroke component of a Shape was not applying the gradient as it did in Xamarin.Forms.

Example screenshot:

![image](https://github.com/crhalvorson/MauiPathGradientRepro/assets/14127039/1adef578-fe98-4503-87ca-dbf1fa647a16)

A potential workaround is to use a Border, although this may be more difficult for some use cases:

![image](https://github.com/crhalvorson/MauiPathGradientRepro/assets/14127039/3736c7ee-f07c-47ea-ad8e-5171598242f4)

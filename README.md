# <img src="http://touchgfx.com/static/touchgfx_logo_open_rep_small.png" width="500" height="135">

TouchGFX is a C++ graphics framework for limited-resource embedded systems based on ARM Cortex-M3, M4 and M7. You can use TouchGFX to create modern user interfaces with a smartphone-like look and feel on hardware platforms an order of magnitude less powerful (48-216 MHz) than smartphones.

This repository, the *TouchGFX Open Repository*, contains numerous examples of, and ideas for, graphical components such as widgets, containers and "mixins" that are not part of the core distribution. They can be used as a source of inspiration for your applications free of charge; The components are all generalized to some extent but probably needs some sort of fine tuning to match your specific needs. Please note that none of the components are guaranteed to be maintained across new versions of TouchGFX. 

You can request a full evaluation version of the framework, as well as order commercial licenses, on the [TouchGFX website](http://touchgfx.com/product-details/evaluation/). Read more about the concept of widgets, containers and "mixins" in the TouchGFX [documentation](http://touchgfx.com/documentation/html/index.html).

# Contributing

This repository would greatly benefit from TouchGFX developers around the world sharing some of their work. Having a solid community that shares complex ideas for TouchGFX widgets is something that can help reduce development time greatly. If you would like to contribute to this repository you can fork and follow the guide below. When done, open a pull request to your branch. Each contribution should conform to the following standards:

 1. Create a suitable folder inside widgets/ for your contribution
 2. Supply at least source- and headerfiles, example code is welcome, but not necessary.
 2. Supply one or more screenshots of the widget in action. Graphical components that make up the widget are also welcome for clarity.
 3. Create a *README.md* containing, in Markdown:
   - Purpose of the widget - Any screenshots you may have could be shown here.
   - Version(s) of TouchGFX you've tested your code on
   - Functional description of the widget and its configuration. Code can be verbatim formatted in the .md file by indenting with 4 spaces.

Please note that your contribution is subject to the terms that can be found <a href="license.txt">here</a>.

Thank you for your contribution!
# List of Components

In the following table you can see the name, TouchGFX version, and a preview of the TouchGFX graphical components in this repository. 

The TouchGFX version stated is the version that the component has been tested with. All components are expected to work with later versions of TouchGFX as well, however, this is not guaranteed. 

<table style="width:100%">
  <tr>
    <td>LinearGauge <br>TouchGFX 4.1.1<br><a href="widgets/LinearGauge/"><img src="widgets/LinearGauge/LinearGaugeThumbnail.png" height="100" style="max-width:100%;"></a></td>
    <td>ExtendedZoomAnimationImage <br>TouchGFX 4.1.1<br> <a href="widgets/ExtendedZoomAnimationImage/"> <img src="widgets/ExtendedZoomAnimationImage/screenshots/imgThumbnail.png" height="100"></a></td> 
    <td>Carousel <br>TouchGFX 4.1.1<br> <a href="widgets/Carousel/"> <img src="widgets/Carousel/screenshots/carouselThumbnail.bmp" height="100"></a></td>
  </tr>
  <tr>
    <td>DotIndicator <br>TouchGFX 4.1.1<br>  <a href="widgets/DotIndicator/"> <img src="widgets/DotIndicator/screenshots/img00.bmp" height="100"></a></td>
    <td>SwipeContainer <br>TouchGFX 4.1.1<br> <a href="widgets/SwipeContainer/"> <img src="widgets/SwipeContainer/screenshots/img01.bmp" height="100"></a></td> 
    <td>Gauge <br>TouchGFX 4.2<br> <a href="widgets/Gauge/"> <img src="widgets/Gauge/GaugePressure.png" height="100"></a></td>
  </tr>
  <tr>
    <td>WheelSelector <br>TouchGFX 4.2<br> <a href="widgets/WheelSelector/"> <img src="widgets/WheelSelector/days_fade_in.png" height="100"></a></td>
    <td>CircularProgress <br>TouchGFX 4.2<br> <a href="widgets/CircularProgress/"> <img src="widgets/CircularProgress/example.png" height="100"></a></td> 
    <td>Lens <br>TouchGFX 4.2 <br><a href="widgets/Lens/"><img src="widgets/Lens/screenshots/lens-effect.png" height="100"></a></td>
  </tr>
  <tr>
    <td>Graph <br>TouchGFX 4.3<br> <a href="widgets/Graph/"> <img src="widgets/Graph/screenshots/img00.bmp" height="100"></a></td>  
    <td>QRCode <br>TouchGFX 4.3<br> <a href="widgets/QRCode/"> <img src="widgets/QRCode/screenshots/qr.bmp" height="100"></a></td>
    <td>Animated Gauge<br>TouchGFX 4.4.1<br><a href="widgets/AnimatedGauge/"> <img src="widgets/AnimatedGauge/screenshots/AnimatedGauge-small.gif" height="100"></a></td>
  </tr>
</table>
 
# Links

* [Website] (http://touchgfx.com)
* [Documentation] (http://touchgfx.com/documentation/html/index.html)

# Videos

* [TouchGFX Demo on STM32F429 Evaluation Board 4.3"](http://www.youtube.com/watch?v=QcKX_Pc6ldU)
* [TouchGFX Demo on STM32F429 Discovery Board 2.4"](http://www.youtube.com/watch?v=j-fgE1hOlbo)
* [TouchGFX Demo on Embedded Artists LPC4088 Display Module 4.3"](https://www.youtube.com/watch?v=g_GjiUXrIc8)
* [TouchGFX Demo on Embedded Artists LPC4357 DevKit 4.3"](http://www.youtube.com/watch?v=OzRpGLfjh1c)
* [TouchGFX Demo on TouchGFX Demo Board NXP 4357 4.3"](http://www.youtube.com/watch?v=dvSK0oXQqfA)

# Screenshots

<img align="left" src="http://touchgfx.com/static/touchgfx_demos.png">

# License Terms

All software, including widgets, containers and mixins and codes found in this repository (hereinafter referred to collectively as the “Software”) are available to download free of charge and the Software may be used for both commercial and non-commercial purposes. You may use, copy, redistribute and modify the Software as needed. The code is distributed in the hope that it will be useful. 

Read Full License/Contribution Terms text <a href="license.txt">here</a>. 

# Ownership

The TouchGFX framework is a Draupner Graphics product.

<img align="left" width="150" height="118" src="http://touchgfx.com/static/draupner_vlogo.png">

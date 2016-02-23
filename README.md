# LMSocialMenu (v1.0)

##### Introduction
LMSocialMenu is a simple css styled bar which you can put all your social media sites like Facebook, Twitter, Google+ (it's a lie, nobody uses Google+), linkedIn and so on. It's fixed on the left side of window and it has a beatiful animation in order to show the name.

##### Installation
To use LMWeb Finder you need to link .css file provided in your document head:
```html
    <link href="LMSocialMenu.css" type="text/css" rel="stylesheet"> 
```
Also you need to create a simple html structure which is expandible to all you need:
```html
<div id="social-menu">
    <span class="social-line">
        <span class="logo"><a href="http://facebook.com" target="_blank"><img src="facebook_logo.png" alt="Facebook"></a></span>
        <span class="text facebook-text">Facebook</span>
    </span>
</div>
```
You only need to clone social-line span all times changing social network name, background and link.

#####Configuration
If you don't like classes names or id it's so easy to change: go to css file and change name; go back to html and take care chosen names coincide.
<br /> 
There is an example for you to view how it works.<br /> 
<br />

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/" target="_blank"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">LMSocialMenu</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">legomolina</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/" target="_blank">Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional License</a>.

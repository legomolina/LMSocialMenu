# LMSocialMenu (v1.0)

##### Introduction
LMSocialMenu is a simple css styled bar which you can put on all your social media sites like Facebook, Twitter, Google+ (it's a lie, nobody uses Google+), linkedIn and so on. It's fixed on the left side of the window and it has a beatiful animation in order to show the social network name.

##### Installation
To use LMWeb Finder you need to link .css file provided in your document head:
```html
    <link href="LMSocialMenu.css" type="text/css" rel="stylesheet"> 
```
Also you need to create a simple html structure which is expandible in any way you need it:
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
If you don't like class names or id it's really easy to change: go to css file and change name; go back to html and take care the chosen names are the same.
<br /> 
There is an example for you to see how it works.<br />

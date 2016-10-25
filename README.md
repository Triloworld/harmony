# Harmony

# Why another frontend framework?
I'am tired to creating something from scrach, using plugins that don't match with each other and many other problems like separating logic from styling etc.
What we all need is simply, copy and paste solution to create and maintain frontend code. 

# What we need?
- simple rules
- flexible to cover all possible needs
- separation concept in JS,CSS,HTML by utilizng MVC
- copy and paste in defult supported CMS
- backward compatible

# Base
We don't need to write uncompiled code anymore:
- HTMl - TWIG
- CSS - SCSS
- JS - jQuery

# Separation

Frontend in 99% is mess without rules and standards. 
But what is best to keep it DRY/MVC, clean and simple?

We found holy grail in creating something similar what web components are. 
Class have simply, one leter prefixes, js use only data- atrib and html tags are untouched to reset style.

<div //MODEL
 class="STYLE" //VIEW
 data-js="CONFIGURATION" //CONTROLLER
>DATA</div>

 
# FAQ

# What browser is supported?
The same like jQuery 3.0 and jQuery 3.0 Compact - https://blog.jquery.com/2014/10/29/jquery-3-0-the-next-generations/

# What CMS is supported by default?
This framework and rules will be applied to 3 common system in mind by default: 

 - Wordpress - have possibility to connect to Twig, JS is compatible with our approach
 - Magento 2 - have possibility to connect to Twig, JS is compatible with our approach
 - Drupal 8 - have by default Twig, JS is compatible with our approach
 
# Why this CMS platform we use?
They cover all of needs in web developing and are moderate and they give possibility to use our framework and rules.
Other are just need twig and all comunication need to be handle ajax for maximum flexibility.
We need separation from 

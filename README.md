== IB Theme ==
=========

IB Theme

IB WordPress Theme, Copyright (C) 2014 IdeaBox Themes
IB is distributed under the terms of the GNU GPL

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 2 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.


Hi. I'm a starter theme called `Ib`. I'm a theme meant for hacking so don't use me as just as a Parent Theme. Instead try turning me into the next, most awesome, WordPress theme out there. That's what I'm here for.

My ultra-minimal CSS might make me look like theme tartare but that means less stuff to get in your way when you're designing your awesome theme. Here are some of the other more interesting things you'll find here:

* Full Bootstrap Power, seamlessly integrated in Automattic's starter theme _s to bring these two together the cleanest way.
* A just right amount of lean, well-commented, modern, HTML5 templates.
* A helpful 404 template.
* A sample custom header implementation in `includes/custom-header.php` that can be activated by uncommenting one line in functions.php and adding the code snippet found the comments of `inc/custom-header.php` to your `header.php` template.
* Custom template tags in `includes/template-tags.php` that keep your templates clean and neat and prevent code duplication.
* Some small tweaks in `includes/extras.php` that can improve your theming experience.
* Keyboard navigation for image attachment templates. The script can be found in `js/keyboard-navigation.js`. It's enqueued in `functions.php`.
* Smartly organized starter CSS in `style.css` that will help you to quickly get your design off the ground.
* Licensed under GPLv3 or later. :) Use it to make something cool.

== Getting Started ==
---------------------

If you want to keep it simple, head over to http://underscores.me and generate your `IB Theme` based theme from there. You just input the name of the theme you want to create, click the "Generate" button, and you get your ready-to-awesomize starter theme.

If you want to set things up manually, download `IB Theme` from github. The first thing you want to do is copy the `IB Theme` directory and change the name to something else - Like, say, `megatherium` - then you'll need to do a three-step find and replace on the name in all the templates.

1. Search for `'ib'` (inside single quotations) to capture the text domain.
2. Search for `ib_` to capture all the function names.
3. Search for <code>&nbsp;Ideabox</code> (with a space before it) to capture DocBlocks.
4. Search for `ib-` to capture prefixed handles.

OR

* Search for: `'ib'` and replace with: `'megatherium'`
* Search for: `ib_` and replace with: `megatherium_`
* Search for: <code>&nbsp;Ideabox</code> and replace with: <code>&nbsp;Megatherium</code>
* Search for: `ib-` and replace with: `megatherium-`

Then, update the stylesheet header in style.css and the links in footer.php with your own information. Next, update or delete this readme.

Now you're ready to go! The next step is easy to say but harder to do: make an awesome WordPress theme. :)

Good luck!

We used the Following Schema in this WordPress theme.
Source:http://schema.org/docs/documents.html


== Changelog ==
---------------

= 1.1 =

12.12.2013

Bootstrap update to 3.0.3.
Add the Bootstrap LESS and JS files.
Minor CSS fix for wordwrap.

== 1.0 ==

08.08.2013

Initial release.



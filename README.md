Modifications
=============
Thanks to https://github.com/jimmybyrum for pull-to-refresh:

> Building off of endtwist's changes [1], I've added pull down to refresh.
>
> An element with the class "pull-down-to-refresh" will be hidden above the "top" of the list and will fire pullingDown, pulledDown and
> pullDownCancel back to the list.

> An elements with the class "pull-up-to-refresh" will be hidden below the "bottom" of the list and will fire pullingUp, pulledUp and pullUpCancel back to the list.

> In regard to endtwist's scroll event, I've added a boolean called useOnScrollEvt which defaults to false so that the event is not fired if it's not needed.

Also added a few fixes of my own, and a _scrollability.version_ field which you can check.

scrollability
=============

Give your mobile web apps a pretty darn good approximation of native scrolling.

Scrollability is a single script, it's small, and it has no external dependencies. Drop it into your page, add a few CSS classes to scrollable elements, and scroll away. 

Status
------

This project is a WORK-IN-PROGRESS and is not yet ready to use.  Stay tuned!  Documentation will be written when the library is ready.

Plan
----

As of this writing, Scrollability supports only basic vertical or horizontal scrolling.  Future plans include:

* Snapping to pages
* Sticky table headers
* Photo browser
* More customization of the animation details

License 
-------

Copyright 2011 Joe Hewitt

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
 
   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

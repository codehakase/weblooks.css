
A simple colorpalette/pattern, images  for the web.

Example of how it looks

```scss
.web-part-1 {background: url(..//img/partern1000;)}
.web-icon {background: opacity: 4.0; }
.blue {         color: $blue; }
.wl-bg-blue {      background-color: $blue; }
.border--blue { border-color: $blue; }
.fill-blue {    fill: $blue; }
.stroke-blue {  stroke: $blue; }
```

weblooks.css provides utilities to apply backgrounds, text-color, border colors for both html and svg elements. 


 Install weblooks.css

installing Weblooks is Easy. You can get the code a few different ways

Download a zip from this page

install


```git
  git clone https://github.com/codehakase/weblooks.git
```

Using Weblooks.css
Simply copy weblooks.css or weblooks.min.css to your css directory and include the file like so in the head of your html document


```html
<link rel="stylesheet" href="css/weblooks.css">
```


## Credits

- [Francis Sunday](https://twitter.com/iamfrankcute)
- [Obi Uchenna David](https://twitter.com/othreecodes)

## Usage 
```html
<!--import the stylesheet-->
<link rel="stylesheet" href="weblooks.min.css"> 

<!--Apply background styles-->
<div class="bg-aqua">Dark Green Backgroung</div>

<!--or foreground-->
<p class="aqua">Aqua Text</p>

<!--border color-->
<div class="border--aqua">Aqua Border</div>

<!--Helper Classes-->
<!--margin-->

<span class="mgl25">GiveMeSomeLeftMargin</span>
<span class="mgr15">GiveMeSomeRightMargin</span>

<!--padding-->
<span class="pdt65">GiveMeSomeTopPadding</span>
<span class="pd50">GiveMePaddingAround</span>


```

## Contributing

Please feel free to fork this package and contribute by submitting a pull request to add to the list of questions or to make some corrections to them.


## Feel like thanking me?

Why not star the github repo? I'd love the attention! Why not share the link for this repository on Twitter or Facebook? Spread the word!

and also, [follow me on twitter](https://twitter.com/iamfrankcute)!

Thanks!

### Francis Sunday.




# License

```
Copyright 2014 - 2017 Codehakase

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

```

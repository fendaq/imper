<<<<<<< HEAD
An impress editor
=======
imper
=====

An impress presentation/slider editor website for creating impress.js slider 
(impress.js is inspired by the idea behind prezi.com)
>>>>>>> 90478ebb6a7fa2288cb38c9c3526cf6246dbd5d4

An presentation editor and the player powered by impress.js

### Imper Editor

[Imper editor website](http://switer.github.io/imper/)

### Imper Generation

[Imper generate impress Demo](http://switer.github.io/examples/imper.html#/step-1) 

[Imper generate google html5 slides Demo](http://switer.github.io/examples/html5slides.html)

### Imper Data Format
```javascript
{
  //globla config data
  "cntConf" : {
  	"height" : "600px",
		"width"  : "960px",
		"thumb"  : ""
	},
	//frame data set
	"cntData" : {
		//frame data
		"slider1" : {
			"anim"			: "", // frame transition animation
			"panelAttr" 	: "", // frame panel style attr
			//frame elements data set
			"element"   		: {
				//frame element data
				"data1":{
					"type"		: "DIV", // element type
					"cAttr"		: "", // element container style attr 
					"eAttr"		: "", // element style attr
          "pAttr"   : "", // element panel style attr
					"zIndex"	: 1, //z-index
					"value"		: "text content text!" //[text box || code box :  text string, image || video : data url] 
				},
				"data2":{
				        //...
				}
			}
		},
		//frame data
		"slider2" : {
			//...
		}
	}
}
```

### TODO List

*  English Version
*  Support multiple element selections while editing
*  Slider frame opertation(copy,paste,change position) 
*  touchable


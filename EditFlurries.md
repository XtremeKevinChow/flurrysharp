# Getting dirty #

Adding new flurries is quite easy by editing the **.config.**

> Find something like this: **"**

&lt;setting name="ExtraFlurries" serializeAs="Xml"&gt;

"**.
> From there, you can see**"

&lt;string&gt;

Cyclic Something:{32,blue,200.0,3.0}

&lt;/string&gt;

"**.**

  * **"Cyclic Something"** is the name of the Flurry cluster,
  * **"32"** is the number of streams,
  * **"blue"** is the color mode defined in Types.cs :
> > (red,magenta,blue,cyan,green,yellow,slowCyclic,cyclic,tiedye,rainbow,white,multi,dark)
  * **"200"** is the thickness of flurry ,
  * **"3.0"** is the speed.


> For example
  * 

&lt;string&gt;

hypnotic threesome + 1:{32,blue,200.0,6.0};{32,green,200.0,6.0};{32,red,200.0,6.0};{32,rainbow,200.0,6.0}

&lt;/string&gt;



> defines 4 different flurries to be rendered.

> Note that .NET 2.0 might save the settings under **%USERPROFILE%\Local Settings\Application Data\FlurrySharp\gibberish\_text\_about\_version\_and\_config\_owner** in **user.config**.
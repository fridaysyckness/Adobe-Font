# Adobe-Font




If you use Photoshop for any kind of graphic or web design, you'll understand the importance of having an array of fonts to choose from.

However, you may soon find yourself with a font overload. The problem is that once you get over about 1000 fonts in your Windows directory (usually “C:\Windows\Fonts\”) you’ll find that windows becomes very slow, particularly at startup.

To get around this, you don’t add the fonts to Windows, instead you add them into Photoshop, which is able to handle many more fonts than simply loading them into Windows.

The trick is to put them into the Adobe common fonts folder under program files (usually “C:\Program Files\Common Files\Adobe\Fonts\”).

You can get to this directory by going to Start > Run and issuing the following:

    %ProgramFiles%\Common Files\Adobe\Fonts

This should bring you to a directory called “fonts”, place your fonts in here and they will be loaded when Photoshop loads.

The more fonts you put in here, the longer Adobe Photoshop will take to load, however, Windows will perform a lot better overall this way.

If you’re downloading fonts from dafont.com like me, you’ll find that you’ll need to extract them from the zip file before you place them into this directory, although to most people that should be obvious.

You don’t have to reload Photoshop for the new font to start working, it should appear in the drop down menu straight away.

I had to do this the other day for the first time in ages on a new machine I had setup Adobe Photoshop CS3 on. I realised that I had forgotten the details! Once I had reminded myself I figured I would write it up here for future reference.

This should work on any version of Photoshop above 5.5, including Photoshop 6, 7, CS, CS2, CS3 and CS4.

Hope this helps!

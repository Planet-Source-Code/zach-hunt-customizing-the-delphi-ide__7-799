<div align="center">

## Customizing the Delphi IDE


</div>

### Description

Using the windows registry you can customize many different aspects of the Delphi IDE that are not available in the Enviornment options of Delphi. This tutorial shows how to do this. Please vote!
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Zach Hunt](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/zach-hunt.md)
**Level**          |Beginner
**User Rating**    |3.8 (15 globes from 4 users)
**Compatibility**  |Delphi 5, Delphi 4, Pre Delphi 4
**Category**       |[Registry](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/registry__7-36.md)
**World**          |[Delphi](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/delphi.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/zach-hunt-customizing-the-delphi-ide__7-799/archive/master.zip)





### Source Code

```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN">
<html xmlns:v="urn:schemas-microsoft-com:vml"
xmlns:o="urn:schemas-microsoft-com:office:office"
xmlns:w="urn:schemas-microsoft-com:office:word"
xmlns="http://www.w3.org/TR/REC-html40">
<head>
<meta http-equiv=Content-Type content="text/html; charset=windows-1252">
<meta name=ProgId content=Word.Document>
<meta name=Generator content="Microsoft Word 9">
<meta name=Originator content="Microsoft Word 9">
<link rel=File-List href="./Registry333_files/filelist.xml">
<title>Customizing the Delphi IDE</title>
<xml>
 <o:DocumentProperties>
 <o:Author>TH</o:Author>
 <o:LastAuthor>TH</o:LastAuthor>
 <o:Revision>2</o:Revision>
 <o:TotalTime>13</o:TotalTime>
 <o:Created>2002-05-06T05:28:00Z</o:Created>
 <o:LastSaved>2002-05-06T05:28:00Z</o:LastSaved>
 <o:Pages>1</o:Pages>
 <o:Words>654</o:Words>
 <o:Characters>3732</o:Characters>
 <o:Company>HFLP</o:Company>
 <o:Lines>31</o:Lines>
 <o:Paragraphs>7</o:Paragraphs>
 <o:CharactersWithSpaces>4583</o:CharactersWithSpaces>
 <o:Version>9.2720</o:Version>
 </o:DocumentProperties>
</xml>
<style>
<!--
 /* Style Definitions */
p.MsoNormal, li.MsoNormal, div.MsoNormal
	{mso-style-parent:"";
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	font-size:12.0pt;
	font-family:"Times New Roman";
	mso-fareast-font-family:"Times New Roman";}
h1
	{mso-style-next:Normal;
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	mso-outline-level:1;
	font-size:12.0pt;
	font-family:"Times New Roman";
	mso-font-kerning:0pt;}
h2
	{mso-style-next:Normal;
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	mso-outline-level:2;
	font-size:16.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Times New Roman";}
h3
	{mso-style-next:Normal;
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	mso-outline-level:3;
	font-size:14.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Times New Roman";}
h4
	{mso-style-next:Normal;
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	mso-outline-level:4;
	font-size:14.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Times New Roman";
	text-decoration:underline;
	text-underline:single;}
h5
	{mso-style-next:Normal;
	margin:0in;
	margin-bottom:.0001pt;
	mso-pagination:widow-orphan;
	mso-outline-level:5;
	font-size:16.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Times New Roman";
	text-decoration:underline;
	text-underline:single;}
h6
	{mso-style-next:Normal;
	margin:0in;
	margin-bottom:.0001pt;
	mso-line-height-alt:12.0pt;
	mso-pagination:widow-orphan;
	mso-outline-level:6;
	font-size:14.0pt;
	mso-bidi-font-size:12.0pt;
	font-family:"Times New Roman";
	color:#333399;
	text-decoration:underline;
	text-underline:single;}
@page Section1
	{size:8.5in 11.0in;
	margin:1.0in 1.25in 1.0in 1.25in;
	mso-header-margin:.5in;
	mso-footer-margin:.5in;
	mso-paper-source:0;}
div.Section1
	{page:Section1;}
-->
</style>
<xml>
 <o:shapedefaults v:ext="edit" spidmax="1027"/>
</xml><xml>
 <o:shapelayout v:ext="edit">
 <o:idmap v:ext="edit" data="1"/>
 </o:shapelayout></xml>
</head>
<body lang=EN-US style='tab-interval:.5in'>
<div class=Section1>
<h2 style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:green'>&nbsp;<o:p></o:p></span></h2>
<h2 style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:green'>Customizing the Delphi IDE<o:p></o:p></span></h2>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
tutorial shows you how to customize several different aspects of the Delphi IDE
using the windows registry.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>The
program regedit.exe, which allows you to edit the windows registry, is located
in “C:\Windows”</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>All
of the keys used to edit the Delphi IDE are in the
“HKEY_CURRENT_USER\Software\Borland\(Version Number)”</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>Most
of these keys are available on previous versions of Delphi but I based this
article on Delphi 6 so depending on the version of Delphi that you have some of
these keys may not be in the registry.<span style="mso-spacerun: yes"> 
</span>Also the changes to the Delphi IDE don’t take place until you exit and
restart Delphi.</p>
<h4 style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:#333399'>Code Insight<o:p></o:p></span></h4>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>All
of the keys in this section are in the “(Version Number)\Code Insight” key<b><u><span
style='font-size:16.0pt;mso-bidi-font-size:12.0pt'><o:p></o:p></span></u></b></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>In
this key there are a lot of different keys that allow you to customize the
colors of different parts of the code completion popup list.<span
style="mso-spacerun: yes">  </span>All the key’s names end in color.<span
style="mso-spacerun: yes">  </span>Just set the key to a color constant that is
used in Delphi.<span style="mso-spacerun: yes">   </span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>CodeCompleteAutoParens<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if when you press space or enter on a selection in the code
completion list it will automatically insert the opening and closing brackets
or not.<span style="mso-spacerun: yes">  </span>Set the key to False to have
the code completion not insert the brackets.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>CodeCompleteHeight, CodeCompleteWidth<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>These
two keys change the default height and width for the code completion list.<span
style="mso-spacerun: yes">  </span>Just set the two keys to either a
hexadecimal value or a decimal value.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Scope Sort<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the code completion list appears in scope order or in alphabetical
order.<span style="mso-spacerun: yes">  </span>The default is True so set the
key to False to have the code completion list appear in alphabetical order.</p>
<h4 style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:navy'>Component Palette<o:p></o:p></span></h4>
<h1 style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon;font-weight:normal'><![if !supportEmptyParas]>&nbsp;<![endif]><o:p></o:p></span></h1>
<h1 style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon;font-weight:normal'>AutoPaletteScroll<o:p></o:p></span></h1>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>In
the (Version Number) key add a new key called “Extras” in that folder you add a
new string key and name that key “AutoPaletteScroll”.<span style="mso-spacerun:
yes">  </span>Set the key to True and whenever your mouse is over an arrow that
scrolls through components it will scroll automatically, you don’t have to
click the arrow.<span style="mso-spacerun: yes">  </span>This is not the arrow
that scrolls through the categories of components. </p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>AutoPaletteSelect<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>In
the same Extras key as in the above example you can add another string key
called “AutoPaletteScroll”.<span style="mso-spacerun: yes">  </span>Set this
key to True and whenever your mouse is over a component category on the
component palette like Standard or Additional it will automatically select the
group and you don’t have to click the mouse button.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>SortPaletteTabs<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>In
the “(Version Number)\Main Window” key there is a key called
“SortPaletteTabs”.<span style="mso-spacerun: yes">  </span>This key determines
if the right click menu of the component palette is in alphabetical sort or in
the order they appear on the palette.<span style="mso-spacerun: yes"> 
</span>Set the key to False to set the order to the order it appears on the
palette.</p>
<h6 style='line-height:12.0pt;mso-line-height-rule:exactly'>&nbsp;Object
Inspector</h6>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>All
of the keys in this section are in the “(Version Number)\Object Inspector” key</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>In
this key there are a whole lot of different keys that allow you to customize
the colors of different parts of the object inspector.<span
style="mso-spacerun: yes">  </span>All the key’s names end in color.<span
style="mso-spacerun: yes">  </span>Just set the key to a color constant that is
used in Delphi.<span style="mso-spacerun: yes">  </span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Show Classname in Instance List<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the classname is displayed in the object inspector drop down
list.<span style="mso-spacerun: yes">  </span>Set the key to False to have the
pull down list not display the classnames.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Show Grid Lines<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the grid lines show up in the object inspector.<span
style="mso-spacerun: yes">  </span>Set the key to False to have the grid lines
not visible.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Show Instance List<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the drop down list at the top of the object inspector is
displayed in the object inspector.<span style="mso-spacerun: yes">  </span>Set
the key to False to have the drop down list not visible.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Show Status Bar<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the status bar at the bottom of the object inspector is
displayed.<span style="mso-spacerun: yes">  </span>Set the key to False to have
the status bar not visible.</p>
<h6 style='line-height:12.0pt;mso-line-height-rule:exactly'>Window Menu</h6>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>All
of the keys in this section are in the “(Version Number)\Main Window” key</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Show Window Menu<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the Windows menu shows up in the Delphi IDE.<span
style="mso-spacerun: yes">  </span>Set the key to False to make the windows
menu not visible.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'><span
style='color:maroon'>Sort Window Menu<o:p></o:p></span></p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>This
key determines if the windows inside of the windows menu appear in alphabetical
order or in the order of most used.<span style="mso-spacerun: yes">  </span>Set
the key to False to make the windows appear in the order of most used.</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>&nbsp;</p>
<p class=MsoNormal style='line-height:12.0pt;mso-line-height-rule:exactly'>These
are just a few of the keys in the registry that can customize the Delphi IDE.<span
style="mso-spacerun: yes">  </span>Go ahead and explore all of the other keys
in the Delphi registry.<span style="mso-spacerun: yes">  </span>Some of the
keys are not there automatically.<span style="mso-spacerun: yes">  </span>You
have to add the key and set the value.<span style="mso-spacerun: yes"> 
</span>So keep on exploring, there are a lot of things that you can do with the
windows registry.</p>
</div>
</body>
</html>
```


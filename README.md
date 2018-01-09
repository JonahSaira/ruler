ruler
=====
Simple on-screen pixel ruler.

<br />
<a href="http://www.softpedia.com/progDownload/Ruler-andrijac-Download-256095.html"><img alt="download page" src="https://raw.githubusercontent.com/andrijac/ruler/master/img/softpedia_download_large_shadow.png" /></a>

<img src="https://github.com/andrijac/ruler/raw/master/img/ruler.gif">

Binaries:
https://github.com/andrijac/ruler/tree/master/Bin

Ruler is fork of small utility application originally developed by Jeff Key:

- http://ruler.codeplex.com/ :floppy_disk:
- ~~http://weblogs.asp.net/jkey/archive/2004/09/01/224433.aspx~~ :skull:
- ~~http://www.sliver.com/dotnet/ruler/~~ :skull:

Support for .NET 2.0 is kept. :thumbsup:

**<a name="newfeatures" href="https://github.com/andrijac/ruler/blob/master/NewFeatures.md">Added features</a>**

### Ruler shortcuts:

- **Space** and **Double click**: will toggle direction of Ruler. 
- **Arrow keys**: move Ruler

### Command line parameters (optional):
In current implementation, you can either not use parameters (just start app) or use all parameters (you cannot used parameters selectively).
Parameters are intended to be used internally to duplicate Ruler by passing configuration to new instance, but you can use them to save prefered Ruler configuration too
The way parameters are passed to program and parsed might change in future.

`ruler [Width:int] [Height:int] [IsVertical:bool] [Opacity:double] [ShowToolTip:bool] [IsLocked:bool] [TopMost:bool]`

Example:
`ruler 100 50 false 0.6 true false true`

*Gifs are made using LICEcap http://www.cockos.com/licecap/*
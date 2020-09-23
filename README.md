<div align="center">

## Titlebarless window


</div>

### Description

This code will make it possible to open an url, in a window without titlebar. You can set the url,name,witdh, height, top end left of the window.
 
### More Info
 
url,name,witdh, height, top end left

a reference to the created window object


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[MMeijer](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mmeijer.md)
**Level**          |Intermediate
**User Rating**    |4.8 (19 globes from 4 users)
**Compatibility**  |
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__2-68.md)
**World**          |[Java](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/java.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mmeijer-titlebarless-window__2-3090/archive/master.zip)





### Source Code

```
<html>
<head>
<title></title>
</head>
<body>
<script type="text/javascript">
<!--
function openFramelessWindow(sUrl,sName,lWidth,lHeight,lLeft,lTop)
{
	var objWin = window.open('',sName,'fullscreen=1');
	objWin.focus();
	objWin.resizeTo(lWidth,lHeight);
	objWin.moveTo(lLeft,lTop);
	objWin.location.href=sUrl;
	return (objWin);
}
//-->
</script>
<input type="button" onclick="openFramelessWindow('http://www.microsoft.com','test',200,200,0,300);" value="openFrameless()" />
</body>
</hmtl>
```



Visual Studio打开文件不显示内容(显示空白背景)
解决方式两种，1不灵就用2，都不灵那就...
首先关闭所有VS.
第一种：清空目录 ComponentModelCache 和 MEFCacheBackup 
	目录大概位置 %LocalAppData%\Microsoft\VisualStudio   (AppData\Local\Microsoft\VisualStudio\16.0_e8f9cf68\MEFCacheBackup)
第二种：字体问题导致  更换字体
	Tools -> Options-> Environment -> Font and Colors
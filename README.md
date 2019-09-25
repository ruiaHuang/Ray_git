@font-face {
	font-family: 'lato';
	src: url(./font/Lato-Light.ttf);
}
@font-face {
	font-family: "webfontSourceHanSansSC";
	src: url(./font/SourceHanSansCN-Light.ttf);
}






font-family: "lato", "SourceHanSansSC-Light", "Source-Han-Light","Source Han Sans CN","webfontSourceHanSansSC";

font-family: "lato", "SourceHanSansSC-Light","Source-Han-Light","Source Han Sans CN","SourceHanSansCN-Light","webfontSourceHanSansSC" !important








引用
body{
    font-family: "lato", "SourceHanSansSC-Light","Source-Han-Light","Source Han Sans CN","SourceHanSansCN-Light","webfontSourceHanSansSC" !important
}

/ lato 字体只有数字和英文,所以汉字就默认使用下面的字体(思源字体)

/ "SourceHanSansSC-Light","Source-Han-Light","Source Han Sans CN","SourceHanSansCN-Light" 
/ 这个是思源字体的不同写法，为了兼容不同浏览器可以识别该字体

/ "webfontSourceHanSansSC" 这个就比较厉害了。  是上面字体包的引用。
如果前面的字体就没找到，就下载这个字体使用。




@font-face {
  font-family: "SourceHanSansCN-Light";
  src: url("../font/SourceHanSansCN-Light.otf"),
    url("../font/SourceHanSansCN-Light.ttf");
  font-family: "SourceHanSansCN-Normal";
  src: url("../font/SourceHanSansCN-Normal.otf");
  font-family: "SourceHanSansCN-Regular";
  src: url("../font/SourceHanSansCN-Regular.otf");

  font-family: "Trump";
  src: url("../font/trumpgothiceast_bold-webfont.eot");
  src: url("../font/trumpgothiceast_bold-webfont.eot?#iefix")
      format("embedded-opentype"),
    url("../font/trumpgothiceast_bold-webfont.woff2") format("woff2"),
    url("../font/trumpgothiceast_bold-webfont.woff") format("woff"),
    url("../font/trumpgothiceast_bold-webfont.ttf") format("truetype"),
    url("../font/trumpgothiceast_bold-webfont.svg#trumpgothiceast_boldbold")
      format("svg");
}
@font-face {
	font-family: 'lato';
	src: url(./font/Lato-Light.ttf);
}
@font-face {
	font-family: "webfontSourceHanSansSC";
	src: url(./font/SourceHanSansCN-Light.ttf);
}















font-family: "lato", "SourceHanSansSC-Light", "Source-Han-Light","Source Han Sans CN","webfontSourceHanSansSC", Arial, sans-serif;
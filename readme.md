Thanks for [fir.im](http://fir.im)

This shell will upload .ipa to [fir.im](http://fir.im) and others can install from it.

#Configuration easily.

!["xcode"](http://www.minroad.com/wp-content/uploads/2013/11/a.png)

###Copy all code from `runscript.shell` to Xcode Run Script.

1. change `ad_hoc` to your "Build Configuration" name.

		if [ "${CONFIGURATION}" = "ad_hoc" ]; then
	
2. change `pathtoartwork` to your artwork or icon path.
   
		pathtoartwork="iFurniture/icon/120.png"
	

That's all.  It will alert url when you build use Build Configuration = "ad_hoc".

!["alert"](http://www.minroad.com/wp-content/uploads/2013/11/b.png)

If have any question, let me know.

Sina Weibo: [@qdvictory](http://weibo.com/qdvictory)


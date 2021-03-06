<div class="article"><h1 ><font color="#AAA">class </font>VideoSignalWidget</h1></div>

~~~java
 class VideoSignalWidget extends FrameLayoutWidget 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.ux.widget</td></tr><tr valign="top"><td width=15%><font color="#999"><i>Inherits From:</i></td><td width=85%><font color="#999"><code>FrameLayoutWidget</code></td></tr></table></html>



##### Display:

![uilib_image](/assets/VIDEO.gif)<br style="clear:both" />

<font color="#666">5 vertical bars represents the current Video signal strength.



##### Usage:



<font color="#666">Preferred Aspect Ratio: 19:11.



##### Class Members:

<div class="api-row" id="videosignalwidget_onvideosignalstrengthchange"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#videosignalwidget_onvideosignalstrengthchange_inline">onVideoSignalStrengthChange</a></div></div><div class="inline-doc" id="videosignalwidget_onvideosignalstrengthchange_inline"

><div class="article"><h6 ><font color="#AAA">method </font>onVideoSignalStrengthChange</h6></div>

~~~java
@MainThread
@Keep
 void onVideoSignalStrengthChange(@IntRange(from = 0, to = 100) int signalValue) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.ux.widget</td></tr></table></html>



##### Description:



<font color="#666">Triggers when the value of the video signal strength changes.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">@IntRange(from = 0, to = 100) int <font color="#000">signalValue</td><td><font color="#666"><i>0 - 100; 0 means no signal, 100 means the best signal strength;</i></td></tr></table></html></div>



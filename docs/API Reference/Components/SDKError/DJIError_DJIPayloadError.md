<div class="article"><h1 ><font color="#AAA">class </font>DJIPayloadError</h1></div>

~~~java
 class DJIPayloadError extends DJIError 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr><tr valign="top"><td width=15%><font color="#999"><i>Inherits From:</i></td><td width=85%><font color="#999"><code><a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></code></td></tr></table></html>



##### Description:



<font color="#666">Errors related to the payload.



##### Class Members:



#### Members

<div class="api-row" id="djierror_djipayloaderror_invalidformatofwidgetconfiguration"><div class="api-col left">General</div><div class="api-col middle" style="color:#AAA">final</div><div class="api-col right"><a class="trigger" href="#djierror_djipayloaderror_invalidformatofwidgetconfiguration_inline">INVALID_FORMAT_OF_WIDGET_CONFIGURATION</a></div></div><div class="inline-doc" id="djierror_djipayloaderror_invalidformatofwidgetconfiguration_inline"

><div class="article"><h6 ><font color="#AAA">final </font>INVALID_FORMAT_OF_WIDGET_CONFIGURATION</h6></div>

~~~java
 static final DJIError INVALID_FORMAT_OF_WIDGET_CONFIGURATION = new DJIError("The format of widget configuration is invalid.")
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">The format of widget configuration is invalid.

</div>

<div class="api-row" id="djierror_djipayloaderror_commandcannotbeexecutedincurrentmode"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">final</div><div class="api-col right"><a class="trigger" href="#djierror_djipayloaderror_commandcannotbeexecutedincurrentmode_inline">COMMAND_CAN_NOT_BE_EXECUTED_IN_CURRENT_MODE</a></div></div><div class="inline-doc" id="djierror_djipayloaderror_commandcannotbeexecutedincurrentmode_inline"

><div class="article"><h6 ><font color="#AAA">final </font>COMMAND_CAN_NOT_BE_EXECUTED_IN_CURRENT_MODE</h6></div>

~~~java
 static final DJIError COMMAND_CAN_NOT_BE_EXECUTED_IN_CURRENT_MODE = new DJIError("The command is not supported by the current payload mode.")
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">The command cannot be executed in current payload mode. See <code><a href="/Components/Payload/DJIPayload.html#djipayload_djipayloadproductphase">PayloadProductPhase</a></code>.

</div>



##### Inherited Methods:

<div class="api-row" id="djierror_djisdkflighthuberrorforcode"><div class="api-col left">dji.common.error.DJIError</div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_djisdkflighthuberrorforcode_inline">getDJIError</a></div></div><div class="inline-doc" id="djierror_djisdkflighthuberrorforcode_inline"

><div class="article"><h6 ><font color="#AAA">method </font>getDJIError</h6></div>

~~~java
 static DJIError getDJIError(int errorCode) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">Returns the specific error in the <code><a href="/Components/SDKError/DJIError_DJISDKFlightHubError.html#djierror_djisdkflighthuberror">DJIFlightHubError</a></code> according to the error code.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">int <font color="#000">errorCode</td><td><font color="#666"><i>errorCode for <code><a href="/Components/SDKError/DJIError_DJISDKFlightHubError.html#djierror_djisdkflighthuberror">DJIFlightHubError</a></code>.</i></td></tr></table></html>

##### Return:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">static <a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></td><td><font color="#666"><i>An NSError object initialized with errorCode. If the errorCode was 0, returns nil.</i></td></tr></table></html></div>

<div class="api-row" id="djierror_djiutmisserrorforcodewitherrorcode"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_djiutmisserrorforcodewitherrorcode_inline">getDJIError</a></div></div><div class="inline-doc" id="djierror_djiutmisserrorforcodewitherrorcode_inline"

><div class="article"><h6 ><font color="#AAA">method </font>getDJIError</h6></div>

~~~java
 static DJIError getDJIError(int errorCode) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.sdk.utmiss</td></tr></table></html>



##### Description:



<font color="#666">Get DJIUTMISSError.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">int <font color="#000">errorCode</td><td><font color="#666"><i>An int value of error code.</i></td></tr></table></html>

##### Return:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">static <a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></td><td><font color="#666"><i>An object of <code><a href="/Components/SDKError/DJIError.html#djierror">DJIError</a></code>.</i></td></tr></table></html></div>

<div class="api-row" id="djierror_getdescription"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_getdescription_inline">getDescription</a></div></div><div class="inline-doc" id="djierror_getdescription_inline"

><div class="article"><h6 ><font color="#AAA">method </font>getDescription</h6></div>

~~~java
 String getDescription() 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">Returns the description of the error code.



##### Return:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">String</td><td><font color="#666"><i>The description of the error code.</i></td></tr></table></html></div>

<div class="api-row" id="djierror_setdescription"><div class="api-col left"></div><div class="api-col middle" style="color:#AAA">method</div><div class="api-col right"><a class="trigger" href="#djierror_setdescription_inline">setDescription</a></div></div><div class="inline-doc" id="djierror_setdescription_inline"

><div class="article"><h6 ><font color="#AAA">method </font>setDescription</h6></div>

~~~java
 void setDescription(String desc) 
~~~

<html><table class="table-supportedby"><tr valign="top"><td width=15%><font color="#999"><i>Package:</i></td><td width=85%><font color="#999">dji.common.error</td></tr></table></html>



##### Description:



<font color="#666">Sets the description for the error code.



##### Input Parameters:

<html><table class="table-inline-parameters"><tr valign="top"><td><font color="#70BF41">String <font color="#000">desc</td><td><font color="#666"><i>Description string.</i></td></tr></table></html></div>



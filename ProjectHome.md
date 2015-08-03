

&lt;IMG src="http://img97.imageshack.us/img97/1817/logoia.gif" height="14" width="14"&gt;

 

&lt;B&gt;



&lt;FONT size="3"&gt;

REST Client

&lt;/FONT&gt;



&lt;/B&gt;

 Tool

<a href='http://www.softpedia.com/get/Programming/Other-Programming-Files/RESTClient-Tool.shtml'>
<br>
<br>
<IMG src="http://www.softpedia.com/_img/softpedia_100_clean.png" align="right"><br>
<br>
<br>
<br>
<br>
<h4>Introduction</h4>
Feature rich rest client for developers to play with RESTful web services. It can be used to test any URL for following HTTP methods<br>
<ul><li>GET<br>
</li><li>POST<br>
</li><li>PUT<br>
</li><li>DELETE<br>
</li><li>HEAD<br>
</li><li>OPTIONS<br>
</li><li>TRACE</li></ul>

<h4>Main Features</h4>
<ol><li>Simultaneous views of request, response and browser.<br>
</li><li>Post raw data or file, text content or binary.<br>
</li><li>Post params in either body or as part of URL (twitter style).<br>
</li><li>Post multipart form data with same ease as of normal post.<br>
</li><li>Handle response equally well even if it is binary e.g. image, pdf etc. No gibberish characters anymore.<br>
</li><li>Play with headers, params and request body.<br>
</li><li>Indented XML/JSON views for better readability.</li></ol>

<h4>Min. Requirement</h4>
<ul><li>Java 1.6<br>
</li><li>Eclipse 3.4 (for plugin)<br>
</li><li>HTTP 1.1 compatibility</li></ul>

<h4>Downloads</h4>
<table><thead><th> <b>OS</b> </th><th> <b>Exe</b> </th><th> <b>Executable Jar</b> </th><th> <b>Eclipse Plugin Jar</b> </th><th> <b>Plugin Update Site</b> </th></thead><tbody>
<tr><td> Windows   </td><td> <a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/downloads/detail?name=rc-tool_1.0.3.exe'>exe file</a> </td><td> <a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/downloads/detail?name=rc-tool-SA_win32x86_1.0.3.jar'>executable jar</a> </td><td> <a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/downloads/detail?name=code.google.restclient.tool_1.0.3.jar'>plugin jar</a> </td><td> <a href='https://svn.codespot.com/a/eclipselabs.org/restclient-tool/trunk/eclipse/update/'>https://svn.codespot.com/a/eclipselabs.org/restclient-tool/trunk/eclipse/update/</a> </td></tr>
<tr><td> Mac       </td><td> executable </td><td> executable jar        </td><td> <a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/downloads/detail?name=code.google.restclient.tool_1.0.3.jar'>plugin jar</a> </td><td> <a href='https://svn.codespot.com/a/eclipselabs.org/restclient-tool/trunk/eclipse/update/'>https://svn.codespot.com/a/eclipselabs.org/restclient-tool/trunk/eclipse/update/</a> </td></tr>
<tr><td> Linux     </td><td> executable </td><td> executable jar        </td><td> <a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/downloads/detail?name=code.google.restclient.tool_1.0.3.jar'>plugin jar</a> </td><td> <a href='https://svn.codespot.com/a/eclipselabs.org/restclient-tool/trunk/eclipse/update/'>https://svn.codespot.com/a/eclipselabs.org/restclient-tool/trunk/eclipse/update/</a> </td></tr></tbody></table>

After installing eclipse plugin it can be found @ Window -> Show View -> Other -> REST Client -> <code>RestClient Tool</code>
<br>
<br>
<BR><br>
<br>
<br>
<br>
<BR><br>
<br>
<br>
Note:- It warns about unsigned jar while running for the first time. This is because standard SWT distribution jar is bundled with OS specific libraries to interact with native look and feel widgets of OS i.e. it has few DLLs for windows. For more info visit <a href='http://www.eclipse.org/swt'>http://www.eclipse.org/swt</a>

<h4>SSL Handling</h4>
All SSL validations are disabled by default. User can customize/override default behavior.<br>
Please go through <a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/source/browse/trunk/docs/ssl-handling.txt'>documentation</a>.<br>
<br>
<br>
<h4>Screen Shots</h4>
XML Response<br>
<img src='http://img175.imageshack.us/img175/7149/screenshot1fiz.jpg' />

HTML Response <code>[Google Book Search]</code>
<img src='http://img175.imageshack.us/img175/8761/screenshot2p.jpg' />

Image Response <code>[Google Static Map]</code>
<img src='http://img820.imageshack.us/img820/7565/screenshot3cv.jpg' />

Rest Client as Eclipse Plugin<br>
<img src='http://img256.imageshack.us/img256/2269/screenshot4jb.jpg' />

<h3>Releases</h3>

<h4>Release 1.0.3 - September 12, 2011</h4>
Issue Fixed:<br>
<a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/issues/detail?id=8'>http://code.google.com/a/eclipselabs.org/p/restclient-tool/issues/detail?id=8</a>

Fix includes enhancements for SSL Handling.<br>
<br>
Documentation:<br>
<br>
<br>
<BR><br>
<br>
<br>
<a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/source/browse/trunk/docs/ssl-handling.txt'>http://code.google.com/a/eclipselabs.org/p/restclient-tool/source/browse/trunk/docs/ssl-handling.txt</a>
<br>
<br>
<BR><br>
<br>
<br>
<a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/source/browse/trunk/standalone/conf/rest-client_override.properties'>http://code.google.com/a/eclipselabs.org/p/restclient-tool/source/browse/trunk/standalone/conf/rest-client_override.properties</a>


<h4>Release 1.0.2 - July 22, 2010</h4>

List of Fixes for Issues:<br>
<ol><li>New lines (CR) get removed from text file while submitting it as POST body.<br>
</li><li>Response body should be displayed as is if no indentation.<br>
</li><li>Content-Type header goes blank when posting any file.<br>
</li><li>Display body part of request pane is not encoded (with UTF-8) while actually client submits encoded params body string. It is misleading.<br>
</li><li>Request pane doesn't display content if request results erroneous response.<br>
</li><li>Request pane doesn't display actual post body message format if request is multipart/form-data.<br>
</li><li>Add OPTIONS and TRACE HTTP methods.<br>
</li><li>Do not verify host names in SSL certificate. Allow all host names.</li></ol>

Issue List:<br>
<ol><li><a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/issues/detail?id=1'>http://code.google.com/a/eclipselabs.org/p/restclient-tool/issues/detail?id=1</a>
</li><li><a href='http://code.google.com/a/eclipselabs.org/p/restclient-tool/issues/detail?id=2'>http://code.google.com/a/eclipselabs.org/p/restclient-tool/issues/detail?id=2</a></li></ol>

<h4>Release 1.0.1 - July 6, 2010</h4>
Added indentation to XML and JSON displayed in request and response pane
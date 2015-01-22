<h2>JvmQueue Small HTML Components, Presentation Only</h2>
 
<p>These are small components which can be slipped into any HTML page</p>

<h3>HTML</h3>
<p>Each HTML file uses two CSS files</p>

<h3>CSS</h3>
<p>One CSS file has the same name as the HTML file</p>
<p>The other CSS file has the same name as the above CSS file, but has Ie as a suffix</p>

<h3>Stategies and Techniques</h3>
 <ul>
	<li>Grunt used to ensure CSS conforms to standards, LINT</li>
	<li>Conditional comments for IE tweaks</li>
	<li>HTML5 Shim allows IE to render HTML5 tags</li>
	<li>CSS tiny classes to emulate small JavaScript functions</li>
	<li>A single CSS rule does one thing, and one thing well</li>
	<li>Removing or adding a class to an HTML tag allows adding a single presentation unit or removing it</li>
	<li>Ie. Adding textAlignLeft to an HTML tag causes text to align left.</li>
</ul>
<h4>Fundemental Architecture</h4>
<dl>
	<h3>site</h3>
	<dd>html resources</dd>
	<dt>styles</dt>
	<dd>CSS files</dd>
	<dt>images</dt>
	<dd>image resources, sprites</dd>	
</dl>
<h5>Repository: https://github.com/jvmqueue/smallHtmlComponents/tree/master/</h5>




 

 

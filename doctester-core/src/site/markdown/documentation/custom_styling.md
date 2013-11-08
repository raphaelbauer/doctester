## Customizing the html generated by DocTester via css

You can easily brand the css generated by DocTester. All css of 
DocTester is built with Bootstrap. You can add your branding by adding
a file <code>/src/test/resources/org/doctester/custom_doctester_stylesheet.css</code>
to your project.

For instance the following css adds a logo and changes the color of the headline
in the header:

<pre class="prettyprint languague-css">
body {
	background-repeat: no-repeat;
	background-image: url(data:image/png;base64,iVC);
	background-attachment: fixed;
	background-position: 10px 55px;
}

a.navbar-brand {
	color: #F39300 !important; 
}
</pre>
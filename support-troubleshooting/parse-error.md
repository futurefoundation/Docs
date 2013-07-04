# Parse Error #

The reason why this error shows up is because you have one or more errors in your custom CSS/LESS CSS.

The error will look similar to this:

<pre>
"PageLines Custom LESS/CSS error.
parse error: failed at `padding: 10px ` line: X"
</pre>

To resolve this error, you're going to need to review your custom CSS, LESS CSS for any errors such as a missing `{ `, `}`, `;` or even spelling mistakes in your CSS properties.

We have provided a basic example below, this minor error can trigger a Parse Error.

~~~ .css
.example {
	color: 14px
	padding: 20px 0;
	margin: 15px 0;
}
~~~

As you can see above, the `color: 14px` has no semi-colon `;` that is required to separate each decalaration. To resolve this example issue above, simply locate the CSS in your custom code and add the semi-colon, save the changes and refresh, the parse error should now be resolved.
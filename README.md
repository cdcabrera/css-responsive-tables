<h1>CSS.Responsive Tables</h1>
<p>
    Quick bit of CSS &amp; HTML to get you going with a responsive table layout. The two main goals were to avoid using client-side scripting and to streamline.
</p>

<h2>How it works</h2>
<p>
    Makes use of a CSS media query up to a width you desire. Scale your browser window down to the appropriate size for activation.
</p>
<p>
    In my personal projects I seem to be able to get away with a standard table view somewhere around 500 to 549px/34.3125em.
    The media query has the added benefit of weeding out early versions of IE.
</p>



<h2>Browser compatibility</h2>
<p>
    Works in Firefox, Chrome, Opera, and Safari. IE-9 is fine as well. Technically IE-8 can handle the responsive format,
    but due to media queries and the lack of a shim 8 gets lumped into IE-7 territory. And IE-7-, well, those users receive the original table.
</p>

<h2>License</h2>
<p>
    Ignoring a license on this project since I'm unsure where the pattern originated (feel free to help me update any kudos).
    But to give credit to my resource... a friend of mine,
    <a href="https://github.com/jpstreich">jpstreich</a>, introduced me to this concept and the original code around late 2011 to
    early 2012, on a collaborative research project.
</p>
<p>
    I did include <a href="http://necolas.github.com/normalize.css">Normalize.css</a> and the box model tweak from
    <a href="http://www.paulirish.com/2012/box-sizing-border-box-ftw/">Paul Irish</a> for general formatting purposes.
</p>

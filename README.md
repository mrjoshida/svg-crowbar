#SVG Crowbar

A quick hack to SVG Crowbar that allows it to pull SVGs from Code.org Blockly apps. In Chrome only, drag this link <a href="javascript:javascript: (function () %7B var e %3D document.createElement(%27script%27)%3B e.setAttribute(%27src%27, %27https://rawgit.com/mrjoshida/svg-crowbar/gh-pages/svg-crowbar-blockly.js%27)%3B e.setAttribute(%27class%27, %27svg-crowbar%27)%3B document.body.appendChild(e)%3B %7D)()%3B">SVG Crowbar Blockly</a> to your bookmarks bar. On a blockly puzzle, click the SVG Crowbar Blockly button. This will populate your page with download buttons for all of the SVG elements. To download the block SVG, click on the '.blocklySvg' button. Note: this doesn't pull down any .pngs associated with the blocks (such as arrows and icons in the Course 1).

SVG Crowbar Chrome-specific bookmarklet that extracts SVG nodes and accompanying styles from an HTML document and downloads them as an SVG file—A file which you could open and edit in Adobe Illustrator, for instance. Because SVGs are resolution independent, it’s great for when you want to use web technologies to create documents that are meant to be printed (like, maybe on newsprint). It was created with [d3.js](http://d3js.org) in mind, but it should work fine with any SVG.

[Project page](http://nytimes.github.com/svg-crowbar/)

# HW3 - Standards Based CSS Responsive Web Design - Site Build Out Phase 2

## Assignment Description

<h2>Learning Outcomes</h2>
<ul>
<li>The students will begin to master the use of Cascading Style Sheets for designing the presentation layer of web sites and applications in a layered fashion.</li>
<li>The students will explore CSS syntax including Flexbox, CSS Grid, Media Queries, CSS variables, CSS animations, and a variety of common CSS properties. The focus will be on standards based CSS, but there will be opportunity to explore proprietary features such as the need for vendor-prefixes.</li>
<li>Presentation technologies such as custom fonts and images will also be utilized to expose students to the syntax, but emphasis will be placed on performance focused use of such technology which may include correct HTML usage (picture element and srcset), image format choice and optimization, and font optimization strategies.</li>
<li>The students will explore Responsive Web Design (RWD) and how to execute a look that should allow for mobile, tablet, and desktop forms. Upon conclusion the students should be able to discuss the challenges and benefits of this design pattern.<br><br></li>
</ul>

<h2><br>Part 1 - Standards Based CSS Use (30 pts + 4 EC points)</h2>
<p>To demonstrate CSS knowledge, use the technology to style your HTML pages from the previous homework (HW2). You may need to add classes, ids, and restructure your elements in order to do this task. That is fine. However, do not convert your site to a &lt;div&gt; dominant design - this can result in significant point loss.</p>
<p>To layout your page you MUST use <span style="background-color: #e6b8e9;">CSS Flexbox and/or CSS Grid</span> <strong>(10 pts)</strong>. You do not have to account for ancient browsers so assume Edge Chromium, Chrome, latest Safari and latest Firefox level access.</p>
<p>To style your page, use whichever CSS properties you like, but you must show demonstration of these <span style="background-color: #e6b8e9;">intermediate or advanced ideas</span>:</p>
<ul>
<li>CSS Variables (with fallbacks while using variables) used in at least two different styling contexts <strong>(2 pts)</strong></li>
<li>Custom Fonts (also with fallback to a serif or sans serif font in case of failure). For full credit code must show signs of the font being imported, <span>you CANNOT rely on your browser already having your font of choice.<strong> (2 pts)</strong></span></li>
<li>Relative units including but not limited to em, rem, %. <strong>(3 pts)</strong></li>
<li>Dynamic viewport units including but not limited to dvw, dvh.&nbsp; <strong>(2 pts)</strong></li>
<li>CSS Animations, Transitions and Transforms <strong>(3 pts)</strong></li>
<li>Media Queries (See Part 3 - Responsive Web Design)</li>
<li>Nested and Scoped CSS <strong>(4 pts)</strong></li>
<li>Any new CSS-related feature from Baseline 2024 or Baseline 2025 (see <a href="https://web.dev/baseline/2024" target="_blank">https://web.dev/baseline/2024</a>). For full credit, include in your submission a 2+ sentence-long description of the feature you chose to implement (light-dark()). <strong>(2 pts for correct implementation of the feature, 2 pts for the description)</strong></li>
</ul>
<h3>Extra Credit:&nbsp;</h3>
<p>Some of the following might not have the maximum adoption (currently, most are hovering around 87-88% adoption) but are worth trying out:</p>
<ul>
<li>Use wider gamut color with color() and color-mix() <strong>(2 pts)</strong></li>
<li>New selectors like has() <strong>(2 pts)</strong></li>
</ul>
<p><span style="background-color: #a0e0e9;">Any CSS written should be as standard as is possible.&nbsp;<br><br></span></p>
<h2>Part 2 - Image Usage (15 pts)</h2>
<p>To further enhance your page presentation you should use images. Our minimum threshold for image usage is "a reasonable amount" based on your webpage content - we will take a holistic approach to this.</p>
<ul>
<li>You may use images of any form (GIF, JPEG, WebP, SVG, etc.), but make sure that the types are appropriate for the content served <strong>(6 points)</strong></li>
<li>Your images should be optimized for delivery <strong>(3 pts)&nbsp;</strong>-&nbsp;you should address delivering the appropriate size and/or type of image given the needs of responsive design discussed in the next section. The use of the <em>&lt;picture&gt;</em> tag and the <em>srcset</em> as well as corresponding aspects of media queries are excellent tools for this, so you are not sending too many bytes to small or lower-powered devices.</li>
<li>Accessibility issues with your images such as alternative text, proper use of contrast and proper use of foreground or background should be accounted for <strong>(6 pts)</strong></li>
<li>To adjust pictures with their frames we recommend using <em>object-position</em> and <em>object-fit</em> attributes.</li>
</ul>
<p>&nbsp;</p>
<h2>Part 3 - Responsive Design (10 points)</h2>
<p>To address device diversity your site should practice the principle of responsive web design. You should account for three types of form factors. Very small screen (phone), tablet or restrictive laptop, and desktop <strong>(6 pts total)</strong>. Employ appropriate pixel breakpoints based upon those factors. There may be variation of those dimensions so do a little research <em>(Note: DevTools can help simulate different screen sizes)</em></p>
<p>Make sure your CSS layouts reflow appropriately and do not require pinch, zoom, or unnecessary horizontal scroll <strong>(3 pts)</strong>. Also make sure per the previous section that images are sized appropriately per device dimension.</p>
<p>Lastly, you may see that the different devices suggest concrete interface changes (e.g.: emergence of a Hamburger menu, touch-aware layout, etc.). You need to show evidence that your design adjusts to address such things <strong>(1</strong><strong>&nbsp;pt)</strong>.</p>
<p>&nbsp;</p>
<h2>Part 4 - Aesthetics and Usability (10 pts + 5 EC)</h2>
<p>The look of the site and our ability as end users to understand what you are doing is paramount. No matter how well we do our sites functionally, if we have a poor experience, we will ultimately fail.</p>
<p>We award up to <strong>5 pts </strong>for the <span style="background-color: #e6b8e9;">aesthetics</span> and <strong>5 pts</strong>for the <span style="background-color: #e6b8e9;">usability</span> of the site. If you are simple and precise in look&nbsp; <em>(aka "minimalistic") </em>and <span style="text-decoration: underline;">obvious in navigation,</span> you will likely get most of the points, but there is inevitable subjectivity based upon the interpretation of the graders. While we have kept the amount of points very low, understand in "real life" most people would attach most of the points here. Particularly excellent jobs may receive up to 5 extra credit points at our discretion.</p>
<p>&nbsp;</p>
<h2>Restrictions and Logistic Details</h2>
<ul>
<li><span style="background-color: #a0e0e9;"><strong>All CSS must be hand authored - no frameworks like Twitter Bootstrap or Tailwind (points can be lost).</strong></span></li>
<li><strong><span style="background-color: #a0e0e9;">You may not purchase a theme or represent an existing design as your own work.</span> </strong>While you are free to use such things as inspiration, direct usage will be considered an AIP violation</li>
<li>You may use stock photography images with or without watermarks. If you use stock imagery out of courtesy, provide HTML comment situations or use a <em>&lt;cite&gt;</em> element to show us where you got the images. This is an important thing to get used to, as misuse of images online can and does resort in legal demand letters. Be aware of what you are pulling in, and think about the copyrights/licences.</li>
<li>AI Image copyright laws are sensitive around the subject, and regulations around the world are not up to date yet. If you choose to use AI images, review the copyright and usage rules of the tool of your choice.</li>
<li><span style="background-color: #a0e0e9;"><strong>You should still not be using JS in your assignment at this stage.</strong>
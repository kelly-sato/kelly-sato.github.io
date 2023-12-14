---
layout: essay
type: essay
title: "A Better Way: Bootstrap"
# All dates must be YYYY-MM-DD format!
date: 2023-10-05
published: true
labels:
  - UI Frameworks
  - Bootstrap 5
---

<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/css/bootstrap.min.css" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0/dist/js/bootstrap.bundle.min.js"></script>

<body>
<div class="container">
<div class="row d-flex justify-content-center align-items-center">
<div class="col-md-6">
<h2>Raw HTML and CSS</h2>
<p>
When I worked with HTML and CSS for the first time in ICS 314, I was underwhelmed by the result. It was a lot of work for a <em>really</em> ugly product.
</p>
<p>
Maybe it's the color combination and the blue hyperlinks, but it looks like an early 2000's website that can and will steal my personal information at the first chance it gets. What scares me more than that is <em>how much work</em> I put into it for it to come out looking like <em>that</em>. I asked myself, how was I ever going to make a beautiful UI if I was struggling to make an ugly one?
</p>
</div>
<div class="col-md-5">
<div class="text-center">
    <img width="350px" src="../img/screencapture-localhost-63342-browserhistory-index-html-2023-10-05-15_58_48.png" class="img-thumbnail"  alt="browser-history">
</div>
</div>
</div>

<div class="row pt-4">
<h2>What makes UI Frameworks so useful?</h2>

<p>
In ICS 314, the UI Framework we used is Bootstrap. Bootstrap has a grid system that allows us to create responsive rows and columns. For my purposes, it has been an absolute game changer, turning what would have been a 20 minute fight with CSS to create columns into a trivial task. It has allowed me to create clean, modern-looking UIs, such as this recreation of the <a href="https://independentenergyhawaii.com">Independent Energy</a> about page.
</p>
</div>
<div class="row d-flex justify-content-center align-items-center">
<div class="col-md-5">
<div class="p-4" style="margin-right: 10px">
    <img width="350" src="../img/ie-cropped.png" class="img-thumbnail"  alt="your-choice">
</div>
</div>
<div class="col-md-7">
<p>
However, Bootstrap is not just the grid system---it's the buttons, the navigation bar, the background images and the embedded video, too. Because Bootstrap is a collection of CSS classes, it makes building a visually appealing UI so much easier.
</p>
<p>
For this website recreation assignment, I custom made the buttons, though I really didn't have to. I wanted the button to look accurate to the actual website, though Bootstrap's <code>btn-outline-light</code> class would have made a really nice, similar looking button. No ugly, early 2000's raw HTML and CSS buttons to be found!
</p>
<div class="container pb-3 d-flex justify-content-center">
<button type="button" class="btn btn-outline-dark">This is a Bootstrap button!</button>
</div>
<p>
Though these pre-made classes for stylized elements are great, I have to emphasize that the best thing about Bootstrap is undoubtedly the grid system. It is not difficult to learn, and learning it pays off <em>fast</em>. I don't think I can ever go back to raw HTML and CSS knowing that I won't have Bootstrap's intuitive grid system in my tool belt.
</p>
</div>
</div>
<div class="row pt-2">
<h2>Bootstrap for essays</h2>
<p>
Before Bootstrap, my technical essays were plainly formatted and lacked pictures. I worried that any styling I attempted would inhibit the flow of the essay. An image would be a monolith amidst a sea of text, ugly and in the way. Now, writing this essay, I knew I wanted to include images that would relate to the text beside it. Since the images are taller than they are wide, I knew that if I didn't do some special formatting, it would be a monolith. So, immediately, I added Bootstrap's script tags and started arranging things to my liking. 
</p>
<p>
And after all that, I can confidently say this is a decently visually appealing essay! At the very least, it's more appealing than a wall of text. Bootstrap's utility is not just confined to crafting visually pleasing websites—it extends to improving the presentation of technical content, such as this essay. Its flexibility allows for the seamless integration of images, buttons, carousels, forms, and more.
</p>
<p>
As I reflect on the difference between using raw HTML/CSS and Bootstrap's framework, I realize that Bootstrap is really a tool that allows creators to communicate their design ideas more effectively and more efficiently. Whether it's building a modern website or formatting a technical essay (like this one!), Bootstrap has become an indispensable part of my toolkit, revolutionizing the way I approach design and presentation in the digital realm.
</p>
</div>
</div>
</body>
Description:  A marketing agency has asked our team to refractor their website's HTML using CSS code, without compromising the source image.

Assignment instructions are,
 to make sure that all links are functioning correctly. 
 To rework the CSS by making it more efficient, consolidating CSS selectors and properties, and organizing their semantic structure of HTML elements.

We found,
issues with the HTML and CSS: the code and inefficient use of HTML5 semantics. 
There is redundancy that can be simplied by condensing the CSS code. 

Summary of Changes,

connecting links for functionality we implemented in html,

<div id="search-engine-optimization" class="search-engine-optimization">
<div id="online-reputation-management" class="online-reputation-management">
<div id="social-media-marketing" class="social-media-marketing">

We implemented accessibility attributes in html and added, 

alt="search engine optimization"
alt="online reputation management"
alt="social media marketing"

In condensing CSS Code, we applied:

search-engine-optimization,
.online-reputation-management,
.social-media-marketing 
{
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

.search-engine-optimization img,
.online-reputation-management img,
.social-media-marketing img {
    max-height: 200px;
}
.search-engine-optimization h2,
.online-reputation-management h2,
.social-media-marketing h2 {
    margin-bottom: 20px;
    font-size: 36px;

We made use of tags changing "div" to "footer"

What I've learned:

I've learned how to connect links for functionality.

Consolidate code and make css less cluttered and more efficient.

I;ve learned to use HTML5 semantics and deploy the application to url.


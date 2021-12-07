# Bootstrap
### The official Bootstrap website describes it as:
* “The most popular HTML, CSS, and JS framework for developing responsive, mobile-first projects on the web.”

### Here’s what that means in plainer terms:
* Bootstrap is a giant collection of handy, reusable bits of code written in HTML, CSS, and JavaScript. It’s also a frontend development framework that enables developers and designers to quickly build fully responsive websites.

Essentially, Bootstrap saves you from writing lots of CSS code, giving you more time to spend on designing webpages.

### Advantages:
* Its responsive grid
    * No more spending hours coding your own grid—Bootstrap comes with its own grid system predefined.
* Its responsive images
    * Bootstrap comes with its own code for automatically resizing images based on the current screen size. Just add the .img-responsive class to your images, and the predefined CSS rules take care of the rest.
* Its components
   * Navigation bars
   * Dropdowns
   * Progress bars
   * Thumbnails

As you’ve probably noticed by now, Bootstrap is a powerful tool that allows a developer to get up and running quickly and painlessly. It makes it easy to integrate many great features that enrich a user’s interaction with the web without having to code them from scratch.

# Microformats
Designed for humans first and machines second, microformats are a set of simple, open data formats built upon existing and widely adopted standards. Instead of throwing away what works today, microformats intend to solve simpler problems first by adapting to current behaviors and usage patterns.

Microformats are:
* A way of thinking about data
* Design principles for formats
* Adapted to current behaviors and usage patterns
* Highly correlated with semantic XHTML

The microformats principles:
* Solve a specific problem
* Start as simple as possible
* Design for humans first, machines second
* Reuse building blocks from widely adopted standards
* Modularity / embeddability


# Maps
Mapy.cz is a Czech internet and mobile map application developed by Seznam.cz . All map materials show the Czech Republic , most of them also Slovakia and some types of maps cover the whole world . The many features of the application include route planner by car, public transport, bicycle, on foot and more.

API Documentation:
* https://api.mapy.cz/

# Open graph markup for Facebook
Most content is shared to Facebook as a URL, so it's important that you mark up your website with Open Graph tags to take control over how your content appears on Facebook. For your website to be shared correctly by our crawler, your server must also use the gzip and deflate encodings.

Without these Open Graph tags, the Facebook Crawler uses internal heuristics to make a best guess about the title, description, and preview image for your content. Designate this info explicitly with Open Graph tags to ensure the highest quality posts on Facebook.

Markup Example: <br>
For example, here's how to mark up an article, news story or blog post with og:type="article" and several additional properties <br>
`<meta property="og:url"                content="http://www.nytimes.com/2015 02/19/arts/international/when-great-minds-dont-think-alike.html" />`<br>
`<meta property="og:type"               content="article" />`<br>
`<meta property="og:title"              content="When Great Minds Don’t Think Alike" />`<br>
`<meta property="og:description"        content="How much does culture influence creative thinking?" />`<br>
`<meta property="og:image"              content="http://static01.nyt.com/images/2015/02/19/arts/international/19iht-btnumbers19A/19iht-btnumbers19A-facebookJumbo-v2.jpg" />`<br>

Documentation:
* https://developers.facebook.com/docs/sharing/webmasters/

# Cards markup for Twitter
Twitter card tags look similar to Open Graph tags, and are based on the same conventions as the Open Graph protocol. When using Open Graph protocol to describe data on a page, it is easy to generate a Twitter card without duplicating tags and data. When the Twitter card processor looks for tags on a page, it first checks for the Twitter-specific property, and if not present, falls back to the supported Open Graph property. This allows for both to be defined on the page independently, and minimizes the amount of duplicate markup required to describe content and experience.

Markup example: <br>
`<meta name="twitter:card" content="summary" />`<br>
`<meta name="twitter:site" content="@nytimesbits" />`<br>
`<meta name="twitter:creator" content="@nickbilton" />`<br>
`<meta property="og:url" content="http://bits.blogs.nytimes.com/2011/12/08/a-twitter-for-my-sister/" />`<br>
`<meta property="og:title" content="A Twitter for My Sister" />`<br>
`<meta property="og:description" content="In the early days, Twitter grew so quickly that it was almost impossible to add new features because engineers spent their time trying to keep the rocket ship from stalling." />`<br>
`<meta property="og:image" content="http://graphics8.nytimes.com/images/2011/12/08/technology/bits-newtwitter/bits-newtwitter-tmagArticle.jpg" />`
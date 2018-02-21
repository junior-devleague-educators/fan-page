# Fan Page

### Getting Started

1. You are tasked to build a fan page for your favorite artist.
2. Change the `title` element of your web page to "_Artist Name_ Fan Page" (replace Artist Name with the actual name of artist)
3. There are two parts of the project. The first part focuses only on HTML. The second part will focus on CSS.
4. Below is an example of what you will be working towards. Don't worry about styling for now, we will move onto that when we get into the CSS portion of class.

![alt text](https://github.com/junior-devleague-educators/fan-page/blob/master/assets/fanpage-mockup.png?raw=true 'Fan Page Wireframe')

## Part I - HTML

### The layout will have three sections:

1. Header
2. Artist Information
3. Music Video

### 1. Header

1. Create a `div` element with a `class` of "content".
2. Inside the `div` element create `nav` element with an id "nav-bar".
3. Inside of the `nav` element, create an unordered list with `ul`, within the `ul` create 2 list items with the `li` tag, each with a class of "nav-links".
4. Inside the first `li` element, create an `a` element, insert `#about-artist` in the `href` attribute and insert "About" as the content for the `a` tag.
5. Inside the second `li` element, create an `a` element, insert `#music-video` in the `href` attribute and insert "Music Videos" as the content for the `a` tag.
6. Inside of the `div` element, but outside of the `nav` element, create a `h1` element with an `id` of "header-title" and insert "_Artist Name_ Fan Page" as content for the `h1` tag (replace "Artist Name" with your favorite artist).

### 2. Artist Information

1. Create a new `div` element with a `class` of "content" and an `id` of "about-artist".
2. Inside the `div` element create another div with a class `gallery`.
3. Inside the `gallery` div create 4 `img` elements with a `class` of "artist-image". In each `img` element set the `href` to an image url link of your choice.
4. Inside the `div` element, create an `h2` element with an id of "artist-facts" and insert "Facts About _Artist Name_" (replace Artist Name with the name of the actual Artist).
5. Inside the `div` element, create an ordered list with the `ol` tag, within the ordered list create 5 list items with the `li` tag. List 1 fact about the artist per `li` tag.
6. Inside the `div` element, create an `a` tag and set the `href` to the artist's official website url, and insert "Visit Official Website" as the content for the `a` tag.

### 3. Music Video

1. Create a `div` element with a `class` of "content" and an `id` of "music-video".
2. Inside the `div` element, create an `h2` element with an id of "music-video-title" and insert "_Title of Music Video_ Video" (replace Title of Music Video with the name of the actual music video).
3. Inside the `div` element, create an `iframe` element and set the `src` to a youtube video link.

* iframe example: https://www.w3schools.com/tags/tag_iframe.asp

### Stretch Goals

When you are done with the above requirements, you may complete bonus stretch goals.

1. Add 5 additional HTML elements that you have not used on your web page.
2. Add 3 additional sections of your choosing.
3. If you created 3 additional sections, add 3 additional links to the nav section and set the href to jump to the correct section.
4. Create a table with the artist's album names and the year the album was released.

## Part II - CSS

Add the following styles in the CSS file of your project.

1. Using the class selector, change the `background-color` of the `content` class to a color of your choosing.
2. Within the `content` code block add a `margin` property and set it's value to `auto`.
3. Within the `content` code block add a `width` property and set it's value to `800px`.
4. Using the element selector, change the font size of the `ol` element to a larger font.
5. Using the class selector, change the `background-color` of the `gallery` class to a color of your choosing.
6. Within the `gallery` code block add a `text-align` property and set it's value to `center`.
7. Using the class selector, add a `width` property to the `artist-image` class and set it's value to `200px`.
8. Import a font of your choosing from google fonts. Change the font of your `body` to the font you imported from google fonts.
9. Remove the underline from all links.
10. Change the color of all links when you hover over them.
11. Change the color of a `visited` link to a different color after it's been visited.
12. Using the id selector, center the `header-title` id.
13. Center the links in your nav bar.
14. Center all header tags (h1, h2, h3, etc).
15. Add a background image to the `body` of your web page.

### Stretch Goals

1. Make all of your images the same size.
2. Import a font of your choosing from google fonts. Change the font of all header tags (h1, h2, h3, etc) to a font of your choosing.
3. Remove the bullets from your unordered list.
4. Select your ordered list and make every other line a different color.
5. Format the background image in `body` so that the `background-attachment` property is fixed and set the value of `background-repeat` so that the background does not repeat.
6. Add 5 additional style properties to any element(s) on your page.

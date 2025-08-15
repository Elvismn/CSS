# june-2025-week-3-session-2

What are CSS Selectors?

CSS selectors are patterns that tell the browser which HTML elements you want to style.

They basically "select" elements from your HTML so you can apply styles to them.

Types of Selectors + Examples
1️⃣ Universal Selector (*)

Selects all elements on the page.

Useful for applying a general style to everything.

* {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}


💡 This will make all text use Arial and remove default margins/padding.

2️⃣ Class Selector (.classname)

Selects elements with a specific class attribute.

Syntax: A dot . followed by the class name.

HTML:

<p class="highlight">This is highlighted text.</p>


CSS:

.highlight {
  color: red;
  font-weight: bold;
}


💡 Any element with class="highlight" will get red, bold text.

3️⃣ ID Selector (#idname)

Selects only one element with a specific id attribute.

Syntax: A hash # followed by the ID name.

HTML:

<h1 id="main-title">Welcome to My Website</h1>


CSS:

#main-title {
  color: blue;
  text-align: center;
}


💡 IDs are unique — you shouldn’t have more than one element with the same ID.


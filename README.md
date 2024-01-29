# CheatSheet
Reference Sheet for App Academy
<!DOCTYPE html>
<html>
    <head>
        <title>HTML Tags Cheat Sheet</title>
    </head>
    <body>
        <h1 id="top-of-page">My HTML Cheat Sheet</h1>
        <h2>Headings</h2>
        <p>
            Headings from `h1` to `h6` identify blocks and sections. Every page must have one `h1`.
        </p>

        <h2>Paragraphs
        </h2>
        <p>
            Paragraphs of text go in `p` tags.
        </p>

        <h2>Lists</h2>
        <h3>Unordered Lists</h3>
        <p>
            Unordered lists are marked with bullet points and go in `ul` tags. Each list item goes in an `li` tag.
        </p>
        <h4>Types of lists:</h4>
        <ul>
            <li>Unordered lists (`ul`)</li>
            <li>Ordered lists (`ol`)</li>
        </ul>

        <h3>Ordered Lists</h3>
        <p>
            Ordered lists are numbered and go in `ol` tags. Each list item goes in an `li` tag.
        </p>
        <h4>Poly's Problem Solving Framework</h4>
        <ol>
            <li>Understand the problem</li>
            <li>Come up with a plan</li>
            <li>Carry out the plan</li>
            <li>Go back and improve your solution</li>
        </ol>

        <h2>Anchors (i.e. links)</h2>
        <p>
            Anchor tags create links to other pages. The URL goes in the `href` attribute.
            <a href="https://duckduckgo.com">
                Go to DuckDuckGo to search for more information.
            </a>
        </p>
        <p>
            Setting `target="_blank"` will open the link in a new window. See
            <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a" target="_blank">
                MDN
            </a>
            for more details.
        </p>
        <p>
            Anchor tags can also create links to a new location on the same page. Instead of putting a URL goes in the "href" attribute, just use the "id" of the element you want to navigate to. This allows you to
            <a href="#top-of-page">
                Jump to the top of the page.
            </a>
        </p>

        <h2> Text Emphasis</h2>
            <h3>Italic</h3>
                <em>
                    The `em` element adds extra emphasis to the text within the opening and closing tags. This shows up as italic text in most browsers.
                </em>
            <h3>Bold</h3>
                <strong>
                    You can also use the `strong` element to emphasize text. This shows up as bold text in most browsers.
                </strong>

        <h2>Organizing Content with `div` and `span`</h2>
            <h3>`div`</h3>
                <p>
                    The `div` element is a block element, so each `div` will show up on a new line.
                </p>
                <div>1st div</div>
                <div>2nd div</div>
                <div>3rd div</div>
            <h3>`span`</h3>
                <p>
                    The `span` element is an inline element, so there will be no line break between each `span`.
                </p>
                <span>1st span</span>
                <span>2nd span</span>
                <span>3rd span</span>

        <h2>Breaking text using the `br` tag</h2>
        <p>
            Replace with Haiku line 1 (syllables)<br>
            Replace with Haiku line 2 (7 syllables)<br>
            Replace with Haiku line 3 (5 syllables)<br>
        </p>
    </body>
</html>

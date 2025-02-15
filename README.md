# Unescaped Angle Brackets in HTML

This repository demonstrates a common HTML error: unescaped angle brackets (&lt; and &gt;).  These characters, when used within text content without proper escaping, can interfere with the HTML parsing process, resulting in unexpected rendering or broken HTML.

## The Bug
The `bug.html` file contains HTML with unescaped angle brackets. This leads to incorrect interpretation by the browser, potentially causing parts of the text to be ignored or interpreted as HTML tags.

## The Solution
The `solution.html` file shows the corrected version of the HTML, using HTML entities (&amp;lt; and &amp;gt;) to represent the angle brackets correctly.

This example highlights the importance of proper HTML escaping to ensure accurate rendering and prevent unexpected behavior.
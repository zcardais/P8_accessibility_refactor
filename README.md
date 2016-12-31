# 3_Accessibility_Refactor

Take a set of interlinked pages that suffer from various accessibility flaws and refine and update them so they are accessible and pass an accessibility validator(s)'s automated checks and a human's check.

Font used: <https://www.google.com/fonts/specimen/Montserrat>

## Project Instructions

- Language attribute has been added to the tag on all pages

- The foreground text and background color has sufficient contrast. I removed the dark background color and replaced it with a white. I also lightened the background color of the transparent main-nav bar while darkening its text to further the contrast.

- Heading elements are used to provide hierarchical structure to page content.

- `<p>` tags with the class "heading" have been replaced by `<h2>` tags to help assist screen readers.

- Now using background image without text (concert02_no_text.jpg) and added text to the HTML to roughly match the layout. Added Montserrat font to replace Open Sans.

- TODO: Next is Add alt tags to all images and then Make sure that the decorative images in tour.html have an empty alt attribute i.e alt="".

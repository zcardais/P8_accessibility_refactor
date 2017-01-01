# 3_Accessibility_Refactor

Take a set of interlinked pages that suffer from various accessibility flaws and refine and update them so they are accessible and pass an accessibility validator(s)'s automated checks and a human's check.

Font used: <https://www.google.com/fonts/specimen/Montserrat>

## Project Instructions

### COMPLETED:

- Language attribute has been added to the tag on all pages

- The foreground text and background color has sufficient contrast. I removed the dark background color and replaced it with a white. I also lightened the background color of the transparent main-nav bar while darkening its text to further the contrast.

- Heading elements are used to provide hierarchical structure to page content.

- `<p>` tags with the class "heading" have been replaced by `<h2>` tags to help assist screen readers.

- Replaced background image with the version without text (concert02_no_text.jpg) and added text to the HTML to roughly match the layout. Added Montserrat font to replace Open Sans.

- Added alt tags to all images on all html pages. Decorative images in tour.html have an empty alt attribute i.e alt="".

- Links are visually distinct.

- Hover state added to links.

- The image link icons in the footer have accompanying text describing the link. The alt text for the image is used on the survey.html and tour.html pages. CSS styling is used to hide text on index.html.

- Create a table for the tour dates information using the element for table data cells and the element for table header cells.

- Ensure your table has a scope and caption element.

### TODO:

#### Form

- Ensure form elements have styled focus states using the :focus pseudo class.
- Add associated labels for form controls.
- Make sure all labels have a 'for' value. Matching for and id values associate the label with the appropriate form control.
- Group form elements with a fieldset.
- Add a legend to describe the grouping.
- Ensure the select field options are in alphabetical order.
- Make sure you can select options in the drop-down menu by typing from the keyboard.

#### Checking your code:

- Check your code using the Chrome Accessibility extension and the Fangs extension for Firefox.
- You can also copy and paste your HTML into the Accessibility Validator (see the Project Resources section for link).
- You will also need to check your code against the Accessibility Checklist (see the Project Resources section for link).

#### Make sure to check your code is valid by running it through an HTML and CSS validator.

- Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
- There are a few exceptions that you don't need to fix:

  - Don't worry about any warnings, we just need you to check any errors that might be there.
  - If CSS validator flags use of calc, vendor prefixes or pseudo-elements/pseudo-classes these errors should be ignored.
  - If HTML validator flags use of pipe ('|') in Google font links/URLs this error can also be ignored.

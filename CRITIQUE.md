# Manual Critiques
- Font hierarchy is good, but the color choices could be improved to better reinforce the hierarchy.
- Some text colors against their respective backgrounds may not meet WCAG contrast requirements.
- Navigation feels rather bland and doesn't stand out enough. The navigation links and buttons could use a stronger visual hierarchy.
- Line spacing is generally good, although it feels a little excessive in some paragraphs, particularly at smaller widths.
- Button hover states make the primary and secondary buttons look too similar when secondary is in hover state, reducing their visual distinction.
- Overall alignment is consistent, and the elements line up well throughout the page.
- The two fonts are used consistently, with Bricolage Grotesque for headings and interface elements and Newsreader for body text.
- Like the sparse use of color but too much on the the book spines, I would keep it but lessen it somehow, because this makes the rest of the page feel very lacking in color and visual interest.
- Responsive navigation could be improved, as most navigation links disappear on smaller screens without a replacement menu.
- The interactive elements are also rather inconsisent with the links glowing to no affect but just underlined.
- No active naviation indicator.
- Color pallete needs balance, the background and font color are so bland that the stronger accent colors just drag the focus to them.
- Navigation links disappear when under 760px
- Dates on top of the book spine do not have enough spacing underneath, so its just really close to the event titles.
- The checkboxes could be slightly larger. They're noticeably smaller than the text inputs, making the form controls feel somewhat inconsistent.
- Spacing within the form feels inconsistent. The distances between labels, inputs, checkboxes, and the submit button could be more uniform.
- There's slightly too much vertical space above the hero content. Reducing the top padding would make the empty space above and below the content feel more balanced.
- The footer feels extremely disconnected from the rest of the page. Its dark background creates an abrupt transition from the lighter sections.
- The links feel inconsistent with the rest of the page and with one another in terms of styling.
- The text colors lack sufficient contrast against the background, making some of the content difficult to read.
- Spacing is inconsistent, both between the top and bottom edges of the footer and among its contents.
- The column contents could be better arranged. For example, the "Back to top" link feels awkwardly placed directly underneath the email address.

# WAVE before: 0 errors, 10 contrast errors, 0 alerts
- Insufficient text contrast (3.88:1) on the book spine
- All text elements have insufficient contrast against the background for the footer

# Table
| # | Problem | Where | Found with | Fix | Fixed? |
|---|---|---|---|---|---|
| 1 | Insufficient text contrast (3.88:1). | Book spine date (Nov 19) | WAVE | Darken the rose background or use a more contrasting text color. | No |
| 2 | Multiple text elements have insufficient contrast against the background. | Footer (brand, description, headings, links, copyright) | WAVE | Adjust footer background and text colors to meet contrast requirements. | No |
| 3 | Text may have insufficient contrast against its background. | Other gray/light text | Contrast checker | Adjust text or background colors to meet WCAG AA requirements. | To check |
| 4 | Colors and font sizes may be unnecessarily inconsistent. | Entire page | CSS Overview | Consolidate styles and standardize repeated values where appropriate. | To check |
| 5 | Keyboard focus indicators may be missing or difficult to see. | Navigation, buttons, and other interactive elements | Keyboard | Add or improve `:focus-visible` styling. | To check |
| 6 | Spacing and padding may be inconsistent. | Buttons, cards, and sections | Visual inspection | Standardize spacing and padding. | To check |
| 7 | Border radius and element sizing may be inconsistent. | Buttons, cards, and form elements | Visual inspection | Standardize dimensions and border radius where appropriate. | To check |
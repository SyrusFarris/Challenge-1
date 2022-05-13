# Code Refactor Starter Code

tldr; noted changes start at line 30... This challenge is to make the website by our client, Horiseon, meet accessibility standards. We will work through the code and make adjustments where necessary to make sure everything meets the clients standards and our standards as professional developers. This readme will act as documentation referencing the changes made at specific lines of code within the html, css, and how they will positively impact the quality of the website, and the accessibility of the website for potential users/customers. Documentation will begin at line 30 of this readme doc. website url: https://syrusfarris.github.io/Challenge-1/


## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN a webpage that meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the icon and image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN I find that they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title
```

## Changes Documented By Team in html

In line 7 we changed "website" to "Horiseon" to accurately display the name of the company within the tab of the browser.

In line 11 we changed the "div" element tag to "header" to accurately represent the this area of code. Line 26 was changed as well for the closing header tag.

In line 13 we changed the "div" tag to "nav" to accurately repsent that this is a nav bar for navigation. Line 25 was adjusted as well for he closing "nav" tag. subsequently we had to adjust the ".header div" in the css files to ".header nav" to not break the code and for it to still function as expected.

Line 27's div tag now for the "hero" section states "section" to help differentiate the code and give it more readability.

line 28's tags have now been changed from "div" to section to denote that this is a seperate section from the "Hero" section.

line 29 now has an "id" linking the "search-engine-optimization" to the nav bar when when it is clicked to bring the users to the correct location on the webiste. 

At line 52 the "div" tag was changed to "aside" to accurately represent the correct semantics and place of content for this section code. the corresponding "div" tag at line 73 was adjusted as well.

Line 74 now has "footer" semantics in place of "div" to accurately represent this section of code. The closing "div" tag at line 79 was adjusted as well.

Alts were added to img's at lines: 30, 37, 44 for accessibility purposes. No alt's were included for the img's in the benefits section because they are viewed as decorative img's.

## Change Documented By Team in css

Starting at line 31 and anywhere else within the css code now has Calibri in quotes for it to be able to rendered if necessary by the users browser.

The benifits, "aside", section was heavily consolidated to run with lesser code cleaning up the work flow of the code and website run performance.

The "content" section was heavily consolodated to run with lesser code, cleaning up the work flow of the code and website run performance. also all the code related to the content section was migrated in css to above the "benefits/aside" section. to show proper sequential order.

![content-section-correction](./Develop/assets/images/website-example.jpg?raw=true "content-section-correctionimg")

Notes were added throughout the css file to seperate the sections of code and to make it more readable and accessible for other developers.

*** NOTE THAT LINE NUMBERS LISTED ABOVE REFERENCE THE PREVIOUS LOCATION OF LINES OF CODE THAT MAY HAVE CHANGED DUE TO NOTES BEING ADDED TO html/css TO SEPERATE SECTIONS OF CODE AND THE ADDITION/REMOVAL OF CODE FOR OPTOMIZATION!***


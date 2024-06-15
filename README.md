# Code Refactor Starter Code

# Challenge requirements / specifications
User Story
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
WHEN I view the image elements
THEN I find accessible alt attributes
WHEN I view the heading attributes
THEN they fall in sequential order
WHEN I view the title element
THEN I find a concise, descriptive title


# Checklist
Acceptance Criteria
GIVEN a webpage meets accessibility standards
WHEN I view the source code
THEN I find semantic HTML elements
# replaced all the 'div' tags that I could to semantic tags
# there was one div tag that I couldn't change, there's a comment marking it in the code

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning
# Css style sheet follows the same order as the HTML by appearance, and proper indenting was used

WHEN I view the image elements
THEN I find accessible alt attributes
# added alt text to every 'img' tag

WHEN I view the heading attributes
THEN they fall in sequential order
# put header tag at the top, and footer tag at the bottom

WHEN I view the title element
THEN I find a concise, descriptive title
# changed the title from just 'website'

# general notes / improvements
There were only three links at the top, one of which was dead, so I fixed it.

collapsed the 'benefits' tags into one another, so it didn't repeat as much



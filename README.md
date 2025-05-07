# afd-week-1

# Converting Non-Semantic HTML to Semantic HTML

## Exercise Overview

**Objective**: Students will practice converting a non-semantic HTML page into a properly structured semantic HTML document.

**Skills Practiced**:
- Understanding HTML5 semantic elements
- Recognizing non-semantic markup patterns
- Improving document structure and accessibility
- Writing cleaner, more maintainable HTML

## Instructions

# Semantic HTML Conversion Exercise

## Task

Convert the provided non-semantic HTML page into semantic HTML5 markup. Your goal is to replace all generic `div` elements with appropriate semantic elements while maintaining the same visual structure.

## Requirements

1. Replace all appropriate `div` elements with semantic HTML5 elements such as:
   - `<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`
   - `<h1>`-`<h6>` for headings
   - `<time>` for dates
   - Other semantic elements as appropriate

2. Maintain all existing content and basic structure

3. Ensure the page remains accessible:
   - Use proper heading hierarchy
   - Include ARIA attributes where helpful
   - Maintain logical document flow

4. The CSS should continue to work with your semantic markup (you may need to update selectors)

## Evaluation Criteria

- Proper use of semantic HTML5 elements
- Logical document structure
- Accessibility improvements
- Code cleanliness and organization
- Maintenance of all original content

## Tips

1. Analyze the current structure to identify natural semantic sections
2. Consider what each content block represents (navigation, article, sidebar, etc.)
3. Pay attention to heading hierarchy
4. Test your page with a screen reader to verify accessibility

## Submission

Commit your modified `index.html` file and push to your GitHub Classroom repository.

---

## Instructor's Solution Key Points

The solution should demonstrate:
1. Replacement of header div with `<header>`
2. Navigation in `<nav>` with list items (`<ul>`, `<li>`)
3. Main content in `<main>` with articles in `<article>` tags
4. Proper heading levels (`<h1>`, `<h2>`, etc.)
5. Dates wrapped in `<time datetime="">`
6. Sidebar content in `<aside>`
7. Footer content in `<footer>`
8. Author information potentially in `<address>` or with `rel="author"`
9. Lists for navigation/menu items

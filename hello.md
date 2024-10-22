# hello.html

80 concepts and syntax elements introduced in the `hello.html` file in this repo.

1. **HTML Document Type Declaration**  
   *Indicates the HTML version being used.*  
   ```html
   <!DOCTYPE html>
   ```
   This declares the document as HTML5.

2. **HTML Root Element**  
   *Contains all HTML elements.*  
   ```html
   <html>
   ```
   All other HTML elements go inside the `<html>` tag.

3. **Language Attribute**  
   *Specifies the language of the document.*  
   ```html
   <html lang="en">
   ```
   Sets the language to English.

4. **HTML Head Element**  
   *Contains metadata and links to styles/scripts.*  
   ```html
   <head>...</head>
   ```
   Holds meta information, like title and CSS.

5. **Character Encoding Meta Tag**  
   *Defines character encoding.*  
   ```html
   <meta charset="UTF-8">
   ```
   Ensures the document uses UTF-8 encoding.

6. **Viewport Meta Tag**  
   *Optimizes the site for mobile devices.*  
   ```html
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   ```
   Adjusts the layout based on the device's screen width.

7. **HTML Title Element**  
   *Defines the title shown in browser tabs.*  
   ```html
   <title>Simple One-Page Website</title>
   ```
   Displays the page title in the browser tab.

8. **Style Element for CSS**  
   *Includes internal CSS styles.*  
   ```html
   <style>...</style>
   ```
   Adds styles directly in the HTML document.

9. **HTML Body Element**  
   *Contains the visible content of the page.*  
   ```html
   <body>...</body>
   ```
   All the visible elements go inside `<body>`.

10. **HTML Navigation Element**  
    *Defines a navigation bar.*  
    ```html
    <nav>...</nav>
    ```
    Holds links for navigating within the page.

11. **Navigation Links**  
    *Creates clickable links for navigation.*  
    ```html
    <a href="#hello">Hello</a>
    ```
    Links to a section with the id "hello."

12. **HTML Section Elements**  
    *Divides content into sections.*  
    ```html
    <section id="hello">...</section>
    ```
    Identifies sections of the page with unique IDs.

13. **Section Headings**  
    *Defines headings for sections.*  
    ```html
    <h2>Hello</h2>
    ```
    Displays a heading inside a section.

14. **HTML Closing Tags**  
    *Closes HTML elements.*  
    ```html
    </section>
    ```
    Closes an open section element.

15. **CSS Selector for `body` and `html`**  
    *Applies styles to both `body` and `html`.*  
    ```css
    body, html {
        margin: 0;
        padding: 0;
    }
    ```
    Removes default margins and paddings.

16. **CSS Property `margin: 0;`**  
    *Removes default margin from elements.*  
    ```css
    margin: 0;
    ```
    Ensures no extra spacing around the body.

17. **CSS Property `padding: 0;`**  
    *Removes default padding from elements.*  
    ```css
    padding: 0;
    ```
    Removes padding inside the body and html.

18. **CSS Property `font-family: Arial, sans-serif;`**  
    *Sets the default font for the page.*  
    ```css
    font-family: Arial, sans-serif;
    ```
    Uses Arial as the primary font, with a fallback.

19. **CSS Property `scroll-behavior: smooth;`**  
    *Enables smooth scrolling behavior.*  
    ```css
    scroll-behavior: smooth;
    ```
    Smoothly scrolls between anchor links.

20. **CSS Selector for `nav`**  
    *Applies styles to the `nav` element.*  
    ```css
    nav {
        position: fixed;
        top: 0;
        width: 100%;
    }
    ```
    Fixes the nav bar to the top.

21. **CSS Property `position: fixed;`**  
    *Fixes an element’s position relative to the viewport.*  
    ```css
    position: fixed;
    ```
    Keeps the navigation bar always visible.

22. **CSS Property `top: 0;`**  
    *Positions the element at the top.*  
    ```css
    top: 0;
    ```
    Anchors the navigation bar to the top.

23. **CSS Property `width: 100%;`**  
    *Sets the element to full width.*  
    ```css
    width: 100%;
    ```
    Ensures the element spans the entire width of the page.

24. **CSS Property `background-color: #333;`**  
    *Sets the background color of an element.*  
    ```css
    background-color: #333;
    ```
    Gives the navigation bar a dark gray background.

25. **CSS Property `padding: 15px 0;`**  
    *Adds vertical padding to the element.*  
    ```css
    padding: 15px 0;
    ```
    Adds space inside the element, top and bottom.

26. **CSS Property `text-align: center;`**  
    *Centers the text horizontally.*  
    ```css
    text-align: center;
    ```
    Ensures the text inside `nav` is centred.

27. **CSS Selector for `nav a`**  
    *Styles the anchor links inside `nav`.*  
    ```css
    nav a {
        color: white;
        margin: 0 15px;
    }
    ```
    Makes the links white with horizontal spacing.

28. **CSS Property `color: white;`**  
    *Sets the text color to white.*  
    ```css
    color: white;
    ```
    Colors the link text white.

29. **CSS Property `text-decoration: none;`**  
    *Removes underlining from links.*  
    ```css
    text-decoration: none;
    ```
    Removes the default underline from links.

30. **CSS Property `margin: 0 15px;`**  
    *Adds space between elements horizontally.*  
    ```css
    margin: 0 15px;
    ```
    Adds 15px space on either side of the links.

31. **CSS Property `font-size: 18px;`**  
    *Sets the size of the text.*  
    ```css
    font-size: 18px;
    ```
    Makes the link text 18px in size.

32. **CSS Property `transition: color 0.3s ease;`**  
    *Creates a smooth transition effect.*  
    ```css
    transition: color 0.3s ease;
    ```
    Changes the link color smoothly on hover.

33. **CSS Selector for `nav a:hover`**  
    *Applies hover effects to the navigation links.*  
    ```css
    nav a:hover {
        color: #ddd;
    }
    ```
    Changes the link color to light gray when hovered.

34. **CSS Property `color: #ddd;`**  
    *Changes the text color to light gray on hover.*  
    ```css
    color: #ddd;
    ```
    Colors the link light gray when hovered.

35. **CSS Selector for `section`**  
    *Styles the section elements.*  
    ```css
    section {
        height: 100vh;
        display: flex;
    }
    ```
    Ensures each section is the height of the viewport and uses flexbox.

36. **CSS Property `height: 100vh;`**  
    *Sets the height to the full viewport height.*  
    ```css
    height: 100vh;
    ```
    Makes the section take up the entire height of the screen.

37. **CSS Property `display: flex;`**  
    *Applies the flexbox layout.*  
    ```css
    display: flex;
    ```
    Uses flexbox to align and centre content.

38. **CSS Property `justify-content: center;`**  
    *Centres content horizontally using flexbox.*  
    ```css
    justify-content: center;
    ```
    Aligns content to the centre horizontally.

39. **CSS Property `align-items: center;`**  
    *Centres content vertically using flexbox.*  
    ```css
    align-items: center;
    ```
    Aligns content to the centre vertically.

40. **CSS Property `font-size: 2em;`**  
    *Increases the size of the text.*  
    ```css
    font-size: 2em;
    ```
    Doubles the default font size.

41. **CSS Property `transition: background-color 0.5s ease;`**  
    *Animates background colour changes.*  
    ```css
    transition: background-color 0.5s ease;
    ```
    Smoothly changes the background colour.

42. **CSS Selector for `section:target`**  
    *Styles sections when targeted by a link.*  
    ```css
    section:target {
        background-color: #f8f8f8;
    }
    ```
    Changes the section background colour when clicked.

43. **CSS Property `background-color: #f8f8f8;`**  
    *Changes the section background colour.*  
   
    ```css
    background-color: #f8f8f8;
    ```
    Sets the background colour to light gray when targeted.

44. **CSS Selector for `#hello`**  
    *Styles the section with the id `hello`.*  
    ```css
    #hello {
        background-color: #f0f0f0;
    }
    ```
    Sets the initial background colour for the "Hello" section.

45. **CSS Property `background-color: #f0f0f0;`**  
    *Sets a light gray background for the section.*  
    ```css
    background-color: #f0f0f0;
    ```
    Gives the "Hello" section a light gray background.

46. **CSS Selector for `#keep-going`**  
    *Styles the section with the id `keep-going`.*  
    ```css
    #keep-going {
        background-color: #e0e0e0;
    }
    ```
    Sets the initial background color for the "Keep going" section.

47. **CSS Property `background-color: #e0e0e0;`**  
    *Sets a light gray background for the section.*  
    ```css
    background-color: #e0e0e0;
    ```
    Gives the "Keep going" section a light gray background.

48. **CSS Selector for `#goodbye`**  
    *Styles the section with the id `goodbye`.*  
    ```css
    #goodbye {
        background-color: #d0d0d0;
    }
    ```
    Sets the initial background color for the "Goodbye" section.

49. **CSS Property `background-color: #d0d0d0;`**  
    *Sets a light gray background for the section.*  
    ```css
    background-color: #d0d0d0;
    ```
    Gives the "Goodbye" section a light gray background.

50. **HTML `id` Attributes**  
    *Identifies sections by their unique id.*  
    ```html
    <section id="hello">...</section>
    ```
    Assigns unique IDs to sections for internal navigation.

51. **HTML `href` Attributes in Links**  
    *Links to sections using their IDs.*  
    ```html
    <a href="#hello">Hello</a>
    ```
    Creates a link that jumps to the "Hello" section.

52. **CSS Universal Selector Concepts**  
    *Applies styles to multiple elements at once.*  
    ```css
    body, html {
        margin: 0;
    }
    ```
    Applies styles to both the body and html elements.

53. **Flexbox Layout**  
    *Centres content horizontally and vertically.*  
    ```css
    display: flex;
    justify-content: center;
    align-items: center;
    ```
    Uses flexbox to centre content within the section.

54. **Fixed Positioning**  
    *Keeps an element fixed in one place.*  
    ```css
    position: fixed;
    top: 0;
    ```
    Ensures the nav bar remains visible during scrolling.

55. **Viewport Units**  
    *Uses viewport height (vh) for responsive design.*  
    ```css
    height: 100vh;
    ```
    Makes the section take up the full height of the screen.

56. **CSS Transitions**  
    *Smoothens changes between states.*  
    ```css
    transition: background-color 0.5s ease;
    ```
    Adds smooth transitions when background colours change.

57. **CSS Pseudo-classes**  
    *Applies styles based on an element's state.*  
    ```css
    nav a:hover {
        color: #ddd;
    }
    ```
    Changes the link colour when hovered.

58. **Anchor Links**  
    *Navigates to specific sections on the page.*  
    ```html
    <a href="#hello">Hello</a>
    ```
    Clicking this link jumps to the section with id `hello`.

59. **Smooth Scrolling**  
    *Adds smooth transition when scrolling to sections.*  
    ```css
    scroll-behavior: smooth;
    ```
    Smoothly scrolls between sections when navigating with anchor links.

60. **The Box Model**  
    *Defines how elements are sized and spaced.*  
    ```css
    margin: 0;
    padding: 0;
    ```
    Resets the default margins and paddings.

61. **Hexadecimal Colours**  
    *Defines colours using hex codes.*  
    ```css
    background-color: #333;
    ```
    Sets the background colour to dark gray.

62. **Font Families**  
    *Sets a font with fallbacks.*  
    ```css
    font-family: Arial, sans-serif;
    ```
    Uses Arial as the primary font, with `sans-serif` as a fallback.

63. **Meta Tags**  
    *Defines metadata for the HTML document.*  
    ```html
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    ```
    Ensures the page is responsive on different devices.

64. **HTML5 Semantic Elements**  
    *Organizes content with semantic elements.*  
    ```html
    <nav>...</nav>
    ```
    Uses `<nav>` to define a navigation bar.

65. **CSS Selectors**  
    *Targets specific elements for styling.*  
    ```css
    nav a {
        color: white;
    }
    ```
    Targets the anchor tags inside the navigation element.

66. **CSS Cascading and Specificity**  
    *Determines how styles are applied.*  
    ```css
    nav a:hover {
        color: #ddd;
    }
    ```
    More specific rules override less specific ones.

67. **HTML Attributes**  
    *Defines characteristics for HTML elements.*  
    ```html
    <a href="#hello">Hello</a>
    ```
    The `href` attribute specifies where the link points.

68. ** Relative Units**  
    *Uses relative sizes for responsive design.*  
    ```css
    font-size: 2em;
    ```
    Sets the font size relative to the parent element's size.

69. ** CSS Reset**  
    *Removes default browser styling.*  
    ```css
    margin: 0;
    padding: 0;
    ```
    Resets margin and padding to create a consistent layout.

70. ** Responsive Design**  
    *Ensures the layout adapts to different screen sizes.*  
    ```css
    height: 100vh;
    ```
    Makes sections scale based on viewport size.

71. ** Document Structure**  
    *Organizes HTML elements in a hierarchy.*  
    ```html
    <html>...</html>
    ```
    The root `<html>` element contains all other elements.

72. ** Web Page Rendering**  
    *How browsers interpret HTML and CSS.*  
    Browsers render elements based on their hierarchy and styling.

73. ** User Interaction**  
    *Hover and click effects enhance user experience.*  
    ```css
    nav a:hover {
        color: #ddd;
    }
    ```
    Changes link color when hovered for better interaction.

74. ** Accessibility**  
    *Uses proper tags and attributes for accessibility.*  
    Correct use of IDs and anchor links enhances accessibility for users navigating with assistive technologies.

75. ** Web Standards**  
    *Adheres to best practices in HTML and CSS.*  
    Using HTML5 and proper syntax ensures compatibility across browsers.

76. ** Inline CSS**  
    *Uses CSS inside HTML via the `<style>` tag.*  
    ```html
    <style>...</style>
    ```
    Embeds CSS directly in the HTML document.

77. ** Cross-browser Compatibility**  
    *Ensures consistent behavior across different browsers.*  
    Proper use of meta tags and CSS ensures the page renders consistently across modern browsers.

78. ** CSS Inheritance**  
    *How styles propagate to child elements.*  
    ```css
    font-family: Arial, sans-serif;
    ```
    The `font-family` property applies to all child elements unless overridden.

79. ** Pseudo-selectors**  
    *Styles elements based on their state.*  
    ```css
    nav a:target {
        background-color: #f8f8f8;
    }
    ```
    Styles a section when it's the target of a link.

80. ** Anchors and Navigation**  
    *Links create navigation within the page.*  
    ```html
    <a href="#goodbye">Goodbye</a>
    ```
    Clicking this link jumps to the section with id `goodbye`.

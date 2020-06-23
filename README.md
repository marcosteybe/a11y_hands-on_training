# Accessibility Hands-On training

This is the accessibility training developed by Hawkeye to raise the awareness and importance of this topic.
By using native tags you are already on an accessible way as native tags are identified and read properly by screen readers. Avoid div soups. Use wai-aria only if no native element is available.


### Tasks and Goals
#### Accessible vs. non-accessible examples

Overview:
1. Create a semantic structure for Headings. https://www.w3.org/TR/WCAG20-TECHS/H42.html
2. Make the list accessible. https://www.w3.org/TR/WCAG20-TECHS/H48.html
3. Use the native tag instead of the deprecated role labeling for the header, footer, main part.

Forms: 
1. Set the focus to invalid field after submit. https://www.w3.org/WAI/tutorials/forms/instructions/
2. Bind a label to the input field https://www.w3.org/WAI/tutorials/forms/labels/
3. Make the dynamic content of the password validation accessible https://www.w3.org/WAI/tutorials/forms/notifications/
  
Layout: 
1. Buttons > Use a button for actions https://www.w3.org/TR/wai-aria-practices/examples/button/button.html
2. Links > Use a link for navigation (extern as intern) https://webaim.org/techniques/hypertext/link_text
3. Images > Use alternative text in order to explain the meaning of an image or hide them for screen readers. https://webaim.org/techniques/alttext/

Colors, Contrasts, Language and Fontsize:
1. Enhance the contrasts in order to achieve a minimum value of 4.5:1 (Level AA) https://webaim.org/articles/contrast/
2. Define the correct language for paragraph with different languages.
3. Use a scalable font-size. https://www.w3.org/TR/WCAG20-TECHS/C14.html
  
Keyboard Navigation: 
1. Use your Keyboard and check if the focus order is ok and every active element can be focused. Is the focus visible? https://www.w3.org/WAI/WCAG21/Understanding/focus-visible.html
2. Avoid focus traps! https://www.w3.org/TR/UNDERSTANDING-WCAG20/keyboard-operation-trapping.html
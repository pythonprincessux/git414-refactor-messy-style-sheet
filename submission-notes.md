Kiara McRae

## Reflection
In my opinion, the most useful refactor was grouping the repeated button, card, and notice styles. Each group now shares one rule, making future updates easier to maintain for myself or future developers if they were to pick up where I left off. I also added custom properties for repeated values and reduced the specificity of two navigation state selectors.

## Browser Checks
I compared the original and refactored stylesheets using the same test page in Chrome at 375px and 1280px. The intended colors, spacing, and component appearance remained consistent. Cards stacked at the narrow width and displayed in three columns at the wide width as intended.

## AI Disclosure
I used ChatGPT to help identify duplicated CSS, and propose an organization plan. I made all the final decisions. I applied the changes and checked all of the results and testing in my browser.
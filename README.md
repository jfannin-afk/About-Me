## Accessibility audit (WAVE)
- Home: WAVE found 0 errors, 0 contrast errors, and 0 alerts.
- Projects: WAVE found o errors, 0 contrast errors, and 0 alerts.
- About/Contact: WAVE found 0 errors, 0 contrast, and 0 alerts.
## Color contrast
Checked with the WebAIM Contrast Checker; all listed combinations pass WCAG AA.
- Body text `#243447` on aquamarine `#7FFFD4`: 10.35:1.
- Context text `#243447` on lightcyan `#E0FFFF`: 12.01:1.
- Header text whitesmoke `#F5F5F5` on charcoal-blue `#243447`: 11.62:1.
## Visual design
- **Proximity:** I grouped related content together, such as the Contact Information heading and email address. 
- **Similarity:** I used the same color palette and consistent heading fonts across the pages to make related elements feel connected.
- **Color palette:** I used aquamarine, lightcyan, charcoal-blue (`#243447`), and whitesmoke consistently across the site.
## Accessible contact form
- Each form field has a visible label associated with its input. 
- Related fields are grouped with a `<fieldset>` and `<legend>` where appropriate.
- Required fields are identified in their labels and use HTML validation.
- Error messages explain how to correct invalid or missing input.
## Testing
- Tested responsive layout at 320px, 768px, and 1200px in Chrome DevTools; no horizontal scrolling or overlap.
- Ran WAVE on Home, Projects, and About/Contact; results are listed above.
- Checked listed text/background color pairs with WebAIM Contrast Checker; all passed WCAG AA.
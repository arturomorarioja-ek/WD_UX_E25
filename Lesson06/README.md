[User Experience - Autumn 2025](https://github.com/arturomorarioja-kea/WD_UX_E25/blob/main/README.md)

# Lesson 6 - 2 October

[-> Show solutions CSS Restaurant + Music CDs]: #
[  -> Feedback (see below)]: #

[-> Colours]: #

[-> White space]: #
[  -> In-class exercise]: #

[-> Further JS: JS frameworks]: #
[-> Further JS: sessionStorage + localStorage]: #
[-> In-class exercises: Stored music CDs]: #

## First Mandatory Assignment exercise solutions
- [Restaurant](https://github.com/arturomorarioja/kea_css_restaurant_solution)
  
[- Music CDs(https://github.com/arturomorarioja/kea_js_music_cds_solution)]: #

General feedback. Things to improve
- Code should be divided into folders. As projects tend to grow, file organisation can soon become unmanageable
- Avoid absolute paths, as it limits the deployability of your project. Do never start a URL path with `/`
- CSS custom properties (variables) must be used for all colours and fonts, and they must be used consistently: just one hardcoded colour can cause grave problems regarding code maintainability
- CSS custom properties must also be used for fixed pixel dimensions
- Remember to load your JavaScript files either with `defer` or as modules
  - Because of loading JavaScript in deferred mode, targeting the `DOMContentLoaded` event is unnecessary

## In-class exercises

### CSS Grid
Complete the code in https://github.com/arturomorarioja/kea_grid_practice_initial using grid and flexbox so that Michel Foucault’s bio page looks like this:

<img width="1024" height="599" alt="image" src="https://github.com/user-attachments/assets/a00e4ffe-bf34-461e-8062-4147948a35a0" />

[Proposed solution(https://github.com/arturomorarioja/kea_grid_practice)]: #

[### White space]: #
[Work in groups of 4. Assess how white space has been used in the following websites, explain which methods have been used to remove visual clutter, and propose actions to remove it in the most cluttered websites:]: #
[- https://www.thomann.de/gb/index.html]: #
[- https://www.zalando.dk/]: #
[- https://www.momondo.dk/]: #

[Show your findings to the class.]: #

## Homework
Check out the following slide decks on Itslearning:

[- **Information Architecture: White Space**]: #

- **Responsive Web Design**, with attention to Grid
  - I recommend bookmarking CSS-tricks.com's [guide on Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)
- **JavaScript: Further Features**, specifically slide 8 (SPA - Single Page Application)

Check out the following code samples

- [CSS Grid with template columns](https://codepen.io/arturomorarioja/pen/wvRmrjj)
- [CSS Grid with template areas](https://codepen.io/arturomorarioja/pen/LYXyVXJ)
- [SPA Restaurant](https://github.com/arturomorarioja/css_restaurant_spa)

Practice responsiveness with CSS:
- [CSS Diner](https://flukeout.github.io/). Practice selecting elements
- [MDN Web Docs](https://developer.mozilla.org/en-US/). Test your skills:
  - [Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Position_skills)
  - [Floats](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Floats_skills)
  - [Responsive web design and media queries](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/rwd_skills):
    - Without flex and grid (the cards may have different height)
    - With flex and grid
  - [Proposed solutions](https://codepen.io/collection/NqBvMy)
  - [Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox_skills)
  - [Grid](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Grid_skills)
- [Codepip](https://codepip.com/):
  - [Flexbox Froggy](https://flexboxfroggy.com/)
  - [Grid Garden](https://cssgridgarden.com/)
- [Coding Fantasy](https://codingfantasy.com/):
  - [Flexbox Adventure](https://codingfantasy.com/games/flexboxadventure)
  - [CSS Grid Attack](https://codingfantasy.com/games/css-grid-attack)
- [Flexbox Zombies](https://flexboxzombies.com/)

[### First Mandatory Assignment]: #
[Start working on the Tristan Wede Lind responsive SPA application]: #

# responsive-design

responsive grid layout from mozilla dev

## CSS grid
## Flexbox
Responsive typography references the viewport to transform text. It does this through media queries, clamp(), or CSS Locks. While these techniques enable granular control of typography across screen sizes, they lack the ability to control typography in different components. This means that, for a page with an array of differently sized content areas, a new headline style would need to be created for each of these areas with a responsive typography approach.

Intrinsic typography doesn’t need all that. With intrinsic typography, a single headline style can be used in all different content areas. Discrete headline styles can be consolidated into one intrinsic headline. This is a distinction similar to that of element queries versus media queries: with element queries it’s possible to bind all of the scaling information to a component, where media queries the styles always reference the viewport.


# HTML5 tags 
## use <header> article main nav footer tags 
so that the screen readers could read the file. 
don't just use divs everywhere.
also add "meta" and "open graph" tabs which are used by every 
social platform. SEO related

## performance ✅
-- preloading
-- prefetching
using link tags 🌐

preload resources to the browser cache which will be used in website
ex. nextJS,remix

## Script 📃
where to put it ? 🤔
for performance,  it's always put at the bottom of the html body
 so that it doesn't stop rendering of html page.

-- normal script tag , html renders and stops when it encounters
a script tag , only when the script is fetched and executed, 
the html start rendering again.

-- async script 
html render until it encounters script with async and
 it keeps rendering even when fetching the script and
 stops when execution of starts.

-- script at body end
 html renders completely and then script is fetched and executed 

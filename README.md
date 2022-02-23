# aem-frontend-101

This guide is intended to explain the basis of frontend development for Adobe Experience Manager. From componentes to libraries, CSS & Javascript, so you can get the main idea and iterate from here.

Constantly learning and rewriting...

## Javascript

### Do not populate the Javascript global/window scope

(libraries would do that for you anyway)

When you are developing for a component-oriented content management system (from now on CMS), you are not on your own. Your feature or component may be sharing the page with a lot of other component-alike features. Imagine you create several global variables and one or two functions.
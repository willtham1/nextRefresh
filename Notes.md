## File Structure
/app - This contains all the routes, components, and logic for the applications
/app/lib - This contains functions for the application such as reusable utility funtions and data feteching funciton.
/app/ui - Conatins all the UI components for the application, such as cards, tables, and forms.

## Typescript
`export type ...` export allows that definition to be imported and used in other files.
`interface` - can be merged, can be slightly better for performance for large code bases due to declaration merging
`type` - cannot be extended/merged, can be more complex to resoleve, especially with adv features

##CSS
use `global.css` to add css rules to all routes in your app
its good practice to add the css file to the top level componenet. in next.js its the root layout
Tailwind is a css framework that speeds up the dev process by allowing you to quickluy write utility classes directly in your react code
clsx libary allows you to conditionally style an element based on state or other condidtions

##Fonts
Fonts play a significant role in the design of a website, but using cusom fonts in your project can affect performance if font files need to be fetched and located

##Image
Make sure you set a height and a width for images before theyre susceptible 

## Nested Routes
Routes a created in the /app folder using folder names and either a page.tsx or layout.tsx
Anything in the glodal layout file will be displayed for the whole roject. So using metadata or footers for example should be placed here
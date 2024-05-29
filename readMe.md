## Tailwind
- Provide a set of classes, each class usually applies a single style 
## Set up tailwind 
- Install Tailwind CSS using CDN link
- Install Tailwind CSS using CLI
- Install Tailwind CSS using Post CSS

## Hover, Focus, and active Effects
You can add the hover effect by just adding a prefix before the class name.

## Reponsive dezign 
- use sm:(put your classes here )

## Support Dark mode 
- use dark prefix dark:(put your classes here )
- to use dark mode, add darkMode:class to module.exports 


## Add custom style 
- Use SQUARE method 
- Use Tailwind.config file (add your own class)

Here an example for for the first method 
- set the width to 500px: w-[400px]
- set the height to 574px: w-[574px]

## Directives
Directives are custom Tailwind-specific at rules you can use in your CSS that offer special functionality for Tailwind CSS projects.

There are 3 directives:

1. @tailwind - to insert Tailwind’s base, components, utilities and variants styles into your CSS.

2. @layer - to tell Tailwind which “bucket” a set of custom styles belong to. Valid layers are base, components, and utilities.

3. @apply - to inline any existing utility classes into your own custom CSS.

## Function
For now, Tailwind has two functions:

1. theme() - to access your Tailwind config values using dot notation.

2. screen() - allows you to create media queries that reference your breakpoints by name instead of duplicating their values in your own CSS.

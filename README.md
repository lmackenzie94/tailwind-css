# Tailwind CSS

- Tailwind CSS is a highly customizable, low-level CSS framework that gives you all of the building blocks you need to build bespoke designs without any annoying opinionated styles you have to fight to override.
- Instead of opinionated predesigned components (ex: card, button, etc.), Tailwind provides low-level utility classes that let you build completely custom designs without ever leaving your HTML.

### Notes

- Add a build script: <code>"build:css": "tailwind build src/style.css -o dist/style.css"</code>
- Download extension 'HTML CSS Support' to get a dropdown helper for class names
- Run <code>npx tailwind init</code> to create a blank config file. This is where you configure all your customization. Make sure to run the build script after changing the config file.
- To create custom classes using tailwind's utility classes, add the classes to 'src/style.css' and use the '@apply' directive
- For easy responsiveness, add 'flex' for certain screen sizes (ex. medium and up). That way, content will be 'block' and stack on smaller screens.

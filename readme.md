# Styling React Apps

### Static & Dynamic Styling for Pretty Apps

- Styling with ***Vanilla CSS***
- Scoping Styles with ***CSS Modules***
- *CSS-in-JS* Styling with ***Styled Components***
- Styling with ***Tailwind CSS***
- Static & ***Dynamic (Conditional)*** Styling



## 1. Vanilla CSS

    It's the basic way of styling react component by writting CSS rules in a single CSS file or multiple CSS files and importing it into React Component

    
### 1.1 Advantages of Vanilla CSS

- CSS code is decoupled from JSX Code

- you write CSS code as you (maybe) know and (maybe) love it

- CSS code can be written by another developer who needs only a minimal amount of access to your JSX code.


### 1.2 Disadvantages of Vanilla CSS

- You need to know CSS

- CSS code is not scoped to components

- CSS rules may clash across components (e.g: same CSS class name used in different components for different purposes).

## 2. Inline Styling

    Applying CSS property as an object to each and every HTML element inside the JSX code.

### 2.1 Inline Styling: Advantages

- Quick & easy to add to JSX

- Styles only effect the element to which you add them

- Dynamic (Conditional) styling is simple

### 2.2 Inline Styling: Disadvantages

- you need to know CSS Rules

- You have to use CamelCase for CSS property name

- You need to style every element individually

- No Seperation between CSS & JSX code.



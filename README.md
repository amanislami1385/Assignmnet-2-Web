# Assignment 2 - Advanced CSS

## Student Information

- Name: Aman Islami
- Group: IT-2510
- University: Astana IT University
- Course: Web Technologies / Front-End Development

## Project Description

This project is Assignment 2: Advanced CSS (Flexbox & Grid).

The purpose of this assignment is to demonstrate the use of:

- CSS Grid
- CSS Flexbox
- CSS selectors
- Colors
- Fonts
- Spacing
- Responsive layouts
- Fluid CSS properties

The project contains three main tasks.

## Task 1 - Geometric Composition

Task 1 uses CSS Grid to create a geometric composition.

The composition uses:

- 6 columns
- 6 rows
- CSS Grid
- Grid gaps for the black lines
- Different colors for the geometric blocks
- A square aspect ratio

The layout scales with the available screen width.

## Task 2 - Component Library

Task 2 uses Flexbox to create several reusable interface components.

### Navigation Bar

The navigation bar contains:

- Logo
- Navigation links
- Login button
- Sign Up button

Flexbox keeps the buttons on the right side.

### Cards

Three cards are created for:

- HTML
- CSS
- Flexbox

The cards use Flexbox so that their buttons remain at the bottom even when the descriptions have different lengths.

### Pagination

The pagination contains:

- Previous button
- Page numbers
- Next button
- Result count

Flexbox is used to arrange the elements and allow them to wrap when the available space becomes smaller.

### Comment Block

The comment component contains:

- Avatar
- User name
- Comment text

Flexbox keeps the text beside the avatar when the text becomes longer.

### Pricing Table

The pricing section contains three plans:

- Basic
- Professional
- Premium

The Professional plan is marked as Recommended.

Flexbox is used to create the layout without fixed heights.

## Task 3 - Three Layouts, One Markup

Task 3 contains 12 articles/products.

The same HTML content can be displayed in three different layouts by changing one class on the container.

### Grid Layout

Class:

    layout-grid

The articles are displayed as responsive cards using CSS Grid.

### List Layout

Class:

    layout-list

The articles are displayed in rows with:

- Image on the left
- Title and description in the middle
- Date on the right

### Magazine Layout

Class:

    layout-magazine

The first article becomes the main lead article and occupies a larger area. The other articles are arranged around it using CSS Grid.

## Technologies Used

- HTML5
- CSS3
- CSS Grid
- CSS Flexbox

No JavaScript, Bootstrap, or CSS media queries are used.

## Project Structure

    Assignment2_AdvancedCSS/
    │
    ├── index.html
    ├── styles.css
    └── README.md

## How to Run

1. Download or clone the repository.
2. Open the `Assignment2_AdvancedCSS` folder.
3. Open `index.html` in a browser.

You can also use Visual Studio Code with the Live Server extension.

For example:

    http://127.0.0.1:5501/index.html

## Testing Task 3

Open `index.html` and find the products container.

For Grid layout:

    <div class="products layout-grid">

For List layout:

    <div class="products layout-list">

For Magazine layout:

    <div class="products layout-magazine">

Change only the class name to test each layout.

The HTML content remains unchanged.

## CSS Layout Tools

| Task | CSS Tool |
|---|---|
| Task 1 - Geometric Composition | CSS Grid |
| Task 2 - Navigation | Flexbox |
| Task 2 - Cards | Flexbox |
| Task 2 - Pagination | Flexbox |
| Task 2 - Comment | Flexbox |
| Task 2 - Pricing | Flexbox |
| Task 3 - Grid Mode | CSS Grid + Flexbox |
| Task 3 - List Mode | CSS Grid + Flexbox |
| Task 3 - Magazine Mode | CSS Grid + Flexbox |

## Responsive Design

The project uses flexible CSS properties such as:

- `flex`
- `flex-wrap`
- `minmax()`
- `auto-fit`
- `gap`
- `aspect-ratio`
- `min-width`
- `width: min()`

These properties allow the layouts to adapt to different screen sizes without using media queries.

## Conclusion

This assignment demonstrates how CSS Grid and Flexbox can be used for different layout problems.

CSS Grid is mainly used for two-dimensional layouts with rows and columns, while Flexbox is used for arranging and aligning elements in one direction.

The project also demonstrates responsive design using flexible CSS properties without JavaScript, Bootstrap, or media queries.

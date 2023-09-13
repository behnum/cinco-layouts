# cinco-layouts

A cheatsheet of some css-based responsive layouts. The focus is on flexbox and grid layouts.

## CSS Layout Implementations

This README provides guidance on implementing five different layouts using CSS for your HTML content. These layouts are achieved through various CSS techniques to create responsive and visually appealing designs.

## Cluster Layout

The cluster layout uses `display: flex` and `flex-wrap` to allow elements to adjust their size and wrap onto the next line when space is limited. To implement this layout, simply apply the `.cluster` class to your container.

```html
<div class="cluster">
  <!-- Add your child elements here -->
</div>
```

## Flexible Grid Layout

The flexible grid layout also utilizes `display: flex` but with an added flexibility. To create a flexible grid, apply the `.flexible-grid` class to your container, and each child element will automatically adjust to the available space.

```html
<div class="flexible-grid">
  <!-- Add your child elements here -->
</div>
```

## Auto Grid Layout

For a more structured grid, use the auto grid layout. Apply the `.auto-grid` class to your container, and it will automatically create a grid with responsive column widths.

```html
<div class="auto-grid">
  <!-- Add your child elements here -->
</div>
```

## Reel Layout

The reel layout is perfect for horizontally scrolling content. Apply the `.reel` class to your container, and it will create a horizontal scrolling layout with snap points for easy navigation.

```html
<div class="reel">
  <!-- Add your child elements here -->
</div>
```

## Main with Sidebar Layout

To create a main content area with a sidebar, use the `.main-with-sidebar` class for your container. The main content will automatically grow to fill the available space, while the sidebar remains fixed.

```html
<div class="main-with-sidebar parent">
  <main class="child">
    <!-- Main content here -->
  </main>
  <aside class="child">
    <!-- Sidebar content here -->
  </aside>
</div>
```

These CSS layouts offer versatility and responsiveness to enhance your web page's visual appeal. Choose the one that suits your design requirements and apply the corresponding class to your HTML container. No need for complex media queries; these layouts adapt beautifully to different screen sizes. Happy coding! ☕️

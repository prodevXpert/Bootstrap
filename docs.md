# Boostrap official documentation from w3schools.com

# Fluid Container
1. Full width container
2. always open the entire width of the screen 
3. Width is always 100%

# Usage Example

```  .container-fluid ```

# Container padding
1. By default container have left and right padding with no top and bottom padding.
2. We can customize padding 

# Example Usage
```.container .pt-5 ```

# 1 Grid System in Bootstrap
1. built with flexbox
2. allows up to 12 columns across the page
3. grid system is responsive
4. will re-arrange automatically depending on the screen size

# 1.1 Grid Classes
1. .col-xs (extra small devices - screen width less than 576px)
2. .col-sm- (small devices - screen width equal to or greater than 576px)
3. .col-md- (medium devices - screen width equal to or greater than 768px)
4. .col-lg- (large devices - screen width equal to or greater than 992px)
5. .col-xl- (xlarge devices - screen width equal to or greater than 1200px)
6. .col-xxl- (xxlarge devices - screen width equal to or greater than 1400px)

# Bootstrap Text colors

The classes for text colors are: 
1. .text-muted, 
2. .text-primary, 
3. .text-success, 
4. .text-info, 
5. .text-warning, 
6. .text-danger, 
7. .text-secondary, 
8. .text-white, 
9. .text-dark, 
10. .text-body 

(default body color/often black) and 
.text-light:

# Bootstrap Background Colors

1. .bg-primary,
2. .bg-success,
3. .bg-info,
4. .bg-warning,
5. .bg-danger,
6. .bg-secondary,
7. .bg-dark,
8. .bg-light.

# 1 Table

# 1.1 Basic Table
1. light padding and horizontal dividers.
2. ``` .table ```

# 1.2 Striped Table
1. class adds zebra-stripes to a table
2. ``` .table-striped ```

# 1.3 Bordered Table
1. adds borders on all sides of the table and cells
2. ``` .table-bordered ```

# 1.3 Hover Rows
1. adds a hover effect (grey background color) on table rows
2. ``` .table-hover ```

# 1.4 Black/Dark Table
1. adds a black background to the table
2. ``` .table-dark ```

# 1.5 Dark Striped Table
1. Combine ````.table-dark ``` and ```.table-striped ``` to create a dark, striped table

# 1.5 Hoverable Dark Table
1. adds a hover effect (grey background color) on table rows
2. ``` .table-hover ```

# 1.6 Borderless Table
1. removes borders from the table
2. ``` .table-borderless ```

# 1.7 Contextual Classes
1. can be used to color the whole table ``` <table> ```,  the table rows ``` <tr> ``` or table cells ``` <td> ```.

List of contextual classes

1. ``` .table-primary ``` 	Blue: Indicates an important action
2. ``` .table-success ```	Green: Indicates a successful or positive action
3. ``` .table-danger ```	Red: Indicates a dangerous or potentially negative action
4. ``` .table-info ```	Light blue: Indicates a neutral informative change or action
5. ``` .table-warning ```	Orange: Indicates a warning that might need attention
6. ``` .table-active ```	Grey: Applies the hover color to the table row or table cell
7. ``` .table-secondary ```	Grey: Indicates a slightly less important action
8. ``` .table-light ```	Light grey table or table row background
9. ``` .table-dark ```	Dark grey table or table row background

# 1.8 Table Head Colors
You can also use any of the contextual classes to only add a background color to the table header:

# 1.9 Small Table
1. makes the table smaller by cutting cell padding in half
2. ``` .table-sm ```

# 1.9 Resposive table
1. dds a scrollbar to the table when needed (when it is too big horizontally)
2. ``` .table-responsive ```
3. You can also decide when the table should get a scrollbar, depending on the screen width:

Class	                Screen width
.table-responsive-sm	< 576px
.table-responsive-md	< 768px
.table-responsive-lg	< 992px
.table-responsive-xl	< 1200px
.table-responsive-xxl	< 1400px
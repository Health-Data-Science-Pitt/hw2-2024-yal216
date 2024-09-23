[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/iZoLzfiS)

# homework 2: visualization

Please use Firearm Death Data from 2016 to make figures to show the relation between firearm deaths and other factors such as Gun Law Strictness and GDP per Capita in USA. 

`homework2-template.Rmd` is provided to read data using `read_excel()`. Please provide `homework2-yourname.Rmd` to make two figures similar to those in `homework2.html`.

# Some Hints

The width and height are 8 and 6 inches respectively for both figures. Keep in mind that all texts should be the same as those in the reference figures.

## First Figure

1. The thickness of border of points is 1 and size of points is 3.

1. Border of points is `black`, but points are filled with different colors based on US regions. 

1. What shape of points you need to use? You may change the shape with `scale_shape_manual()` function.

1. Text colors of state abbreviations are the same as the colors filled in the points, but the color legend is not shown.

1. The size of points in the legend is 3, which is larger than default. You may need to use `guides()` with `guide_legend()` function.

1. Figure title is in **bold** face and centered. Please check `theme()` function.

## Second Figure

1. Remove outlier points with `outlier.size = 0`

1. Add all jitter points with `geom_point` function. You may use `position_jitterdodge(jitter.width=0.05)` for `position` argument. In addition, what `shape` and `size` do you use for `geom_point()`?
 
1. Use `theme()` to add box for legend with color other than "black".

1. The legend title is shown in three lines.
   
1. There is a figure caption. 

# Grading

Grade will be based on how many details you have done.


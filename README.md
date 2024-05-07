# HTML5 Canvas Color Blind Friendly Gradient Picker #

Experimental color picker which finds a gradient through the CIE XYZ color space which runs along the edge of a circle centered on a copunctal point and intersecting with a user selected color. Copunctal point positions taken from [this page] [1].

![screenshot](https://github.com/Lokno/ColorPicker/raw/master/doc/screenshot.png)

## Usage ##

Open this link: https://lokno.github.io/ColorPicker/

Select a type of color-blindness using the drop-down menu below the color space:

- (Protan) protanopia (red-blindness)
- (Deutan) deuteranopia (green-blindness)
- (Tritan) tritanopia (blue-blindness)

Select a color by either picking within the color space, or by using the color input field to the right of the drop-down. The gradient appears just below the color space. The top half of the gradient is drawn as it would appear to a person with the color deficiency corresponding to the selected copunctal point. It corresponds to the circle intersecting with the chosen point and centered on the selected copunctal point.

There are two straight white lines drawn over the color space. One is drawn from the copunctal point through the user selected color. The other line represents the major axis of the selected color deficiency. This axis is what color appears to collapse on for someone with that deficiency.

The ring of dots represent the 15 colors from the D-15 color test. Notice how the order of the colors in the loop would be lost once they collapse to the axis.

## Testing ##

- Tested with Firfox 125.0.3 (64-bit)
- Tested with Google Chrome Version 124.0.6367.156 (64-bit)

## Issues ##

- Picking within the color space does not work in Firefox.

  [1]: http://www.color-blindness.com/2009/01/19/colorblind-colors-of-confusion/
# HTML5 Canvas Color Blind Friendly Gradient Picker #

Experimental color picker which finds a gradient through the CIE 1931 color space which runs along the edge of a circle centered on a copunctal point and intersecting with a user selected color. Theoretically this gradient should be discernible by someone with a color deficiency corresponding with the selected copunctal point. Copunctal point positions taken from [this page] [1].

## Usage ##

View picker.html in a web browser. Select a type of color-blindness using the drop-down menu below the color space:

- (Protan) protanopia (red-blindness)
- (Deutan) deuteranopia (green-blindness)
- (Tritan) tritanopia (blue-blindness)

Select a color by either picking within the color space, or by using the color input field to the right of the drop-down. The gradient appears just below the color space. It corresponds to the circle intersecting with the chosen point and centered on the selected copunctal point.

## Testing ##

- Tested with Google Chrome version 36.0.1985.143 m

## Issues ##

- Intersecting point on circle does not match the position of the user clicks.
- Picking within the color space does not work in Firefox.

  [1]: http://www.color-blindness.com/2009/01/19/colorblind-colors-of-confusion/
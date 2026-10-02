# 3D Printed Polarizer Experiment  

## What is this?

![device](device.png)  ![stand](overview.png) 

A small 3D-printed setup showing the non intuitive behaviour of polarized light.  

# What you need

To build this project you will need a 3D printer and some cheap polarizing sunglasses.

![glasses](glasses.png)

These glasses each contain 4 of the ~45mm filters that we need.  
We only need 3 for this print, so we have one spare.

You can find these for example at https://aliexpress.com/item/1005011665620962.html

## Setup
  
### Aligning the filters

![filters](filters.png)
  
After printing the `stl` files and fitting the filters, the filter angles should be aligned relative to each other.  

![align](calibrate.png)     

This is done by rotating the individual filters in the holders until all three are aligned.      
The alignment is complete when the maximum amount of light is passing all 3 filters with the number tabs aligned as shown above.    

Take note that there is a front and backside for the filters, so if not all filters are in the same orientation you might get unexpected results.

## The experiment

The holders have fixed reference orientations of **0°, 45° and 90°**, allowing the filters to be arranged and compared mechanically.  

- **0° + 90°** → dark
- **0° + 45° + 90°** → transmission
- Change the order of the filters → the result can change.

The fun part is that the filters behave as successive transformations of the polarization state.    
Their composition is **not commutative**: `1 × 2 × 3` is not generally the same as `1 × 3 × 2`.

![the trick](trick.png)

# More about polarization

[Wikipedia: Polarization_(waves)](https://en.wikipedia.org/wiki/Polarization_(waves))

[Wikipedia: Polarization state](https://en.wikipedia.org/wiki/Polarization_(waves)#Polarization_state)

---

## Files

The holders and base are provided as printable 3D files.

## License

**CC BY 4.0**

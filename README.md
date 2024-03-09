# Poisson-Image-Editing

This codebase implements advanced image editing techniques using Poisson image editing methods. The two main applications provided are:

## Seamless Cloning

Seamless cloning is a technique that allows for the insertion of one part of an image into another by seamlessly blending the image intensities. This method ensures that the result looks natural and free of abrupt transitions.

## Local Color Change

Local color change is an application that enables altering the color of specific regions in an image without affecting the rest. This is particularly useful for tasks such as object recoloring while maintaining the original lighting and shading details.

Both applications leverage the mathematical principles of the Poisson equation to achieve smooth transitions and natural-looking results in the edited images.

## References

Poisson image editing：[here](https://dl.acm.org/doi/10.1145/1201775.882269)

## Mask Image Creation

The mask images used in this project for seamless cloning and local color changes were crafted using **GIMP 2.1** software.

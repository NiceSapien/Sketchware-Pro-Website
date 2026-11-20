---
title: Math
description: Documentation for built-in Math blocks in Sketchware Pro.
sidebar_position: 5
slug: math
tags:
 - Blocks
 - Built-in 
 - Math
---

In Sketchware Pro, Math blocks help you perform mathematical calculations and get device screen dimensions. You can use them to find screen sizes, calculate powers, round decimals, find minimum/maximum numbers, and use trigonometry.

# Built-in Math Blocks

### getDip ()
![get dip](assets/math/get-dip.png)

Converts a density-independent pixel (dp) value into physical screen pixels on the user's phone. This helps you draw or size views so they look the same physical size across different screen resolutions.

### getDisplayWidthPixels
![get display width pixels](assets/math/get-display-width-pixels.png)

Returns the full width of the device screen in real pixels. Useful for centering elements or making views fill half or full screen width.

### getDisplayHeightPixels
![get display height pixels](assets/math/get-display-height-pixels.png)

Returns the full height of the device screen in real pixels. Useful for calculating layouts based on the available screen height.

### PI (π)
![pi](assets/math/pi.png)

Returns the mathematical constant Pi (approximately `3.14159...`). Useful when calculating circle circumference, area, or rotation.

### E (e)
![e](assets/math/e.png)

Returns Euler's number constant `e` (approximately `2.71828...`). Used in growth and decay math calculations.

### () to the () power
![to the power](assets/math/to-the-power.png)

Raises the first number to the power of the second number. For example, `2` to the power of `3` gives `8` (`2 * 2 * 2`).

### minimum of () and ()
![minimum of and](assets/math/minimum-of-and.png)

Compares two numbers and returns whichever one is smaller. For example, `minimum of 4 and 9` gives `4`.

### maximum of () and ()
![maximum of and](assets/math/maximum-of-and.png)

Compares two numbers and returns whichever one is bigger. For example, `maximum of 4 and 9` gives `9`.

### square root of ()
![square root of](assets/math/square-root-of.png)

Returns the square root of a number. For example, `square root of 25` returns `5` because `5 * 5 = 25`.

### absolute value of ()
![absolute value of](assets/math/absolute-value-of.png)

Removes any negative sign and turns negative numbers into positive numbers. Positive numbers stay positive. For example, `-8` becomes `8`, and `8` stays `8`.

### round ()
![round](assets/math/round.png)

Rounds a decimal number to the nearest whole number. For example, `4.3` rounds down to `4`, and `4.7` rounds up to `5`.

### ceil ()
![ceil](assets/math/ceil.png)

Always rounds a decimal number **up** to the nearest whole integer (ceiling). For example, `4.1` rounds up to `5`.

### floor ()
![floor](assets/math/floor.png)

Always rounds a decimal number **down** to the nearest whole integer (floor). For example, `4.9` rounds down to `4`.

### sin ()
![sin](assets/math/sin.png)

Returns the trigonometric sine of an angle given in radians.

### cos ()
![cos](assets/math/cos.png)

Returns the trigonometric cosine of an angle given in radians.

### tan ()
![tan](assets/math/tan.png)

Returns the trigonometric tangent of an angle given in radians.

### arcsin ()
![arcsin](assets/math/arcsin.png)

Calculates the inverse sine (arcsine) of a value and returns the angle in radians.

### arccos ()
![arccos](assets/math/arccos.png)

Calculates the inverse cosine (arccosine) of a value and returns the angle in radians.

### arctan ()
![arctan](assets/math/arctan.png)

Calculates the inverse tangent (arctangent) of a value and returns the angle in radians.

### exp ()
![exp](assets/math/exp.png)

Returns Euler's number `e` raised to the power of the given number (`e^x`).

### ln ()
![ln](assets/math/ln.png)

Calculates the natural logarithm (base `e`) of a number.

### log ()
![log](assets/math/log.png)

Calculates the common base-10 logarithm of a number. For example, `log of 100` is `2`.

### Degree () to Radian
![degree to radian](assets/math/degree-to-radian.png)

Converts an angle from degrees (like `180°`) into radians (like `3.14159...`), which is needed for functions like `sin` and `cos`.

### Radian () to Degree
![radian to degree](assets/math/radian-to-degree.png)

Converts an angle from radians back into standard degrees (from `0°` to `360°`).

## Bottom line
That was the explanation for every built-in Math block in Sketchware Pro. If you think some info is wrong or doesn't exist, please let us know in our discord server or simply open a Pull Request in our website's GitHub repository.

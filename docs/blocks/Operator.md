---
title: Operator
description: Documentation for built-in Operator blocks in Sketchware Pro.
sidebar_position: 4
slug: operator
tags:
- Blocks
- Built-in 
- Operator
---

In Sketchware Pro, Operator blocks are used to work with math, text, logic, and raw code. You can use them to compare values, join pieces of text together, check conditions, do basic math, and convert data.

# Built-in Operator Blocks

### `true`
![true](assets/operator/true.png)

A simple boolean block that always represents `true`. Use it whenever you need a condition to always be active.

### `false`
![false](assets/operator/false.png)

A simple boolean block that always represents `false`. Use it whenever you need a condition to always be off or inactive.

### `() < ()`
![less than](assets/operator/less-than.png)

Checks if the first number is strictly smaller than the second number. Returns `true` if it is smaller, otherwise returns `false`. For example, `3 < 5` gives `true`.

### `() = ()`
![equal](assets/operator/equal.png)

Checks if two numbers are equal. Returns `true` if they have the exact same value, otherwise returns `false`.

### `() > ()`
![greater than](assets/operator/greater-than.png)

Checks if the first number is strictly larger than the second number. Returns `true` if it is larger, otherwise returns `false`. For example, `7 > 2` gives `true`.

### `<> and <>`
![and](assets/operator/and.png)

Combines two conditions. Returns `true` only if **both** conditions are true. If even one of them is false, the whole block gives `false`.

### `<> or <>`
![or](assets/operator/or.png)

Combines two conditions. Returns `true` if **at least one** of the conditions is true. It only gives `false` if both sides are false.

### `not <>`
![not](assets/operator/not.png)

Flips a boolean value to its opposite. If the input is `true`, it turns into `false`. If the input is `false`, it turns into `true`.

### `() + ()`
![addition](assets/operator/addition.png)

Adds two numbers together and returns the total sum. For example, `4 + 5` gives `9`.

### `() - ()`
![subtraction](assets/operator/subtraction.png)

Subtracts the second number from the first number and returns the difference. For example, `10 - 4` gives `6`.

### `() * ()`
![multiplication](assets/operator/multiplication.png)

Multiplies two numbers together and returns the result. For example, `3 * 4` gives `12`.

### `() / ()`
![division](assets/operator/division.png)

Divides the first number by the second number. For example, `10 / 2` gives `5`.

### `() % ()`
![modulo](assets/operator/modulo.png)

Returns the remainder left over after dividing two numbers (modulo). For example, `7 % 3` gives `1` because 3 goes into 7 twice with 1 left over.

### `pick random () to ()`
![pick random](assets/operator/pick-random.png)

Generates a random whole number between the two chosen values, including both numbers. For example, `pick random 1 to 6` works just like rolling a dice.

### `length of []`
![length of](assets/operator/length-of.png)

Counts how many characters are in a piece of text. For example, `length of "hello"` returns `5`.

### `join [] and []`
![join and](assets/operator/join-and.png)

Glues two pieces of text together into one. For example, joining `"Super "` and `"Mario"` produces `"Super Mario"`.

### `index [] of []`
![index of](assets/operator/index-of.png)

Finds the position of the first time a letter or word appears inside another text. Positions start counting at `0`. If the text is not found at all, it returns `-1`.

### `last index [] of []`
![last index of](assets/operator/last-index-of.png)

Finds the position of the very last time a letter or word appears inside another text. If it is not found, it returns `-1`.

### `substring [] to []`
![substring to](assets/operator/substring-to.png)

Cuts out a smaller slice of text from a string starting at the first position up to (but not including) the second position.

### `[] equals []`
![equals](assets/operator/equals.png)

Checks if two pieces of text are exactly identical, including uppercase and lowercase letters. Returns `true` if they match, and `false` if they don't.

### `[] contains []`
![contains](assets/operator/contains.png)

Checks whether a piece of text has another specific word or character inside it. Returns `true` if found, otherwise `false`.

### `replace all [] with []`
![replace all with](assets/operator/replace-all-with.png)

Finds every occurrence of a word or letter inside your text and swaps it out with a new replacement. For example, replacing `"cat"` with `"dog"` in `"my cat"` turns it into `"my dog"`.

### `trim []`
![trim](assets/operator/trim.png)

Removes any accidental empty spaces from the very beginning and very end of a piece of text.

### `toUpperCase []`
![to upper case](assets/operator/to-upper-case.png)

Changes every letter in your text to ALL CAPITAL (UPPERCASE) letters. For example, `"hello"` becomes `"HELLO"`.

### `toLowerCase []`
![to lower case](assets/operator/to-lower-case.png)

Changes every letter in your text to all lowercase letters. For example, `"WORLD"` becomes `"world"`.

### `toNumber []`
![to number](assets/operator/to-number.png)

Converts a text string containing digits (like `"42"`) into a real number variable you can do math with.

### `parse int []`
![parse int](assets/operator/parse-int.png)

Reads an integer (whole number) out of a text string. Similar to `toNumber`, but strictly reads it as an integer.

### `toHashCode []`
![to hash code](assets/operator/to-hash-code.png)

Calculates a unique numerical hash code for any piece of text. Often used for fast comparisons or organizing data into buckets.

### `toString () without decimal`
![to string without decimal](assets/operator/to-string-without-decimal.png)

Converts a number into text without any decimal places. For example, `15.0` or `15.8` becomes `"15"`.

### `toString () with decimal`
![to string with decimal](assets/operator/to-string-with-decimal.png)

Converts a number into text and keeps the decimal digits. For example, `15.75` becomes `"15.75"`.

### `toDecimalFormat []`
![to decimal format](assets/operator/to-decimal-format.png)

Formats a number into text using a custom pattern (such as `#,###.00` to show commas and two decimal places).

### `JSON [] to Map: [map]`
![json to map](assets/operator/json-to-map.png)

Takes a JSON formatted text string and automatically fills a Map variable with all of its key-value pairs. Great for reading data received from web APIs.

### `Map: [map] to JSON String`
![map to json string](assets/operator/map-to-json-string.png)

Converts all the key-value data inside a Map variable into a standard JSON text string so you can send it to an online server or save it.

### `JSON [] to List Map: [listmap]`
![json to list map](assets/operator/json-to-list-map.png)

Takes a JSON array string and automatically fills a List Map with all of the items. Very useful when downloading lists of items from the internet.

### `List Map: [listmap] to JSON String`
![list map to json string](assets/operator/list-map-to-json-string.png)

Converts an entire List Map into a JSON array text string ready to be saved or uploaded.

### `add source directly []`
![add source directly multiline](assets/operator/add-source-directly-multiline.png)

Allows you to write raw Java code directly as a regular action block. Whatever Java code you type inside this block gets inserted straight into your app's code.

### `boolean []` (ASD Boolean)
![add source directly boolean](assets/operator/add-source-directly-boolean.png)

Allows you to write a snippet of custom Java code that returns a `true` or `false` boolean, which can be snapped directly into any condition slot.

### `number []` (ASD Number)
![add source directly number](assets/operator/add-source-directly-number.png)

Allows you to write custom Java code that produces a number, which can be plugged directly into any number input slot.

### `string []` (ASD String)
![add source directly string](assets/operator/add-source-directly-string.png)

Allows you to write custom Java code that produces a string (text), which can be plugged directly into any text input slot.

## Bottom line
That was the explanation for every built-in Operator block in Sketchware Pro. If you think some info is wrong or doesn't exist, please let us know in our discord server or simply open a Pull Request in our website's GitHub repository.
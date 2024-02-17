# Css Filter

In CSS, the `filter` property allows you to apply graphical effects like blur, grayscale, brightness adjustment, and more to elements on a webpage. It's a powerful tool for creating visual effects without the need for image editing software.

Here are some common filters you can apply using the `filter` property:

1. `blur()`: Applies a blur effect to the element. The higher the value inside the parentheses, the more blurred the element becomes.

2. `grayscale()`: Converts the element to grayscale. A value of 1 means fully grayscale, while 0 means no grayscale.

3. `brightness()`: Adjusts the brightness of the element. Values greater than 1 increase brightness, while values less than 1 decrease brightness.

4. `contrast()`: Adjusts the contrast of the element. Values greater than 1 increase contrast, while values less than 1 decrease contrast.

5. `sepia()`: Applies a sepia tone effect to the element. Values closer to 1 preserve more of the original colors, while higher values increase the sepia effect.

6. `hue-rotate()`: Rotates the hues of the element. Values are in degrees, with 0 and multiples of 360 representing no change.

Here's an example of how you can use the `filter` property in CSS:

```css
img {
  filter: blur(5px) grayscale(0.5) brightness(1.2);
}
```

In this example, the `filter` property is applied to an `<img>` element, applying a blur effect of 5 pixels, a grayscale effect of 50%, and increasing the brightness by 20%. You can combine multiple filters and adjust their values to achieve the desired visual effect.

[MDN refrence](https://developer.mozilla.org/en-US/docs/Web/CSS/filter)

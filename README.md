# 🎨 CSS Transform Exercise

## 📚 Project Description

In this exercise, you will explore the power of CSS transforms to create dynamic, visually engaging elements on a webpage. The goal is to style a set of boxes using **four different CSS transform techniques**. These transforms will help you understand how elements can be scaled, moved, rotated, and skewed to create unique visual effects.

You are encouraged to experiment with combinations of transforms to produce creative and distinct designs for each box.

## ✏️ Task

Apply **four different CSS transforms** to the boxes to make each one look **visually distinct and interesting**.

You may use any of the following transform functions:

- `scale()`
- `translate()`
- `rotate()`
- `skew()`

You can also **combine multiple transforms** on a single element:
```css
transition: 0.3s ease;
````
```css
transform: rotate(20deg) scale(1.2);
```

## ⭐ Bonus Interaction

Once the basic transforms are applied, you can take the project a step further with an **interactive hover effect**. By using the `:hover` selector along with a smooth `transition`, you can make your boxes animate—such as spinning, growing, or shifting—when the user moves their cursor over them.

Example:

```css
.box:hover {
  transform: rotate(360deg);
  transition: 0.3s ease;
}

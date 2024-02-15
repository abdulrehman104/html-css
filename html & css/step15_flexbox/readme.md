# FlexBox

Flexbox is a layout model in CSS that provides a more efficient way to design and structure the layout of items within a container. It's designed to make it easier to align, distribute, and reorder elements within a container, especially when dealing with dynamic or unknown sizes of the elements.

Here are some key concepts and features of Flexbox:

1. **Flexible Box**: Flexbox allows you to create a flexible layout where items can grow or shrink to fill the available space within the container.

2. **Container and Items**: Flexbox works by defining a flex container (using `display: flex;` or `display: inline-flex;`) and placing flex items inside it. The container becomes a flex container, and its children become flex items.

3. **Main and Cross Axis**: Flexbox layout operates along two axes: the main axis and the cross axis. The main axis is determined by the `flex-direction` property, and the cross axis is perpendicular to it.

4. **Flex Direction**: The `flex-direction` property determines the main axis of the flex container, which can be horizontal (row) or vertical (column).

5. **Flex Items Alignment**: Flexbox provides properties like `justify-content` and `align-items` to align flex items along the main and cross axes, respectively.

6. **Flex Item Ordering**: Flex items can be reordered using the `order` property, allowing you to change the visual order without changing the order in the HTML markup.

7. **Flex Item Growth and Shrinkage**: Flex items can grow or shrink based on available space and defined flex properties (`flex-grow`, `flex-shrink`, and `flex-basis`).

8. **Flex Wrap**: Flexbox also supports wrapping flex items onto multiple lines when there's not enough space within the container. This behavior is controlled by the `flex-wrap` property.

Overall, Flexbox provides a powerful and intuitive way to create complex layouts with CSS, making it easier to build responsive and dynamic web designs.

data:image/png;base64,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

# **_Container Properties_**

# Dispay Flex

Display flex se container ke items left se right a jate hn

```css
.selector {
  display: flex;
}
```

# Justify content.

### 1- flex start

items horizontally start mn a jate hn

```css
.selector {
  justify-content: flex-start;
}
```

### 2- flex end

items horizontally end mn a jate hn

```css
.selector {
  justify-content: flex-end;
}
```

### 3- Center

Items ko horizontally center kr deta he

```css .selector {
 justify-content: center;
}
```

# Align items

### 1- flex start

items vertically start mn a jate hn

```css
align-items: flex-start;
```

### 2- flex end

items vertically end mn a jate hn

```css
align-items: flex-end;
```

### 3- center

items vertically center mn a jate hn

```css
align-items: center;
```

# Flex Direction

### 1- Default

By default Left to right hota he

```css
flex-direction: default;
```

### 2- Column

column mn vertically show kre ga (upper se niche )

```css
flex-direction: column;
```

### 3- Column- Reverse

column reverse mn vertically show kre ga (niche se upper )

```css
flex-direction: column-reverse;
```

### 4- Row

Row mn sare items vertically a jayege (start se end tk)

```css
flex-direction: row;
```

### 5- Row-Reverse

Row mn sare items vertically a jayege (end to start tk)

```css
flex-direction: row-reverse;
```

# Flex Axis

![alt text](image.png)

## Justify Contant in main axis

Justify content hamesha main axis ko dekh kr kse bhi containers ko center mn krta he

agr flex direction row he to justify content main axis ko dekh kr horizontally center kr dega items ko

agr flex direction column he to justify content main axis ko dekh kr vertically items ko center kr dega

![alt text](image-1.png)

# Flex Wrap

### 1- Wrap

Zyada items honge to unko wrap kr dega next line mn leke a jayega

```css
flex-wrap: wrap;
```

### 2- no wrap

ak he line mn sare items a jayete next line mn nhi ayege

```css
flex-wrap: nowrap;
```

### 3- wrap reverse

Sare items ko reverse kr dega (end se start tk leke a jayega)

```css
flex-wrap: wrap-reverse;
```

# Align contact

### 1- center

Align item jab use krte hn jab hamare pas ak se zyada line hote hn hamare sare lines ko center mn leke a jayega

```css
align-content: center;
```

### 2- flex start

flex start se sara ka sare start mn a jayega

```css
align-content: flex-start;
```

### 3- flex end

flex end se sara ka sara end mn a jayega

```css
align-content: flex-end;
```

# Flex Flow

Do properites ak sath de sakte hn is mn

```css
flex-flow: row wrap;
```

# Gap

Is ko style mn use krke bhi ham items mn gap de sakte hn

```css
gap: 30px;
```

### 1-Row Gap

Row ke bitch mn gap leke a jayega

```css
row-gap: 40px;
```

### 2-Column Gap

Column ke bitch mn gap leke a jayega

```css
column-gap: 50px;
```

### 3- Gap (row column)

Is se ham row and coloum mn ak sath gap de sakte hn first value row ke hote he second value column ke

```css
gap: 40px 10px;
```

# **_Items Property_**

# Orders

Age kse bhi item ko kse khas order mn lana he to uske liye order ke property use kre ge.
By default items ka order 0 hota he jitna ap orer zyada krte rhe ge item utna end mn ate rhe ge

```css
 <style>
      .items {
        font-size: 50px;
        height: 100px;
        width: 90px;
        background-color: blue;
        /* margin: 4px; */
        border: 2px solid red;
      }
      .order1 {
        order: 1;
      }
      .order2 {
        order: 2;
      }
      .order3 {
        order: 3;
      }
      .order4 {
        order: 4;
      }
    </style>
  </head>
  <body>
    <div class="container">
      <div class="items">0</div>
      <div class="items">0</div>
      <div class="items order3">3</div>
      <div class="items order2">2</div>
      <div class="items order1">1</div>
      <div class="items order4">4</div>
    </div>
  </body>

```

![alt text](image-3.png)

Agr ham is image mn dekhen to ye sare items order ke waja se one buy one aye hn warna ham ne inko age piche define keya tha

# Flex Grow

Flex grow se ham apne container mn jitne mn items mn unko set kr sakte hn. By default iske value 0 hote he.

```css
flex-grow: 1;
```

ham ne iske 1 kr de is se ye huwe ke hamare jitne bhi width se to sare items equally width leke adjust ho jayege

![alt text](image-4.png)

### For one items

Agr kse bhi ak item ko

```html css
<style>
  .items {
    flex-grow: 1;
    font-size: 50px;
    height: 100px;
    width: 90px;
    background-color: blue;
    /* margin: 4px; */
    border: 2px solid red;
  }
  .item1 {
    flex-grow: 2;
  }
</style>
<body>
  <div class="container">
    <div class="items item1">0</div>
    <div class="items">0</div>
    <div class="items order3">3</div>
    <div class="items order2">2</div>
    <div class="items order1">1</div>
    <div class="items order4">4</div>
  </div>
</body>
```

ak item ko flex grow 2 dene se wo items 2 items ke jga lega

![alt text](image-5.png)

# Flex shrint

jis item pr ham ne flex shrint lgaya huwa he wo items shrink ho jayega

```css
flex-shrink: 2;
```

![alt text](image-6.png)

# Align Self

Kse ak item ko handle krna hoto is se kr sakte hn

```css
.item1 {
  align-self: flex-start;
}
.item2 {
  align-self: flex-end;
}
```

![alt text](image-7.png)

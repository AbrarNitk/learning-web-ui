# Box Model

If I have below html

```html
<p>I am a paragraph of text that has a few words in it.</p>
```
and I write the below CSS

```css
p {
    width: 100px;
    height: 50px;
    padding: 20px;
    border: 1px solid;
}
```

- Example [Link](./box-model-example-1.html)

The content is breaking out the element and it is 142px wide, rather than 100px.


> Note: It's all boxes.


## Content and Sizing

> Boxes have different behaviour based on their `display` value, their set dimensions
> and the content that lives with in them

> Notice that when the box is using extrinsic sizing, there's a limit of how much 
> content you can add before it overflows out of the box's bounds. This makes 
> the word, "awesome", overflow.

```css
.awesome {
  text-transform: uppercase;
  font-size: 5rem;
  font-weight: 700;
  line-height: 1;
  border: 5px solid;
  padding: 2rem;

  /* The important extrinsic width */
  width: 400px;
}

.awesome[data-sizing="intrinsic"] {
  width: min-content;
}

/*

Presentational styles 
*/
.awesome {
  --flow-space: 2rem;
}
```

> Key Term:
> When content is too big for the box it is in, we call this overflow. 
> You can manage how an element handles overflow content, using the overflow property.


## The areas of the box model


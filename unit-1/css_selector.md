# Discussion Question - CSS Selectores

## Directions
- In an in-person class, have a group member hook up their laptop to a larger monitor. In a remote class, have a group member share their screen.
- For each queestion, **_everyone should share their explantion, an example, or a mental model_**. 
- Take 20 minutes to _discuss_ and _debate_ these questions as a group. We will review them as a class afterwards. 

## Questions

1. Explain what HTML element(s) the following css selectors will select, and how will they change the styling? Reference [Combinators](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Combinators) if needed.

```css
div#title.danger{
  color: red;
}
```

```css
div #title .danger{
  color: red;
}
```

2. Without changing the HTML snippet below: 
    * How would you select _only_ the list items of `Hello World` and `Good Morning World`?
    * How would you select _only_ the list item of `Goodbye World`? 
Reference [Pseudo-classes](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Selectors/Pseudo-classes_and_pseudo-elements) if needed.

```html
<div class="morning">
  <ul>
    <li>Hello World</li>
    <li>Good Morning World</li>
  </ul>
</div>

<div class="night">
  <ul>
    <li>Good evening World</li>
    <li>Good night World</li>
    <li>Goodbye World</li>
    <li>See ya World</li>
  </ul>
</div>

```

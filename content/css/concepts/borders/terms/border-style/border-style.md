---
Title: "border-style"
Description: "Sets the style of the border. The default value is none."
Subjects:
  - "Web Development"
  - "Web Design"
Tags:
  - "Borders"
  - "Box Model"
CatalogContent:
  - "learn-css"
  - "paths/front-end-engineer-career-path"
  - "paths/full-stack-engineer-career-path"
---

 
Sets the style of the border. The default value is `none`.

## Syntax

```css
border-style: <line-style>;
```

where `<line-style>` can be the following values:

- `none`
- `hidden`
- `dotted`
- `dashed`
- `solid`
- `double`
- `groove`
- `ridge`
- `inset`
- `outset`

## Example 1

Set border of the `h1` element to be green, 3 pixels thick, and dotted:

```css
h1 {
  border-color: green;
  border-width: 3px;
  border-style: dotted;
}
```

## Example 2

Set the top and bottom borders dashed and the left and right borders solid:

```css
h1 {
  border-style: dashed solid;
}
```

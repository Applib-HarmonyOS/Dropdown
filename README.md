# Neumorphism_Dropdown

# Installation :

1. Copy the neumorph_dropdown folder in your repo.
2. Add neumorphism as a dependency in your package.json file.

```json
{
  "dependencies": {
    "neumorphism": "file:../neumorph_dropdown"
  }
}
```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Dropdown

<img src="sample_images/dropdown.png" width="" height="">

Import:
```html
<element name='neudropdown' src='../../../../../../node_modules/neumorphism/dropdown/dropdown.hml'></element>
```

Usage:
```html
<neudropdown width="200px" height="50px" border="10px" @change-event="dropdownSelect">
  <select @change="dropdownSelect">
    <option value="Item 1">Item 1</option>
    <option value="Item 2">Item 2</option>
    <option value="Item 3">Item 3</option>
    <option value="Item 4">Item 4</option>
    <option value="Item 5" selected="true">Item 5</option>
  </select>
</neudropdown>
```

# Reference:

<a href="https://neumorphism.io/">neumorphism.io</a>

<a href="https://ismail9k.github.io/neomorphism/">ismail9k.github.io/neomorphism</a>
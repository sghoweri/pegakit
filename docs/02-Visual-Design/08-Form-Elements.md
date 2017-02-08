# Form elements

Forms allow users to enter information into the system. Close attention should be paid to providing clear and descriptive labels and help text, and to maintaining the ability to tab through forms in an efficient manner.

## Inputs

### Text field

```html
  <label>First name</label> 
  <input type="text" placeholder="First Name"> 
```

### Text field with button

```html
  <input type="text" placeholder="Search">
  <button class="btn-raised">Search</button>
```

### Text area

```html
  <label>First name</label> 
  <input type="textarea" placeholder="First Name"> 
```

### Rich text editor

For textareas that involve community-generated content, such as comments or community posts, we use a basic formatting editor that only allows the following options:

- Text formatting - Bold, Italic, Underline
- Bulleted/Numbered Lists
- Indent/Outdent
- Code Snippets
- Links
- Quotes

## Radio buttons and checkboxes

Radio buttons and checkboxes should be used for option lists that contain fewer then 7 items. If your list contains more than 7 items, use one of the Select widgets instead.

```html
<!-- Radio buttons -->
<input validationtype="required" id="option1" type="radio" value="Option 1">
<label for="option1">French Press</label>
<input validationtype="required" id="option2" type="radio" value="Option 2">
<label for="option2">Espresso</label>
<input validationtype="required" id="option3" type="radio" value="Option 3">
<label for="option3">Café au lait</label>

<!-- Checkboxes -->
<input validationtype="required" id="option4" type="checkbox" value="Option 4">
<label for="option4">French Press</label>
<input validationtype="required" id="option5" type="checkbox" value="Option 5">
<label for="option5">Espresso</label>
<input validationtype="required" id="option6" type="checkbox" value="Option 6">
<label for="option6">Café au lait</label>
```

## Select widgets

Select options should be used for lists that contain more than 7 items. For very long multiselect lists, use the autocomplete widget provided by [Chosen](https://harvesthq.github.io/chosen/).

### Standard Dropdown

```html
<fieldset>
    <div class="field-container">
        <label for="select">Select</label>
        <select id="select">
            <optgroup label="Option Group">
                <option>French Press</option>
                <option>Espresso</option>
                <option>Café au lait</option>
            </optgroup>
        </select>
    </div>
</fieldset>
```




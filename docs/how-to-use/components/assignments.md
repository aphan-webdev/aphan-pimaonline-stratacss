# Assignments Widget

Use the `assignments-widget` to organize each assignment into cards.

## Structure

The `<assignments-widget>` wraps all `<assignment-item>` elements. An `<assignment-item>` typically consists of an `<h3>` heading which is the title of the assignment, a `<p>` element that describes the assignment, and an `<a>` element which is a link styled as a button using `class="button"` that will direct the user to the assignment page.

## HTML 

The `columns widget` in the HTML should have this structure.

```html
<assignments-widget>
  <assignment-item>
    <h3>Assignment Item</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis felis malesuada nulla malesuada, laoreet egestas felis luctus. Vestibulum imperdiet iaculis eros sed hendrerit. Duis consectetur congue nibh sed imperdiet.</p>
    <a href="#" class="button">Link To Assignment</a>
  </assignment-item>
  <assignment-item>
    <h3>Assignment Item</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis felis malesuada nulla malesuada, laoreet egestas felis luctus. Vestibulum imperdiet iaculis eros sed hendrerit. Duis consectetur congue nibh sed imperdiet.</p>
    <a href="#" class="button">Link To Assignment</a>
  </assignment-item>
  <assignment-item>
    <h3>Assignment Item</h3>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis felis malesuada nulla malesuada, laoreet egestas felis luctus. Vestibulum imperdiet iaculis eros sed hendrerit. Duis consectetur congue nibh sed imperdiet.</p>
    <a href="#" class="button">Link To Assignment</a>
  </assignment-item>
</assignments-widget>
```

<div class="example-container">
  <assignments-widget>
    <assignment-item>
      <h3>Assignment Item</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis felis malesuada nulla malesuada, laoreet egestas felis luctus. Vestibulum imperdiet iaculis eros sed hendrerit. Duis consectetur congue nibh sed imperdiet.</p>
      <a href="#" class="button">Link To Assignment</a>
    </assignment-item>
    <assignment-item>
      <h3>Assignment Item</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis felis malesuada nulla malesuada, laoreet egestas felis luctus. Vestibulum imperdiet iaculis eros sed hendrerit. Duis consectetur congue nibh sed imperdiet.</p>
      <a href="#" class="button">Link To Assignment</a>
    </assignment-item>
    <assignment-item>
      <h3>Assignment Item</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque venenatis felis malesuada nulla malesuada, laoreet egestas felis luctus. Vestibulum imperdiet iaculis eros sed hendrerit. Duis consectetur congue nibh sed imperdiet.</p>
      <a href="#" class="button">Link To Assignment</a>
    </assignment-item>
  </assignments-widget>
</div>
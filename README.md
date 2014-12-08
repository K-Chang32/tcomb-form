> "La semplicità è l'ultima sofisticazione" (Leonardo da Vinci)

# Domain Driven Forms

The [tcomb library](https://github.com/gcanti/tcomb) provides a concise but expressive way to define domain models in javascript.

The [tcomb-validation library](https://github.com/gcanti/tcomb-validation) builds on tcomb, providing validation functions for tcomb domain models.

This library builds on those two and realizes an old dream of mine.

![tcomb-form diagram](https://gcanti.github.io/resources/tcomb-form/tcomb-form-diagram.png)

# Playground

[Live Demo!](http://gcanti.github.io/resources/tcomb-form/playground/playground.html)

If you want to see this library in action, the playground contains a dozen examples and the code section is fully editable with live updates in the preview and HTML views.

# Benefits

With tcomb-form you simply call `var Form = t.form.create(domainModel)` to generate a form based on that domain model. What does this get you?

1. Write a lot less HTML
2. Usability and accessibility for free (automatic labels, inline validation, etc)
3. No need to update forms when domain model changes

# Flexibility

- tcomb-forms lets you override automatic features or add additional information to forms.
- You often don't want to use your domain model directly for a form. You can easily create a form specific model with tcomb that captures the details of a particular feature, and then define a function that uses that model to process the main domain model.

# Stable release

This library is under heavy development.
The current stable release is on [branch v0.2](https://github.com/gcanti/tcomb-form/tree/v0.2)

# Roadmap to v0.3.0

- [] fatories must return a valid React component
- [] for attribute for labels
- [] aria support
- [] build examples
- [] rebuild the playground
- templates
  - [] bootstrap
  - [] foundation
  - [] pure
  - [] ionic
  - [] gridforms / [flakes](http://getflakes.com/index.html)

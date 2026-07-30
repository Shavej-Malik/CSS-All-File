nesting scss -> you can write selectors inside other selectors
mixin in scss -> A mixin is like a reusable styles for rule.Helps avoid code repetation.Can use variable by using $
Partials & imports -> Partials -> Small SCSS file (start with _)to split your code(e.g. _header.scss, _footer.scss etc....).Any CSS file will not generate for this type scss file
imports -> Use @import to bring all partials into one main file. Keep project modular and easy to maintain
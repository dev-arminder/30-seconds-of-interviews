### What is the meaning of "cascading' in CSS?

#### Answer

In CSS, more than one style sheet can simultaneously influence a the presentation of a document and rules from these style sheets may overlap in scope (e.g., two rules that apply to the same element specify a font size). CSS resolves these conflicts by assigning a weight to each style rule and when several rules apply, choosing the one with the greatest weight. This is known as the cascade .

The rule used is chosen by cascading down from the more general declarations to the specific rule required. The most specific declaration is chosen.

#### Good to hear

- Cascade determinines which specific stylesheet rule applies to which piece of HTML

##### Additional links

- [Cascade - W3.org](https://www.w3.org/TR/WD-CSS2-971104/cascade.html)

<!-- tags: (css) -->

<!-- expertise: (1) -->

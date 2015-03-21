# Demo Form Field Alignment

Demo of horizontally spacing form fields in HTML/CSS

**index.html**
Contains the form in question. I've set this up using ``<label>`` for each
form element. The elements are wrapped in ``<div>`` to force each grouping onto
its own line.

**main.css**
Contains the styling. The approach is to for the ``<label>`` to have a width that
is larger than the widest content. Since ``<label>`` are inline elements, the width
won't take unless you switch them to ``inline-block``.

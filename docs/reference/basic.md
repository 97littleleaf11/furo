# Basic Markup

## Lists

```{furo-demo}
- Lists in Markdown are pretty straightforward.
- A bunch of bullet points.
  - Nested bullets should be indented by two or more spaces.
  - They can just "show up" inline with the rest of the list.


1. Numbered lists are not complicated.
2. They do exactly what you think they do.

Definition Lists
:  An extremely useful tool for describing stuff.

Term
:  Definition
+++

- Lists in reStructuredText are fairly straightforward.
- A bunch of bullet points.

  - Nested bullets should be indented by **exactly** two spaces.
  - They also need a blank line before them, otherwise it doesn't work right.

1. Numbered lists are not complicated.
2. They do exactly what you think they do.

Definition Lists
   An extremely useful tool for describing stuff.

Term
   Definition
```

## Code

````{furo-demo}
```python
print("Hello from Markdown")
```

+++

.. code-block:: python

    print("Hello from reStructuredText")
````

## Images

```{furo-demo}
![](https://source.unsplash.com/200x200/daily?ferret)

This is from Markdown.

+++

.. image:: https://source.unsplash.com/200x200/daily?ferret

This is from reStructuredText.
```

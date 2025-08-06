# Test docs

For testing sphinx and RTD features.

## Link preview test

```md
Link to {term}`a glossary entry`.
```

Link to {term}`a glossary entry`.

Link to {term}`another glossary entry`.

---

```md
Just a [regular internal link](/reference/index).
```

Just a [regular internal link](/reference/index).

---

```html
A HTML link with <a class="link-preview" href="/reference/index">custom class</a>.
```

A HTML link with <a class="link-preview" href="reference/glossary/#term-a-glossary-entry">custom class</a>.

```{toctree}
:hidden:
reference/index
```

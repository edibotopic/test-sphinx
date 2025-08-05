# Test docs

For testing sphinx and RTD features.

## Link preview test

```md
Link to {term}`a glossary entry`.
```

Link to {term}`a glossary entry`.

---

```md
Just a [regular internal link](/reference/index).
```

Just a [regular internal link](/reference/index).

---

```html
Just another <a class="link-preview" href="/reference/index">regular link</a>.
```

Just another <a class="link-preview" href="reference/">regular link</a>.

```{toctree}
:hidden:
reference/index
```

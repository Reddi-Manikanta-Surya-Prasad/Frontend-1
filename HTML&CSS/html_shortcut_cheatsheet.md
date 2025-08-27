# HTML Emmet Cheat Sheet

A complete list of Emmet shortcuts for HTML with examples.

---

## 1. Basic Tags
| Shortcut | Expands To |
|----------|------------|
| `html:5` or `!` | Basic HTML5 template |
| `div` | `<div></div>` |
| `p` | `<p></p>` |
| `h1` | `<h1></h1>` |
| `span` | `<span></span>` |
| `a` | `<a href=""></a>` |
| `img` | `<img src="" alt="">` |
| `ul>li` | `<ul><li></li></ul>` |
| `ol>li` | `<ol><li></li></ol>` |

---

## 2. Multiplication / Repetition
| Shortcut | Expands To |
|----------|------------|
| `div*4` | 4 `<div></div>` elements |
| `li*5` | 5 `<li></li>` elements |
| `.product$*4` | `<div class="product1"></div>` … `<div class="product4"></div>` |
| `ul>li.item$*3` | 3 list items with classes `item1`, `item2`, `item3` inside `<ul>` |

---

## 3. Nesting
| Shortcut | Expands To |
|----------|------------|
| `ul>li` | `<ul><li></li></ul>` |
| `div>p>span` | `<div><p><span></span></p></div>` |
| `header>nav>ul>li*3` | `<header><nav><ul><li></li><li></li><li></li></ul></nav></header>` |

---

## 4. ID and Class
| Shortcut | Expands To |
|----------|------------|
| `#header` | `<div id="header"></div>` |
| `.container` | `<div class="container"></div>` |
| `ul#nav>li.item*4` | `<ul id="nav"><li class="item"></li>…</ul>` |

---

## 5. Text Content
| Shortcut | Expands To |
|----------|------------|
| `p{Hello World}` | `<p>Hello World</p>` |
| `a{Click Here}` | `<a href="">Click Here</a>` |

---

## 6. Sibling Operator (`+`)
| Shortcut | Expands To |
|----------|------------|
| `h1+p` | `<h1></h1><p></p>` |
| `div+div+div` | 3 `<div></div>` in a row |

---

## 7. Grouping (`()`)
| Shortcut | Expands To |
|----------|------------|
| `(header>nav>ul>li*3)+footer` | Header section with nav and footer after it |

---

## 8. Attributes
| Shortcut | Expands To |
|----------|------------|
| `a[href="#"]` | `<a href="#"></a>` |
| `img[src="img.jpg" alt="image"]` | `<img src="img.jpg" alt="image">` |

---

## 9. Climb-up (`^`)
| Shortcut | Expands To |
|----------|------------|
| `div>p>span^b` | `<div><p><span></span></p><b></b></div>` |

---

## 10. Lorem Ipsum
| Shortcut | Expands To |
|----------|------------|
| `lorem` | `Lorem ipsum dolor sit amet…` |
| `p>lorem10` | `<p>Lorem ipsum…10 words</p>` |

---

## 11. Example Combining Multiple Features
Shortcut:
```
ul#menu>li.item$*4>a{Item $}
```
Expands to:
```html
<ul id="menu">
  <li class="item1"><a href="">Item 1</a></li>
  <li class="item2"><a href="">Item 2</a></li>
  <li class="item3"><a href="">Item 3</a></li>
  <li class="item4"><a href="">Item 4</a></li>
</ul>
```

---

This file contains **all essential Emmet shortcuts for HTML** including tags, nesting, repetition, IDs, classes, attributes, text, and lorem ipsum.

You can save this as `HTML_Emmet_CheatSheet.md` or `HTML_Emmet_CheatSheet.txt` and keep it as a reference.


# 1. Apple Layout Grid System

Apple usually uses a **very wide container with big margins**.

### Desktop container

```
max-width: 980px
max-width: 1100px
max-width: 1200px
```

But the **page itself is much wider**, leaving large whitespace on both sides.

Example:

```css
.container{
  max-width:1100px;
  margin:0 auto;
  padding:0 40px;
}
```

Large side padding is very important.

Typical:

```
mobile: 20px
tablet: 32px
desktop: 40–48px
```

---

# 2. Apple Typography Scale

Apple typography is **very large compared to SaaS sites**.

Typical scale:

| Type          | Size    |
| ------------- | ------- |
| Hero heading  | 64–80px |
| Section title | 40–56px |
| Card title    | 24–32px |
| Body text     | 17–21px |

Example:

```css
.hero-title{
  font-size:clamp(40px,6vw,72px);
}

.section-title{
  font-size:clamp(28px,4vw,48px);
}

.body-text{
  font-size:18px;
}
```

Notice Apple loves **fluid typography using `clamp()`**.

---

# 3. Apple Spacing System (Realistic)

Apple sections breathe **a lot**.

Typical spacing:

| Element         | Size      |
| --------------- | --------- |
| Section spacing | 120–200px |
| Card padding    | 48–64px   |
| Grid gap        | 40–64px   |
| Text spacing    | 16–24px   |

Example:

```css
.section{
  padding:160px 0;
}
```

---

# 4. Apple Card Layout

Apple cards usually follow this pattern:

```
Card
 ├ Image
 ├ Title
 ├ Description
 └ CTA
```

Spacing example:

```
Image → Title : 24px
Title → Text : 12px
Text → Button : 24px
```

CSS example:

```css
.card{
  padding:56px;
  border-radius:28px;
  background:#f5f5f7;
}

.card-content{
  display:flex;
  flex-direction:column;
  gap:16px;
}
```

---

# 5. Apple Grid Layout

Apple uses **very simple grids**.

Example:

```css
.cards{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:48px;
}
```

Responsive version:

```css
.cards{
  grid-template-columns:1fr;
}

@media (min-width:768px){
  .cards{
    grid-template-columns:repeat(2,1fr);
  }
}

@media (min-width:1200px){
  .cards{
    grid-template-columns:repeat(3,1fr);
  }
}
```

---

# 6. Apple Border Radius

Apple uses **soft but noticeable radius**.

Typical:

```
16px
20px
24px
28px
```

Example:

```css
.card{
  border-radius:28px;
}
```

---

# 7. Apple Section Example (Complete)

```css
.section{
  padding:clamp(80px,10vw,200px) 0;
}

.container{
  max-width:1100px;
  margin:auto;
  padding:0 40px;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:clamp(24px,4vw,64px);
}

.card{
  padding:clamp(32px,4vw,64px);
  border-radius:28px;
  background:#f5f5f7;
}
```

---

# 8. The Secret Apple Rule

The most important design rule Apple follows:

```
Outer spacing >> inner spacing
```

Example:

```
Section padding: 160px
Card padding: 56px
Text spacing: 16px
```

This creates the **luxury breathing space**.

---

# 9. What Makes Apple UI Feel Premium

It’s mainly:

✔ huge whitespace
✔ large typography
✔ minimal elements
✔ strong grid alignment

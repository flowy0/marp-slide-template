---
marp: true
theme: default
_class: lead
paginate: true
backgroundColor: #fff
backgroundImage: url('https://marp.app/assets/hero-background.svg')
footer: '© 2024' 
transition: fade
style: |
  section::after {
    /* Layout of pagination content */
    box-sizing: border-box;
    text-align: right;
    width: 120px;
    height: 120px;
    line-height: 140px;
    padding: 20px;
  }
  .columns3 {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 3fr));
    gap: 1rem;
  }
  .columns2 {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 3fr));
    gap: 1rem;
  }
  .redtext{
    color: red
  }

---
<style>
  section {
    font-family:'Arial';
    font-size: 26px;
    color: #595959; 
  }
  img[alt~="center"] {
  display: block;
  margin: 0 auto;
  }
  h1 {
    font-size: 42px; /* equivalent to font size 40 */
    color: #595959;
  }
  h2 {
    font-size: 37px 
  }
</style>



![bg](assets/specific-background.jpg) 
<div class="columns3">
<div>
</div>
<div>
</div>
<div>

<br> <br> <br> <br> <br> <br> <br>

# Presentation Title

Presenter Name
Date
</div>
</div>


---

# Agenda

0. Item 0
1. Item 1
---


# Example of Headers and Code Snippets

### Header Description
#### Title of Code Snippet
```python
your code snippet here
```


---

# Customised Font Size for Slide Content

<style scoped>section { font-size: 22px ; text-align: left;}</style>

- your content here (custom font size for this slide)

<!-- Speaker Notes Here will be shown in HTML exports
-->


---
# Example of 2 Column Layout
- Text within the `<div class="columns2">` has to be written in HTML

<br> <br>
<div class="columns2">


<div>
First Column 
<br>
- your content here
- </div>

<div>
2nd column 
<br>
- your content here
</div>

</div>

---
# Example of 3 Column Layout
- Text within the `<div class="columns3">` has to be written in HTML

<br> <br>
<div class="columns3">


<div>
First Column 
<br>
- your content here
- </div>

<div>
2nd column 
<br>
- your content here
</div>

<div>
3rd column 
<br>
- your content here
</div>
</div>



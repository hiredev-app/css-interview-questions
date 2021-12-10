![Image header](https://github.com/hiredev-app/css-interview-questions/blob/main/image-header.png?raw=true)

## Questions

<details>
<summary>The four aspects that make up the box model are: | <i>Multi choice answer</i></summary>

- [x] Padding
- [ ] Typography
- [x] Margin
- [x] Border
- [x] Content
- [ ] Color</details>

<details>
<summary>Select the correct pairs of text formatting and corresponding CSS properties: | <i>Multi choice answer</i></summary>

- [ ] Italic - font-weight: bold;
- [x] Underline - text-decoration: underline;
- [x] Bold - font-weight: bold;
- [x] Italic - font-style: italic;</details>

<details>
<summary>Select legal CSS color values: | <i>Multi choice answer</i></summary>

- [x] #00ff00
- [x] hsla(120, 100%, 50%, 0.3)
- [ ] 00ff00
- [x] rgba(0, 255, 0, 0.3)</details>

<details>
<summary>Select legal CSS color values: | <i>Multi choice answer</i></summary>

- [x] blue
- [x] hsl(120, 100%, 50%)
- [ ] cmyk(1, 0, 1, 0)
- [x] rgb(0, 255, 0)</details>

<details>
<summary>Consider following CSS and HTML. How big will the vertical space between the paragraphs be? | <i>Single choice answer</i></summary>

- [ ] 56px
- [ ] 24px
- [x] 32px
- [ ] 44px
~~~html
<style>
  p {
    margin-top: 32px;
    margin-bottom: 24px;
  }
</style>
<p>Paragraph One</p>
<p>Paragraph Two</p>
~~~
</details>

<details>
<summary>Consider following CSS and HTML. How big will the vertical space between the paragraphs be? | <i>Single choice answer</i></summary>

- [ ] 56px
- [ ] 24px
- [x] 32px
- [ ] 44px
~~~html
<style>
  p {
    margin-top: 32px;
    margin-bottom: 24px;
  }
</style>
<div>
  <p>Paragraph One</p>
</div>
<p>Paragraph Two</p>
~~~
</details>

<details>
<summary>Consider following CSS and HTML. Will the child and parent margins collapse? | <i>Single choice answer</i></summary>

- [ ] No
- [x] Yes
~~~html
<style>
  .parent {
    margin-top: 72px;
  }
  .child {
    margin-top: 24px;
  }
</style>
<div class="parent">
  <p class="child">Paragraph One</p>
</div>
~~~
</details>

<details>
<summary>Consider following CSS and HTML. How big will the horizontal space between the paragraphs be? | <i>Single choice answer</i></summary>

- [x] 56px
- [ ] 24px
- [ ] 32px
- [ ] 44px
~~~html
<style>
  p {
    margin-left: 32px;
    margin-right: 24px;
  }
</style>
<p>Paragraph One</p>
<p>Paragraph Two</p>
~~~
</details>

<details>
<summary>Select correct scenarios to form a new stacking context: | <i>Multi choice answer</i></summary>

- [ ] <body> element of the document.
- [ ] Element with a transparent background-color, for example background-color:rgba(255, 0, 0, 0).
- [x] Element with a opacity value less than 1.
- [x] Element with a isolation value isolate.
- [x] Element with a position value absolute or relative and z-index value other than auto.</details>

<details>
<summary>Select correct scenarios to form a new stacking context: | <i>Multi choice answer</i></summary>

- [x] Root element of the document (<html>).
- [x] Element that is a child of a flex container, with z-index value other than auto.
- [x] Element that is a child of a grid container, with z-index value other than auto.
- [ ] Element that is a child of a block container.
- [x] Element with a position value fixed or sticky.</details>

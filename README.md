# Практическая работа по теме "CSS Селекторы"
---
[Упражение №1](https://artemchubatyi.github.io/selectors/index.html)

СSS код для первого задания:

```css
:root {
    --color_1: #231A31;
    --color_2: #E42F45;
    --color_3: #8AB2FF;
    --color_4: #F1C40F;
    --color_5: #B7569A;
    --color_6: #E4F091;
    --color_7: #085F63;
    --color_8: #887575;
}
div:first-of-type p + p {
    background-color: var(--color_1);
}
div:first-of-type p + h2 {
    background-color: var(--color_2);
}
span ~ h2 {
    background-color: var(--color_3);
}
div ~ h2 {
    background-color: var(--color_4);
}
```
---
[Упражение №2](https://artemchubatyi.github.io/selectors/index2.html)

СSS код для второго задания:

```css
a[href="about"] {
    background-color: var(--color_6);
}
a[href$=".html"] {
    background-color: var(--color_7);
}
p:not([class]) {
    background-color: var(--color_3);
}
*[data-href] {
    color: var(--color_4);
}
a:first-of-type {
    background-color: var(--color_5);
}
*[data-href$=" highlight_me"] {
    text-decoration: underline;
}
```
---
[Упражение №3](https://artemchubatyi.github.io/selectors/index3.html)

СSS код для третего задания:
```css
a.www, a:visited {
    color: var(--color_6);
}   
a:active:not(.www) {
    color: var(--color_7);
}
a:hover {
    background-color: var(--color_1);
}
input:checked + label {
    text-decoration: underline;
}
input[type=text]:focus {
    border: 1px solid blue;
}
input:required {
    background-color: #efefef;
}
```
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
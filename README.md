# \<tsante-dropdown\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/telecomsante/tsante-dropdown)
![](https://img.shields.io/badge/polymer-3.x-blue.svg)
![](https://img.shields.io/badge/npm%20package-2.0.0--pre.3-green.svg)

version : 0.1.2

A simple dropdown menu

![][hero]

## install

```
npm i @teleconsante/tsante-dropdown@2.0.0-pre.3
```

## Quick example

<!--
```
<custom-element-demo>
  <template>
    <link rel="import" href="tsante-dropdown.html">
    <style>
        tsante-dropdown {
            font-family: Roboto, Arial, helvetica;
        }

        ul {
            margin: 0;
            padding: 0;
            list-style-type: none;
            width: 200px;
        }

        li {
            height: 35px;
            display: flex;
            align-items: center;
            padding: 0px 8px;
        }

        li:hover {
            background: dimgray;
            color: white;
        }

        button {
            border: 1px solid lightgray;
            padding: 5px 8px;
            outline: none;
            min-width:90px;
            margin: 0;
        }

        .container {
            height: 250px;
            margin: 20px
        }
    </style>
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<div class="container">
<tsante-dropdown horizontal-align='left' opened>
    <button>Trigger</button>
    <ul slot="dropdown-content">
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
    </ul>
</tsante-dropdown>
</div>
```

The component is licensed under the [ISC License](LICENSE.md)

## dev mode

```
npm install
npm start
```

the documentation should then be available on : 

http://127.0.0.1:8081/components/tsante-dropdown/

[hero]: https://raw.githubusercontent.com/telecomsante/tsante-dropdown/HEAD/hero.gif

# <div align="center">Simple HTML Invoice Template</div>

<p align="center">
<a href="https://validator.w3.org/check?uri=https%3A%2F%2Fsparksuite.github.io%2Fsimple-html-invoice-template%2F"><img alt="W3C Validation" src="https://img.shields.io/w3c-validation/default?targetUrl=https%3A%2F%2Fsparksuite.github.io%2Fsimple-html-invoice-template%2F"></a>
<a href="https://github.com/prettier/prettier"><img alt="license" src="https://img.shields.io/badge/code_style-prettier-ff69b4.svg"></a>
<a href="https://github.com/sparksuite/simple-html-invoice-template/blob/master/LICENSE"><img alt="license" src="https://img.shields.io/github/license/sparksuite/simple-html-invoice-template"></a>
</p>

A modern, clean, and very simple responsive HTML invoice template, because sometimes you just need something quick and simple.

- ✨ Simple design
- 📱 Responsive
- 🔧 Easily customizable
- 🌍 RTL support

## Demo
[Find a demo here](https://sparksuite.github.io/simple-html-invoice-template/)

## How to use
Open the [invoice.html](https://github.com/sparksuite/simple-html-invoice-template/blob/master/invoice.html) file and use its HTML and CSS in your application.

## Printer-friendly styling
By default, the appearance of the invoice when printed is the same as when viewed on a screen. If the invoice is the primary or only element on the page, you may want to consider removing the box-shadow and border, and letting the invoice extend the full width of the page. That can be accomplished with this CSS:
```css
@media print {
  .invoice-box {
    max-width: unset;
    box-shadow: none;
    border: 0px;
  }
}
```

## RTL support
Replace `<div class="invoice-box">` with `<div class="invoice-box rtl">`

## Preview
<img width="1325" alt="Preview" src="https://github.com/sparksuite/simple-html-invoice-template/assets/3850064/5d34c8d2-5ac4-45cf-93f9-1eeaaf23765e">


## Contributing
We love contributions! Contributing is easy; [learn how](https://github.com/sparksuite/simple-html-invoice-template/blob/master/CONTRIBUTING.md).


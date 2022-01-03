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
By default, the layout of the invoice when printed is equal to the regular layout. Optionally, the box-shadow and border line can be removed when printing, to give a more invoice-like feeling.
<p align="center">
  <img alt="Without printer friendly styling" src="https://user-images.githubusercontent.com/22718003/147985007-fb298dd8-b88c-4407-bdea-26fe2c9f595c.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="With printer-friendly styling" src="https://user-images.githubusercontent.com/22718003/147985049-ebf70654-ace3-4e49-b7e1-9fb4d3583163.png" width="45%">
</p>

Example:
```
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
<img width="1325" alt="Preview" src="https://user-images.githubusercontent.com/3850064/111213188-8190a780-859e-11eb-99b5-e038eac4b172.png">

## Contributing
We love contributions! Contributing is easy; [learn how](https://github.com/sparksuite/simple-html-invoice-template/blob/master/CONTRIBUTING.md).


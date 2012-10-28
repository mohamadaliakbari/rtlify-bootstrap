rtlify-bootstrap
================

Provide bootstrap-rtl.css to load after main bootstrap and RTLify layout.

Instalation:

1- Download orginal botstrap files from http://twitter.github.com/bootstrap/
2- Download the same version of rtlify-bootstrap.
3- Load rtlify-bootstrap CSS files right after their equivalent files in main bootstrap files.

So you have something like:

<link href="assets/css/bootstrap.css" rel="stylesheet">
<link href="assets/css/bootstrap-rtl.css" rel="stylesheet">

Notices:
1- AS rtlify-bootstrap just override specific properties you can still customize your Bootstrap using: http://twitter.github.com/bootstrap/customize.html
2- Responsive version is under active development.
3- A modified version of bootstrap.css is involved in repository to see how you can RTLify other version of Bootstrap.
4- You can using exists tools to minify CSS file and produce .min files.

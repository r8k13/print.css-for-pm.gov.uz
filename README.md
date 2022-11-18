# print.css-for-pm.gov.uz
Printer-friendly web page with CSS

**GOAL: To make the printing result of the web page more compact and readable**

Usually, several sheets of [A4](https://papersizes.io/a/a4) paper are required to print out the tracking information from the virtual reception pm.gov.uz web page.

Just take a look at the only two gifs below and compare the default and optimized print result.

**BEFORE:**

![before: default stylesheets for printing tracking information from virtual reception pm.gov.uz web page](b.gif)

**AFTER:**

![after: modified and printer-friendly stylesheets for printing tracking information from virtual reception pm.gov.uz web page](a.gif)

### Installation
The print.css style sheet can be added to the HTML <head> and preferably after other style sheets:

`<link href="print.css" rel="stylesheet" type="text/css" media="print">`

Alternatively, print styles can be included within an existing CSS file using `@media print { ... }` rules.

### Resources
ru: [Инструкция: CSS-оптимизация веб-страницы для печати](https://vc.ru/flood/23660-print-style-sheets) | en: [Origin](https://www.matuzo.at/blog/i-totally-forgot-about-print-style-sheets/) by Manuel Matuzovic

[CSS: The Perfect Print Stylesheet](https://www.jotform.com/blog/css-perfect-print-stylesheet-98272/) by Andreas Hecht

### Contributing
Contributions or constructive feedback, are welcome.

# Contributing to Gonnamake

Looking to contribute something to Gonnamake? **Here's how you can help.**



## Reporting issues

We only accept issues that are bug reports or feature requests. Bugs must be isolated and reproducible problems that we can fix within the Gonnamake core. Please read the following guidelines before opening any issue.

1. **Search for existing issues.** We get a lot of duplicate issues, and you'd help us out a lot by first checking if someone else has reported the same issue. Moreover, the issue may have already been resolved with a fix available.
2. **Create an isolated and reproducible test case.** Be sure the problem exists in Gonnamake's code with a [reduced test case](http://css-tricks.com/reduced-test-cases/) that should be included in each bug report.
3. **Include a live example.** Make use of CodePen or jsFiddle to share your isolated test cases.
4. **Share as much information as possible.** Include operating system and version, browser and version, version of Gonnamake, customized or vanilla build, etc. where appropriate. Also include steps to reproduce the bug.



## Coding standards: HTML

- Four spaces for indentation, never tabs
- Double quotes only, never single quotes
- Always use proper indentation
- Use tags and elements appropriate for an HTML5 doctype (e.g., self-closing tags)



## Coding standards: SCSS

- Adhere to the [Recess CSS property order](http://markdotto.com/2011/11/29/css-property-order/)
- Multiple-line approach (one property and value per line)
- Always a space after a property's colon (.e.g, `display: block;` and not `display:block;`)
- End all lines with a semi-colon
- For multiple, comma-separated selectors, place each selector on it's own line
- Attribute selectors, like `input[type="text"]` should always wrap the attribute's value in double quotes, for consistency and safety (see this [blog post on unquoted attribute values](http://mathiasbynens.be/notes/unquoted-attribute-values) that can lead to XSS attacks).



## Coding standards: JS

-[24 JavaScript Best Practices not to forget](http://net.tutsplus.com/tutorials/javascript-ajax/24-javascript-best-practices-for-beginners/)
- 4 spaces (no tabs)
- Always, Always Use Semicolons
- Object-Oriented JavaScript
- Always Consider the Future



## License

By contributing your code, you agree to license your contribution under the terms of the [GPLv2](LICENSE)
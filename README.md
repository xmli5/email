# The XMLi5 Email

<p>
  <a href="http://validator.w3.org/check?uri=referer">
    <img src="http://www.w3.org/Icons/valid-xhtml10" alt="Valid XHTML 1.0 Transitional" height="31" width="88" />
  </a>
  <a href="http://jigsaw.w3.org/css-validator/check/referer">
    <img style="border:0;width:88px;height:31px" src="http://jigsaw.w3.org/css-validator/images/vcss-blue" alt="Valid CSS!" />
  </a>
</p>

This thing is designed to be bulletproof.

- It uses percentages to ensure that the email is reasonably responsive without relying on hacks and unreliable tricks.

- It works without a DOCTYPE, and is supplied with the XHTML1 Transitional DOCTYPE for reliability between the few clients that don't strip the DOCTYPE.

- It uses only `table`,`tr` and `td` elements and `align`/`valign` attributes for layout.

- It's composed in polyglot HTML, enabling the document to be transmitted as `application/xml+xhtml` with an amendment to the `http-equiv` meta tag specifying the MIME type.

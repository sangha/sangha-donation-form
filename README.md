# Embeddable donation form for Sangha

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/sangha/sangha-donation-form)

## Embed in your page

```html
<script src="https://donate.techcultivation.org/embed/bower_components/webcomponentsjs/webcomponents-loader.js"></script>
<link rel="import" href="https://donate.techcultivation.org/embed/sangha-donation-form.html">

<sangha-donation-form
  api-url="https://api.sangha.techcultivation.org/v1"
  project-ids='[1]'
  buttons='[5,10,20]'
  default-amount='5'>

  <!-- non JS Fallback -->
  <h3>Enable Javascript for interactive donation process</h3>
  <ul>
    <li>Donate to the following address with the following reference</li>
    <li>Static paypal button</li>
    <li>Link to donation receipt</li>
    <li>Mail address for help</li>
  </ul>
</sangha-donation-form>
```

## Development

```bash
# Get dependencies
$ npm install

# Demo site
$ npm start

# Run tests
$ npm test
```

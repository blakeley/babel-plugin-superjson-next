<p style="display: flex; justify-content: center; align-items: center;">
  <img alt="superjson" src="https://github.com/blitz-js/superjson/raw/main/docs/superjson.png" width="180" />
  <span style="margin: 12px; font-size: 24px; font-weight: 100">X</span>
  <img alt="next.js" src="https://seeklogo.com/images/N/next-js-logo-7929BCD36F-seeklogo.com.png" width="90" />
</p>

<p align="center">
  Automatically transform your Next.js Pages to use SuperJSON.
  Supports <code>getStaticProps</code> & <code>getServerSideProps</code>.
</p>

<p align="center">
  <!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
<a href="#contributors"><img src="https://img.shields.io/badge/all_contributors-2-orange.svg?style=flat-square" alt="All Contributors"/></a>
<!-- ALL-CONTRIBUTORS-BADGE:END -->
  <a href="https://www.npmjs.com/package/otion">
    <img alt="npm" src="https://img.shields.io/npm/v/babel-plugin-superjson-next" />
  </a>

  <a href="https://github.com/blitz-js/superjson/actions">
    <img
      alt="CI"
      src="https://github.com/blitz-js/superjson/workflows/CI/badge.svg"
    />
  </a>
</p>

## Getting started

Install the library with your package manager of choice, e.g.:

```
yarn add -D babel-plugin-superjson-next
```

Add the plugin to your `.babelrc`.
If you don't have one, create it.


```json5
{
  "presets": ["next/babel"],
  "plugins": [
    ...
    "superjson-next" // 👈
  ]
}
```

That's it! Now you're free to use all values and type supported by SuperJSON in your Next.js Components.

<!-- Potential new section: how it works -->

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):
<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://github.com/Skn0tt"><img src="https://avatars1.githubusercontent.com/u/14912729?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Simon Knott</b></sub></a><br /><a href="https://github.com/skn0tt/babel-plugin-superjson-next/commits?author=Skn0tt" title="Code">💻</a> <a href="#video-Skn0tt" title="Videos">📹</a> <a href="#ideas-Skn0tt" title="Ideas, Planning, & Feedback">🤔</a> <a href="#maintenance-Skn0tt" title="Maintenance">🚧</a></td>
    <td align="center"><a href="https://twitter.com/flybayer"><img src="https://avatars3.githubusercontent.com/u/8813276?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Brandon Bayer</b></sub></a><br /><a href="#ideas-flybayer" title="Ideas, Planning, & Feedback">🤔</a> <a href="#talk-flybayer" title="Talks">📢</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!

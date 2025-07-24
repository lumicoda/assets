![GitHub](https://img.shields.io/github/license/lumicoda/assets?style=flat-square)
![GitHub repo size](https://img.shields.io/github/repo-size/lumicoda/assets?style=flat-square)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/lumicoda/assets)
![GitHub all releases](https://img.shields.io/github/downloads/lumicoda/assets/total)
[![](https://data.jsdelivr.com/v1/package/gh/lumicoda/assets/badge)](https://www.jsdelivr.com/package/gh/lumicoda/assets)


<p align="center">
    <img alt="at-article logo" title="at-article logo" src="https://img.icons8.com/color/344/branding-iron.png" width="200">
</p>
<div align="center">
  <strong>Assets and branding for Lumicoda</strong>
</div>
<div align="center">
  This repository contains our static assets and serves them to our <a href="#endpoints">Endpoints</a>.
</div>

<div align="center">
  <h3>
    <a href="#endpoints">Endpoints</a>
    <span> | </span>
    <a href="https://lumicoda.github.io/assets/">Documentation</a>
    <span> | </span>
    <a href="#contributing">
      Contributing
    </a>
  </h3>
</div>

<div align="center">
  <sub>Built with ❤︎ by
  <a href="https://lumicoda.ch">Lumicoda</a> and
  <a href="https://github.com/lumicoda/assets/contributors">
    contributors
  </a>
  </sub>
</div>


## Table of Contents

- [Assets](#assets)
  - [Endpoints](#endpoints)
  - [Usage](#usage)
  - [Logo](#logo)
  - [Images](#images)
- [Colors](#colors)
- [Avatar](#avatar)
- [Contributing](#contributing)
- [License](#license)

## Assets
### Endpoints

We store our static assets in this repository, GitHub Pages publishes it and jsDelivr CDN fetch it.

* **Github Pages**: https://lumicoda.github.io/assets
* **jsDelivr CDN**: https://cdn.jsdelivr.net/gh/lumicoda/assets/
* **jsDelivr package**: https://www.jsdelivr.com/package/gh/lumicoda/assets
* **Statically CDN**: https://cdn.statically.io/gh/lumicoda/assets/master/logo/logo-lumicoda.svg

### Usage

For example, our logo is available at :

* https://lumicoda.github.io/assets/logo/logo-lumicoda.svg
* https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda.svg

With jsDelivr CDN, you can choose a specific release or a specific git commit hash:

* https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda.svg
* https://cdn.jsdelivr.net/gh/lumicoda/assets@b96d07edc4c0debe1fe38da344137accf6a55dba/logo/logo-lumicoda.svg

With Statically CDN, you can choose a specific branch, tag or git commit hash:
* https://cdn.statically.io/gh/lumicoda/assets/master/logo/logo-lumicoda.svg

### Logo

<table>
  <tr>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda.svg">
        <img alt="color logo" src="./logo/logo-lumicoda.svg" width="100">
      </a>
      <div>Color</div>
    </td>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda-white.svg">
        <img alt="white logo" src="./logo/logo-lumicoda-white.svg" width="100" style="background:#0d1821;">
      </a>
      <div>White</div>
    </td>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda-black.svg">
        <img alt="black logo" src="./logo/logo-lumicoda-black.svg" width="100" style="background:#0d1821;">
      </a>
      <div>Black</div>
    </td>
  </tr>
  </table>
  <table>
  <tr>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda-square.svg">
        <img alt="square logo" src="./logo/logo-lumicoda-square.svg" width="100">
      </a>
      <div>Square</div>
    </td>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda-square-gray.svg">
        <img alt="square gray logo" src="./logo/logo-lumicoda-square-gray.svg" width="100">
      </a>
      <div>Square grey</div>
    </td>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/logo/logo-lumicoda-square-white.svg">
        <img alt="square white logo" src="./logo/logo-lumicoda-square-white.svg" width="100">
      </a>
      <div>Square White</div>
    </td>
  </tr>
</table>

### Favicon

<table>
  <tr>
    <td style="text-align: center;">
      <a href="https://cdn.jsdelivr.net/gh/lumicoda/assets@latest/favicon/favicon.ico">
        <img alt="color logo" src="./favicon/favicon.ico" height="32">
      </a>
      <div>Favicon logo</div>
    </td>
  </tr>
</table>

### Images
- No images for the moment

## Colors

<table>
  <tr>
    <td style="text-align: center">
      <img alt="" height="50" width="50" src="https://dummyimage.com/50x50/002C73/ffffff.png&text=+">
      <div><code>#002C73</code></div>
    </td>
    <td style="text-align: center">
      <img alt="" height="50" width="50" src="https://dummyimage.com/50x50/FFD166/ffffff.png&text=+">
      <div><code>#FFD166</code></div>
    </td>
  </tr>
</table>

Thanks to [dummyimmage](https://github.com/kingkool68/dummyimage) for the square generation.


## Images optimization

Optimize and resize images effortlessly with [Statically](https://statically.io/docs/using-images/).
* **Endpoint**: `https://cdn.statically.io/img/:domain/h=:pixel,q=:percentage/:image`
* https://cdn.statically.io/img/lumicoda.ch/w=300,h=500/foo.jpg
* https://cdn.statically.io/img/lumicoda.ch/f=auto,w=600,h=400/bar.jpg

## Contributing

We’re really happy to accept contributions from the community, that’s the main reason why we open-sourced it! There are many ways to contribute, even if you’re not a technical person.

1. Fork it (<https://github.com/lumicoda/assets/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

## License

The trademarks, logos and other static assets ("Marks") displayed on this repository are the property of Lumicoda. You are not permitted to use these Marks without the prior written consent of Lumicoda.

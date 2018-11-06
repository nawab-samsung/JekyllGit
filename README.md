# STAR Website
Build the future with STAR platform. STAR website will help you get started with STAR platform developement, by providing informative guides to its general architecture, API references, samples, and everything else you might need. Visit [http://star.samsung.net](http://star.samsung.net) to find what you can make with our core AI technologies.

This repository contains the contents for STAR website. The original documents and components used for building the site can be found in this repository, which are mostly written in _markdown_ format. The space is open for all STAR platform developers. You can make changes in the website by pushing commits to the repository.

## Quick Start

- #### Running a build locally
  To build a site locally from source, see [**Installation**](https://github.sec.samsung.net/STAR/STAR-Website/wiki/Installation) for instructions.

- #### GitHub Pages
  Without building a site locally from source, you can make a private fork of this repository to publish your own copy.
  1. Fork this repository into your personal space.
  2. In the repository settings, make sure your site is being hosted by GitHub Pages.
  3. Your site is published at `https://github.sec.samsung.net/pages/[your account]/STAR-Website`.

## How to Contribute
We encourage contributions from community members. All members can open an issue or a pull request to improve the site at any time. For more information about contributing, please see the [**STAR Community Contributing Guidelines**](https://github.sec.samsung.net/RS7-STAR/STAR-Platform/blob/master/HOW-TO/contributing.md). Also please feel free to request additional features or ask questions/leave comments by posting an issue.

Once a pull request is made, the changes will be available at our [**staging server**](http://10.113.68.74) immediately after merge. If the staging server is not accessible at your location, please make a firewall registration request by filing an issue.

## Architecture
![STAR website release process](https://github.sec.samsung.net/pages/STAR/STAR-Website/assets/wiki/star_website.png)

As depicted in the figure, we use a staging server at [10.113.68.74](http://10.113.68.74) and a release server at [star.samsung.net](http://star.samsung.net) to release the STAR website. The staging server stages changes made by community members which are immediately pulled from the repository after a pull request is merged. The changes are released to the public after a review process.

![Documentation generation](https://github.sec.samsung.net/pages/STAR/STAR-Website/assets/wiki/basic-documentation-generation.jpg)

Markdown contents are converted into HTML documents using Jekyll by the staging server (as the GitHub Pages does). For any details, please see our [**wiki**](https://github.sec.samsung.net/STAR/STAR-Website/wiki).

## Documentation
Additional information about the site and documentation guides can be found at our [**wiki**](https://github.sec.samsung.net/STAR/STAR-Website/wiki). Please refer to the guides if you are writing documents in markdown.


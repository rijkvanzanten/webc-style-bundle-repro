# WebC bundled styles reproduction

Minimal reproduction for issue https://github.com/11ty/eleventy-plugin-webc/issues/33

## Usage

Clone the repo, `npm install` to install the dependencies, and `eleventy` to build the dist.

Note how the output `_site/using-home/index.html` has its `<style>` nested in the webcomponent, whereas `_site/using-root/index.html` is correctly bundled to the head `<style>` tag.
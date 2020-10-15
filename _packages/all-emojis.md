---
package_name: "all-emojis"
package_title: "All Emojis"
package_desc: "All emojis, with alt names, provided by gemoji"
package_version: "0.1.0"
package_author: "FoxxMD"
package_original_repo: "https://github.com/FoxxMD/espanso-all-emojis"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
featured: true
---

# {{ page.package_title }}

All emojis, with all non-conflicting alt names, provided by [gemoji](https://github.com/github/gemoji).

## Usage

To use this package, just type the name of the emoji between two colons.
For example, to use the `smile` emoji 😄, type: `:smile:`

A list of all the possibile emoji expansions can be found [here](https://www.webfx.com/tools/emoji-cheat-sheet/).

 **Note**: all underscores have been replaced with spaces to make them easier to type. For example `:neutral_face:` is `:neutral face:` in the package.

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

## Package Details

Repository: <{{ page.package_original_repo }}>

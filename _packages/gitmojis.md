---
package_name: "gitmojis"
package_title: "Gitmojis support"
package_desc: "Translate gitmoji into emojis"
package_version: "2.0.0"
package_author: "Lyokolux"
package_original_repo: "https://github.com/Lyokolux/espanso-gitmojis"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

A package for [Gitmojis](https://gitmoji.carloscuesta.me/).

## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

That's all. You can start using the package. Open your favorite editor and type `:sparkles:` to test!

## Triggers

Every gitmoji can be written and replaced by the corresponding emoji. The list is available on the webpage of [Gitmojis](https://gitmoji.carloscuesta.me/).

## Run the build script

```
make install
make run
```

---
package_name: "greek-letters"
package_title: "Greek Letters: Upper and Lower"
package_desc: "A simple way to type Greek upper and lowercase letters"
package_version: "0.1.0"
package_author: "Billy McCann"
package_original_repo: "https://github.com/exergonic/espanso-package-greek-letters"
package_repo: "https://github.com/federico-terzi/espanso-hub-core"
is_core: true
---

# {{ page.package_title }}

This plugin allows Espanso users to expand keystrokes such as <kbd>:ga</kbd> into the
Greek letter alpha α.


## Installation

```
espanso install {{ page.package_name }} {% if page.is_core == false %}--external{% endif %}
espanso restart
```

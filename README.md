[![img](https://img.shields.io/badge/code.gouv.fr-contributif-blue.svg)](https://code.gouv.fr/documentation/#quels-degres-douverture-pour-les-codes-sources)
[![Software License](https://img.shields.io/badge/Licence-EPL-green.svg)](https://githut.com/codegouvfr/faq-dsfr/tree/main/item/LICENSES/LICENSE.EPL-2.0.txt)

# Install

Assuming [bbin](https://github.com/babashka/bbin) is installed:

    bbin install https://raw.githubusercontent.com/codegouvfr/subscribe/refs/heads/main/faq-dsfr.clj

Then run:

    faq-dsfr
	
You can then check the application on http://localhost:8080

# FAQ as json

    Here is an example json with "title", "content" and "path", which
    last item is used to infer the category:

    [ {
      "title" : "FAQ title",
      "content" : "<p>Content as HTML",
      "path" : [ "Section", "Subsection (as category)" ]
    } ]

# Example

![FAQ screenshot](faq.png)

See [code.gouv.fr/faq](https://code.gouv.fr/faq).

# Requirements

`faq-dsfr.clj` is a [Clojure](https://clojure.org)
[Babashka](https://babashka.org) script. We recommend installing it
with [bbin](https://github.com/babashka/bbin). To install everything:

    brew install babashka/brew/bbin

For detailed installation instructions:

-   [Install Clojure](https://clojure.org/guides/install_clojure)
-   [Install babashka](https://github.com/babashka/babashka#installation)
-   [Install bbin](https://github.com/babashka/bbin#installation)

# [Contributing](CONTRIBUTING.md)
# Support the Clojure(script) ecosystem

If you like Clojure(script), you can support the ecosystem by making a
donation to [clojuriststogether.org](https://www.clojuriststogether.org).

# License

2025 DINUM, Bastien Guerry.

The code is published under the [EPL 2.0 license](LICENSES/LICENSE.EPL-2.0.txt).

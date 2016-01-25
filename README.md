# Hammurabi's Code

Lawrence Lessig once said that ["Code is Law"](http://harvardmagazine.com/2000/01/code-is-law-html); well "Law is also Code" or at least it will be treated as such here. This project represents an attempt to collect all bills and laws in one organized place. The Hammurabi Project consists of three repos, this one is where the text of the legislation will live. The [Scribe](https://github.com/hammurabiproject/scribe) repo is where all the shell files and crawlers to maintain this project live. The [Notary](https://github.com/hammurabiproject/notary) repo consists of tools for analyzing law.

## Format

This project covers many jurisdictions. Each jurisdiction may have sub-jurisdictions. Use short 2-3 letter codes to identify jurisdictions, but if there is no standard unique short code, it's reasonable to use longer titles.

Each jurisdiction may also have subdirectories for different languages, which are [2-letter codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) prefixed with an "_". Legislation lives in these language subdirectories, uniquely organized however is reasonable for that jurisdictions.

## Contributing

If you're interested in adding legislation for your jurisdictions, please consider writing a tool for [Scribe](https://github.com/hammurabiproject/scribe), rather than submitting PRs here for individual bills.

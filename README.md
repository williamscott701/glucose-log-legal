# Glucose Log — legal

Hosts the privacy policy and terms of use for the **Glucose Log** iOS app, at
<https://williamscott701.github.io/glucose-log-legal/>.

- [Privacy Policy](https://williamscott701.github.io/glucose-log-legal/privacy.html)
- [Terms of Use](https://williamscott701.github.io/glucose-log-legal/terms.html)

## Do not edit these pages by hand

The HTML here is generated. The source of truth is the Markdown bundled inside
the app, so the wording a user reads offline and the wording published here
cannot drift apart:

    GlucoseLog/Resources/PrivacyPolicy.md
    GlucoseLog/Resources/TermsOfUse.md

To publish a change, edit the Markdown in the app repository and run:

    ./scripts/publish-legal.sh

from there. It regenerates this site and pushes it.

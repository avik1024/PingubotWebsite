# PinguBOT content prototype

This folder is an intentionally plain, framework-free content prototype. Its
purpose is to agree on page structure, message hierarchy, copy length, and
calls to action before visual design or application implementation begins.

Start a local web server with Docker and use the shared navigation to review all six pages:

```sh
docker build -t pingubot-prototype .
docker run --rm -p 8080:80 pingubot-prototype
```

Then open `http://localhost:8080/`. Page URLs omit the `.html` extension (for
example, `/about` and `/contact`); requests to legacy `.html` URLs are redirected
to their extensionless equivalents.

Review each page for:

- whether the page makes one clear argument;
- whether any section is repetitive or too long;
- whether important proof or specificity is missing;
- whether the calls to action match the intended business conversation; and
- whether the six-page structure is the right site map.

`styles.css` provides only basic readability and review structure. It is not a
proposal for the final visual design.

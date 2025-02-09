# SPDX 3 model

The Software Package Data Exchange® (SPDX®)
is a standard format for communicating information
about components associated with software packages.
It has wide industry adoption
as a standardized Software Bill of Materials.
It is also an ISO standard, ISO/IEC 5962:2021.

This repository holds the model for the information captured
on the (upcoming) SPDX version 3 standard.

## Branches and Formats

The editable files are written in a constrained subset of Markdown
and are stored in the `main` branch.

These files are automatically processed into the following formats available at https://spdx.github.io/spdx-3-model/:

- HTML files generated by [Ontospy](http://lambdamusic.github.io/Ontospy/): https://spdx.github.io/spdx-3-model/auto-generated/
- [JSON-LD context](http://niem.github.io/json/reference/json-ld/context/) file: [context.json](https://spdx.github.io/spdx-3-model/context.json)
- Model [SHACL](https://en.wikipedia.org/wiki/SHACL) and [OWL](https://www.w3.org/OWL/) files:
  - [Turtle format](https://en.wikipedia.org/wiki/Turtle_(syntax)): [model.ttl](https://spdx.github.io/spdx-3-model/model.ttl)
  - [JSON-LD format](https://json-ld.org/): [model.jsonld](https://spdx.github.io/spdx-3-model/model.jsonld)

Note that these files are also available in the `gh-pages` branch.

People who wish to read the current version of the information
should be viewing the generated files, while anyone wanting to edit
should be working on the former.

For information about how to contribute to a specific profile,
please see [Contributing.md](Contributing.md).

## Contribute!

Feel free to join us and contribute!
The discussions are happening on the spdx-tech mailing list
and during our weekly meetings.
All the details are in: https://spdx.dev/participate/tech/


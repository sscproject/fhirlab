# FHIR® Lab

**Try it here before you build it there.**

FHIR® Lab is a free sandbox for low-resource settings. Try out HL7® FHIR®, SNOMED CT, ICD, LOINC and other standards, and see what works before you invest in national systems.

It's open to policymakers, implementers, developers, students and trainers. Use it to learn, test ideas and make the case for standards in your country.

FHIR® Lab sandbox is developed under The Strengthening Standards Capability Project (SSCP), co-funded by CSIRO Australia and Australian Government, Department of Foreign Affairs and Trade.

Website: **[fhirlab.net](https://fhirlab.net/)**

## Tools

| Tool | What it's for |
| --- | --- |
| [DPI-H Lab](https://dpih.fhirlab.net/) | Learn and build your country's connected health future together. |
| [Ontoserver](https://tx.fhirlab.net/) | Learn FHIR terminology, create ValueSets and expand in Point of Service Systems. |
| [IPS Connectathon Toolkit](https://fhirlab.net/ips-connectathon/) | Get your country team ready for the IPS connectathon. Learn, build and connect together. |
| [Generic FHIR Server](https://cdr.fhirlab.net/) | Fully functional FHIR server to test all things FHIR. |
| [PH Core FHIR Server](https://cdr.phcore.fhirlab.net/) | Fully functional FHIR server for the PH Core FHIR IG. |
| [PH eReferral FHIR Server](https://cdr.pheref.fhirlab.net/) | Fully functional FHIR server for the PH eReferral FHIR IG. |
| [Learning Activities](https://fhirlab.net/learning/) | Short exercises to learn and demonstrate standards in action. |

## Partner with us

We're always looking for great technology partners to power-up our sandbox. If you have a platform that supports standards-based health information exchange, is based on open-standards, support learning and capacity development, then let's talk! [Join us](https://chat.whatsapp.com/D7V2j7qLi31EuPmFCoyRC1).

## Working on this website

This site is built with [Jekyll](https://jekyllrb.com/) and the Doks theme, and is published with GitHub Pages from the `master` branch (see `.github/workflows/jekyll.yml`).

- Home page text and tool cards: `index.md`
- Header, footer and "Partner with us" text: `_config.yml`
- IPS Connectathon Toolkit page: `ips-connectathon.md`

To preview locally with Docker:

```
docker run --rm -p 4000:4000 -v "$PWD:/srv" -w /srv ruby:3.3 bash -c "bundle install && bundle exec jekyll serve --host 0.0.0.0"
```

Then open http://localhost:4000.

---

HL7® and FHIR® are registered trademarks of Health Level Seven International.

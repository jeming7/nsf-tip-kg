# NSF TIP Programs Knowledge Graph

An interactive, evidence-backed knowledge graph of the programs run by NSF's Directorate for
Technology, Innovation and Partnerships (TIP). It maps 58 programs and the relationships between
them — directed pathways, program families, shared operational attributes, shared funded
researchers, and more — where **every connection traces to a checkable NSF source**.

**Live site:** https://jeming7.github.io/nsf-tip-kg/

## What's here

| File | Purpose |
|---|---|
| `index.html` | Landing page |
| `graph.html` | The interactive graph — self-contained, runs entirely in the browser, no server or internet needed |
| `report.html` | A plain-language guide to reading and using the graph |

The graph is one self-contained HTML file (the [vis-network](https://visjs.github.io/vis-network/)
library is inlined), so it works offline and needs no build step.

## Disclaimer

This is an independent visualization of publicly available NSF program information. It is **not an
official NSF product**. Relationships are grounded in NSF's own solicitations, announcements, and
award records; click any connection in the graph to see its source.

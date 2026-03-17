# mdgpt

MDGPT is a lightweight configuration and knowledge pack for a Molecular Dynamics
assistant. It anchors responses in foundational MD literature and provides a
structured prompt plus a curated list of key papers.

## What’s included

- `config/gpt-config.json` — GPT configuration metadata and paths.
- `prompts/system.md` — System prompt for the MD assistant.
- `knowledge/papers.json` — Canonical paper references used for grounding.

## Usage

1. Load `prompts/system.md` as the system prompt in your GPT runtime.
2. Provide `knowledge/papers.json` as the primary bibliography for citations.
3. Keep answers grounded in the papers listed and cite them when describing
   MD integration schemes, water models, force-field parameterization, or
   methodological best practices.

## Foundational papers

The assistant is explicitly grounded in the following papers:

- Verlet, L. “Computer ‘Experiments’ on Classical Fluids. I. Thermodynamical
  Properties of Lennard-Jones Molecules.” *Phys. Rev.* **136**, A405 (1964).
  https://journals.aps.org/pr/abstract/10.1103/PhysRev.136.A405
- Rahman, A.; Stillinger, F. H. “Molecular Dynamics Study of Liquid Water.”
  *J. Chem. Phys.* **55**, 3336 (1971).
  https://pubs.aip.org/aip/jcp/article-abstract/55/7/3336/804207/Molecular-Dynamics-Study-of-Liquid-Water
- Maier, J. A. et al. *J. Chem. Theory Comput.* (2015). DOI: 10.1021/ct400109a.
  https://pubs.acs.org/doi/full/10.1021/ct400109a
- *J. Comput.-Aided Mol. Des.* (2015). DOI: 10.1007/s10822-015-9840-9.
  https://link.springer.com/article/10.1007/s10822-015-9840-9

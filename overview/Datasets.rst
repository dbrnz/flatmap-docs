Flatmap datasets
================

* Published on Pennsieve
* General Pennsieve dataset structure is documented `here <https://docs.pennsieve.io/docs/structure-of-published-datasets>`_.
* As an example, see `here <https://docs.google.com/document/d/1BDGVTSRAWSCOeVhOWkWorhUnxLzvafXeUHgO4V37bg8/edit#heading=h.uh1i7n0dt7m>`_ for scaffold dataset structure.
* Flatmap specific structure:

    - Source:

        + Manifest.json
        + Local files referenced from manifest

    - Derived:

        + Output of mapmaker (--output-dir)
        + RDF describing knowledge (that could be used to populate ``knowledgebase.db``)

* Created by ``mapmaker`` when run with ``--dataset`` option.

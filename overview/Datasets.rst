Flatmap datasets
================

* Published on Pennsieve.
* General Pennsieve dataset structure is documented `here <https://docs.pennsieve.io/docs/structure-of-published-datasets>`_.
* Folder structure is documented `here <https://docs.google.com/presentation/d/1EQPn1FmANpPsFt3CguU-JOQVMMlJsNXluQAK_gb2qVg/edit#slide=id.p1>`_.
* As an example, see `here <https://docs.google.com/document/d/1BDGVTSRAWSCOeVhOWkWorhUnxLzvafXeUHgO4V37bg8/edit#heading=h.uh1i7n0dt7m>`_ for scaffold dataset structure.
* `Dataset template <https://github.com/SciCrunch/sparc-curation/tree/master/resources/DatasetTemplate>`_ on Github.
* Flatmap specific structure:

    - Source:

        + Manifest.json
        + Local files referenced from manifest
        + Connectivity and other information retrieved from SciCrunch at map generation time.

    - Derived:

        + Output of mapmaker (--output-dir)
        + RDF describing knowledge (that could be used to populate ``knowledgebase.db``)

* Created by ``mapmaker`` when run with ``--dataset`` option.
* Summary about flatmap datasets to go at https://docs.google.com/document/d/1WjHmapS_a4OBx035J-noBlQN9a-ejmM20VPH6DHIQ-0/edit#
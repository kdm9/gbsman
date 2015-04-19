GBS Manager
===========

**This is alpha code, under heavy development. Use it like you'd use `rm -rf`.**

Scripts and pipelines to analyse reduced representation sequencing, including
automated job preparation and submission.

Built with python, jinja2 and doit.

Under the hood, it runs:

1. FastQC
2. Axe
3. scythe and sickle, OR trimmomatic
4. Tassel (bwa pipeline), OR UNEAK, OR {p,u}Stacks

Implementation progress
-----------------------

- [ ] Data storage/naming/retrieval
- [ ] SGE/PBS backends
- [ ] QC
- [ ] Demultiplexing
- [ ] Sequence Analysis
- [ ] Post analysis and result archiving

License
-------

GBSman is licensed under the GNU GPL version 3 or (at your option) any later
version.

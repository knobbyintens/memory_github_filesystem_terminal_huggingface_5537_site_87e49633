# Legacy profile export

This folder preserves the final compiled export of the Ardenne Institute for
Speech and Language profile database before its June 2025 decommissioning. It was
carried into the site repository when the old profile service was shut down.

- `legacy_export/export/profilekit.c` - Cython-generated C artefact (Cython 3.0.11).
- `legacy_export/export/SYMBOL_MANIFEST.txt` - inventory of the symbols the export must carry.
- `legacy_export/export/build_info.json` - build metadata.

The Python source used to generate the artefact was deleted together with the old
database; only this compiled copy survives. The export is authoritative for contact
identifiers and publication venue/DOI metadata.

Repository: memory_github_filesystem_terminal_huggingface_5537_site_87e49633

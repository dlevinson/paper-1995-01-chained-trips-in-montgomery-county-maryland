# Chained Trips In Montgomery County, Maryland

## Bibliographic Information

- Row ID: `paper-1995-01`
- Authors: Ajay Kumar and David M. Levinson
- Year: 1995
- Venue: ITE Journal, May 1995, 27-32
- Citation: Kumar, A., and Levinson, D. M. (1995). Chained trips in Montgomery County, Maryland. ITE Journal, May 1995, 27-32.
- Paper record: https://hdl.handle.net/11299/179853

## Package Status

This package is ready for public upload review. A paper-first audit confirmed that the article uses the 1987-88 MWCOG home-interview survey and FORTRAN processing to group trip records into chained work trips. The package keeps only the paper-specific aggregate table workbook and modern sidecars; it does not stage raw household, person, or trip microdata.

The FORTRAN programs are shared with the related MWCOG activity/time-allocation workflow, so they are held once in `_shared_sources/mwcog-trip-chain-fortran` and referenced from this package rather than duplicated here.

## Contents

- `paper/`: local reference copy of the published article for audit convenience.
- `data/aggregate_tables/original_legacy/`: retained Lotus 1-2-3 workbook containing the paper tables.
- `data/aggregate_tables/modernized/xlsx/`: LibreOffice conversion of the retained workbook.
- `data/aggregate_tables/modernized/csv/`: value export of the retained workbook.
- `data/aggregate_tables/SOURCE_FILE_REVIEW.csv`: inclusion/exclusion decisions for the local `ITE-CHAINS` source folder.
- `documentation/SOURCE_DATA_POINTERS.md`: public source-data pointers.
- `documentation/SHARED_CODE_POINTERS.md`: shared FORTRAN source pointer.

## Release Boundary

Public upload should include this package plus a pointer to the shared FORTRAN source package. Do not add raw MWCOG survey records, letters, drafts, author biosketch files, labels, presentation material, or panel-survey material not used by this paper.

<!-- package-hardening-status:start -->
## Package Hardening Status

Generated: 2026-05-20 14:46:37 AEST

- Pipeline: `READY-TO-UPLOAD/PUBLIC`
- Sidecars added/updated: `PACKAGE_STATUS.md`, `PACKAGE_MANIFEST.csv`, `LICENSE_STATUS.md`.
- Paper reference copies are for local audit convenience and are not public-upload assets without rights review.
- Final GitHub upload should use the manifest include statuses and the license-status note.
<!-- package-hardening-status:end -->

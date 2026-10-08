# AMUN SHEET

AMUN SHEET 1.0 (Dev) is a compact spreadsheet application for the AMUNOS DFLAT environment.

## Features

- 26 columns x 64 rows
- Arithmetic expressions with cell references
- SUM, AVERAGE, MIN, MAX, and COUNT
- .ASH v2 workbook format
- Mouse and keyboard navigation
- Insert/delete rows and columns
- Column sorting and width control
- Cell types: Auto, Text, and Number
- Lotus 1-2-3 inspired text-mode interface
- Single-row formula bar with current-cell address
- Borderless worksheet surface with white active cell and blue row/column cues

## Build

AMUN SHEET is currently built as part of the AMUNOS source tree:

```text
make A.img
make vmdk
```

The source is integrated with the AMUNOS DFLAT port and its system-call interface.

## Status

Version: 1.0 (Dev)

This repository is the application source mirror. Runtime integration and disk-image packaging remain in the AMUNOS repository.

## License

See the AMUNOS project for the current project licensing and source provenance.

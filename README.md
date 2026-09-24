# Import Users

CSC VB6 Create Users from 'Same As' user tool (`mail.exe`, project Import). Imports a CSV of username, first name, surname, DOB, same-as account, call number, and authority into an MSFlexGrid, targeting SQL Server `CBDXAAI` database `POLICE` / `tblCreateUsers` via SQLOLEDB. UI caption "Create Users from 'Same As' user"; OCXs: `COMDLG32.OCX`, `MSFLXGRD.OCX`.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Import` (`ImportUsers.vbp`) | VB6 | WinForms exe | CSV Same-As user import into SQL tblCreateUsers |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ImportUsers.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Registered OCX/DLL dependencies referenced by the `.vbp` (may need to be installed separately):
  - `COMDLG32.OCX`
  - `MSFLXGRD.OCX`
- SQL Server OLE DB provider (`SQLOLEDB`) and access to target `POLICE` database

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Import Users`.
Company names in project files: CSC.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.

# AJC Blueprint - PDF Drawing Export

New drawing export option:

- Export PNG
- Export PDF
- PDF includes AJC Blueprint header
- Project name
- Section name
- Section location/type/quantity when available
- Drawing revision
- Export date/time
- Full drawing on landscape A4
- Prepared-by owner footer

The app still stores its operational data in LocalStorage. PDF export uses jsPDF in-browser, with a print-to-PDF fallback if the library cannot load.

# URL Analysis

Example: `http://localhost/chemical_engineering_department_project/courses.html`

| Part | Value | Meaning |
|---|---|---|
| Scheme | `http` | Protocol used locally |
| Host | `localhost` | Current computer |
| Port | normally 80 by default | Default HTTP port if Apache configuration is unchanged |
| Path | `/chemical_engineering_department_project/courses.html` | Folder and requested page |
| Query / fragment | none | No query string or in-page anchor |

Relative paths include `about.html`, `css/style.css`, `images/chemical-process.svg` and `documents/T01-T12-testing-record.md`. Avoid absolute local file paths such as `C:\\Users\\...`.

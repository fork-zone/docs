# Project structure

## Local project

A Sheetbase project contains a backend app and a frontend app structured as below. This chart shows basic files of a project, frontend app structure is different between frontend frameworks, for example, an Angular.

```html
backend/ <!-- the backend app -->
    src/ <!-- main source code -->
    .clasp.json <!-- @google/clasp configs -->
    .claspignore
    appsscript.json <!-- apps script configs -->
    package.json
    rollup.config.js <!-- build tool configs -->
    tsconfig.json
frontend/ <!-- the frontend app (Angular) -->
    src/
    angular.json
    package.json
    tsconfig.json
sheetbase.json <!-- Sheetbase configs -->
package.json <!-- project info -->
```

## Google Drive

Sheetbase project remote assets stored in a Google Drive folder, there is at least one Apps Script file as the distributed backend app, a [sample](https://drive.google.com/drive/folders/1PA201m3pi8W78JtzW_kvjL3Bm8M0gYn2?usp=sharing) project structure.

```html
Sheetbase project: My Project (folder) <!-- project home -->
    My Project Backend (apps script)
    My Project Database (sheets)
```

## Google Cloud project

A Google Apps Script project is powrered by a [Google Cloud Plarform](https://cloud.google.com/) Project, you can view errors, logs and manage other GCP features by heading to the GCP Console project associated with the backend.

From the Apps Script editor: `Resources > Cloud Platform project...`, then click on the project id link.
This is a fork of ericthelemur/nodecg-ticker-control, slightly customized for Licenseathon 2025.

-   `npm run build`: Build the project once.
-   `npm run watch`: Build the project and automatically rebuild on changes.
-   `npm run dev`: Build the project, automatically rebuild on changes, launch the NodeCG server, and automatically restart the NodeCG server on changes.
    -   Only restarts the NodeCG server when server-side (i.e. extension) code changes. Changes to client-side code (i.e. dashboard panels and graphics) will not cause the server to restart, nor will they cause browser tabs to automatically refresh.

## Problems encountered while installing application

1. PORT variable in .env for backend should be 3000
2. mysql2 package should be updated.
3. Should use Docker for easy cross platform installation and not pollute local dev environment.
4. Quotation marks should be around values of .env
5. Change DB_HOST to HOST in `db_connection.js`
6. Replace '\r' in values sourced from .env in `DBConnection` constructor.
7. Default locale for react client should depend on location for proper i18n. Currently defaults to `Mn` in file `src/utils/translate.js`.

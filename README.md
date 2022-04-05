# Interview Scheduler

## Built using ReactJS

### ADD BOOKING

![This is an image](https://github.com/davincecode/scheduler/blob/master/public/images/add.gif)

### EDIT BOOKING

![This is an image](https://github.com/davincecode/scheduler/blob/master/public/images/edit.gif)

### DELETE BOOKING

![This is an image](https://github.com/davincecode/scheduler/blob/master/public/images/delete.gif)

### CANCEL

![This is an image](https://github.com/davincecode/scheduler/blob/master/public/images/cancel.gif)

## Setup

- Install dependencies with `npm install` in the root folder.
- It will automatically install modules into sub folders.

## Please note: Run the app in the root folder

```sh
npm run dev
```

## Scheduler API

Use the psql -U development command to login to the PostgreSQL server with the username development and the password development. This command MUST be run in a vagrant terminal, we are using the PostgreSQL installation provided in the vagrant environment.

CREATE or USE existing DATABASE scheduler_development;.

Copy the .env.example file to .env.development and fill in the necessary PostgreSQL configuration. The node-postgres library uses these environment variables by default.

```sh
PGHOST=localhost
PGUSER=development
PGDATABASE=scheduler_development
PGPASSWORD=development
PGPORT=5432
```

## Scheduler

Create .env and add `SKIP_PREFLIGHT_CHECK=true` if error `npm run client exited with code 1` occurs.

## Dev Dependencies

- axios
- react
- react-dom
- @testing-library/jest-dom
- @testing-library/react
- Cypress
- Storybook
- Node-sass
- Prop-types
- react-test-renderer

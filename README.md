# Sentry Angular Sample

Sample Angular application integrating Sentry to report uncaught exceptions.

## Getting Started
1. Install Angular-cli:
```npm install -g @angular/cli```

2. Set up a new Sentry Angular project  

3. Copy the DSN key from the Sentry Angular project and paste it in [/src/app/app.modules.ts](https://github.com/idosun/sentry-angular-sample/blob/4da28e3d3672dbd086a8b3234d82ef6ea2871f87/src/app/app.module.ts#L10)

    ```
    Sentry.init({
        dsn: "<YOUR DSN>"
        });
    ```

4. To start the dev server run 
```ng serve```

Navigate to http://localhost:4200/ to launch the application.

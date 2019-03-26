# Sentry Angular Sample

Sample Angular application integrating Sentry to report uncaught exceptions.

## Getting Started
1. Install Angular-cli:
```npm install -g @angular/cli```

2. Set up a new Sentry Angular project  

3. Copy the DSN key from the Sentry Angular project and paste it in [/src/app/app.modules.ts]

    Sentry.init({
        dsn: "<YOUR DSN>"
        });

4. To start the dev server run 
```ng serve```

Navigate to http://localhost:4200/ to launch the application.
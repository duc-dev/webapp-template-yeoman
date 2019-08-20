# webapp-template-yeoman

## First time here

Just ignore the dependencies which you have recently installed!

Install gulp, yeoman and webapp template of yeoman:

```bash
npm install --global yo gulp-cli generator-webapp
```

## Install Dependencies

This command to install the dependencies you have just updated.

```bash
npm install
```

## Development

2 Options:

1.  Run your webapp and automatically choose unvailable port:

    ```bash
    npm start
    ```

2.  Run your webapp with your custom port:

    ```bash
    npm start -- --port="your-custom-port"
    ```

    Replace `"your-custom-port"` with your custom port, for example:

    ```bash
    npm start -- --port=8080
    ```

## Build for production

3 options:

1. Build your webap:

   ```bash
   npm run build
   ```

2. Build your webapp and preview it on browser with choosing automatically port:

   ```bash
   npm run serve:dist
   ```

3. Build your webapp and preview it on browser with your automatically port:

   ```bash
   npm run serve:dist -- --port="your-custom-port"
   ```

   Replace `"your-custom-port"` with your custom port, for example:

   ```bash
   Run npm run serve:dist -- --port=5000
   ```

# uswds-application-ui

## Usage

Import the consolidated index file in your Sass. The file is located at
`src/styles/uswds-application-ui/_index.scss`:

```scss
@use 'path/to/uswds-application-ui/index';
```

When building, include the USWDS packages in your `SASS_PATH` so the
`@use "uswds-core"` statements resolve correctly:

```bash
SASS_PATH=node_modules/@uswds/uswds/packages npm run build
```

This command compiles the Sass in `src/styles` into the `dist/` folder.


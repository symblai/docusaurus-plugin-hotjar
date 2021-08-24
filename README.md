# docusaurus-plugin-hotjar

## Installation

```npm i docusaurus-plugin-hotjar```

## Setup

Add to plugins in `docusaurus.config.js`:

```
{
  plugins: [
    'docusaurus-plugin-hotjar',
    ...
  ]
}
```

Add the hotjar configuration to `themeConfig` in the `docusaurus.config.js` file:

```
{
  themeConfig: {
    hotjar: {
      applicationId: HOTJAR_ID,
    },
    ...
  }
}

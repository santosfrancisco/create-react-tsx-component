# Change Log

All notable changes to the Create React and React Native TSX Component extension will be documented in this file.

## [1.7.0]

- Adds the setting **useBarrel** that defines if component will be created using the barrel pattern.
- Adds the setting **useExportDefault** that defines if component will be created using export default or named export.

## [1.6.0]

- The settings for using the `Next JS Framework` are now set as default.
- Adds **Create Next Page** for creation of Next.js Pages.
- Changed the name of menu item from **Create React Component** to **Create Next or React Component**.
- Changed the name of menu item from **Create React Component with Styles** to **Create Next or React Component with Styles**.
- Changed the name of menu item from **Create React Named Component** to **Create Next or React Named Component**.
- Changed the setting for **useArrowFunctionComponent** that defines if component will be created using an a `Regular Function` or `Arrow Function` to uses `Regular Function` as default.
- Changed the setting **useReactFC** that defines if component will be typed using `React.FC` to false as default.
- Changed the setting **useReactImport** that defines if the import of React (`import React from 'react';`) will be used at the beginning of the component to false as default.

## [1.5.0]

- Adds **Orange Icon** 🔶 for React Component Actions.
- Adds **Blue Icon** 🔷 for React Native Component Actions.
- Adds **Create React Named Component** for creation of a React Component file with a name of component without folder creation.
- Adds **Create React Native Named Component** for creation of a React Native Component file with a name of component without folder creation.
- Adds the setting **useArrowFunctionComponent** that defines if component will be created using an `Arrow Function` or a `Regular Function`.
- Adds the setting **useReactFC** that defines if component will be typed using `React.FC`. **Important:** Only applicable if option `Use Arrow Function Component` and `Use React Import` is enabled.
- Adds the setting **useReactImport** that defines if the import of React (`import React from 'react';`) will be used at the beginning of the component. This option should only be used if you are using **React 17+**, that comes with support for the new JSX transform, where we don’t need to import React to our components anymore to use JSX.
- Adds the setting **useCSSModule** that defines if CSS file name will be sufixed with `.module.css` or `.module.scss`. **Important:** Only applicable if option `Styles Format` is `CSS` or `SCSS`.
- Adds `Next JS Framework` support.

## [1.4.3]

- Fixed the `.css` file extension when uses `.js` files format.

## [1.4.2]

- Updated the Readme.md, context menu items names for components with styles, extension name and description.

## [1.4.1]

- Updated the Readme.md.

## [1.4.0]

- Added support to use LESS in components creations.

## [1.3.1]

- Fix Styled Component file extension when use `.jsx` or `.js`.

## [1.3.0]

- Added support to use SCSS or CSS in components creations.

## [1.2.1]

- Updated the Readme.md.

## [1.2.0]

- Added support to create components using Javascript using files with extension `.jsx` and `.js`.

## [1.1.3]

- Update changelog.md file.

## [1.1.2]

- Update the Readme.md and changed the React Native Styled Container component and included StyleSheet for React Native component without Styled Components.

## [1.1.1]

- Update changelog.md file.

## [1.1.0]

- Added support for creating components for React Native.

## [1.0.1]

- Update file Readme.md.

## [1.0.0]

- Initial release.

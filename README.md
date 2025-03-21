# Deprecation Notice
This package has been integrated into [tgui-core](https://github.com/tgstation/tgui-core). Please use that instead. This repo will no longer receive updates.

# TGUI Styles

All the TG official styles for use with the [tgui-core](https://github.com/tgstation/tgui-core) library.

## Installation

First, install the package from inside the proper tgui/packages/x directory using yarn.

```bash
yarn add tgui-styles
```

## Usage

You have two options for importing styles:

### 1. Importing All Styles

To import all styles at once, add the following line to your main Sass file:

```scss
@use "pkg:tgui-styles";
```

### 2. Importing Individual Styles

To import individual styles, add any of the exported styles to your main Sass file:

```scss
@use "pkg:tgui-styles/components/Button";
@use "pkg:tgui-styles/components/Dialog";
@use "pkg:tgui-styles/components/NoticeBox";
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

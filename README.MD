# JS Extractor Groups

A community-driven collection of pattern groups for [JS Extractor](https://github.com/rdzsp/js-extractor).

JS Extractor is a browser extension that helps security researchers and bug bounty hunters extract sensitive information, endpoints, and hidden parameters from JavaScript files.

This repository provides pre-configured extraction groups in YAML format that you can easily import into your JS Extractor extension to enhance your web security testing.

## 🚀 How to Use

1. Ensure you have the [JS Extractor](https://github.com/rdzsp/js-extractor) extension installed in your browser.
2. Open the extension's **Options/Settings** page.
3. Locate the YAML Import/Export section for groups.
4. Copy the raw contents of any `.yml` file from this repository and paste it into the import window, or use the file upload functionality.
5. Once imported, the new extraction group and its patterns will be active inside your extension!

## 🤝 Contributing

We welcome contributions from the community! If you have a solid set of regex patterns useful for bug bounty hunting or security research, we'd love to see them added:

1. Fork this repository.
2. Create or update a YAML file following the `js-extractor` group structure (refer to existing files as a template).
3. Submit a Pull Request with your new patterns.

### Example Group Format
```yaml
js-extractor:
  name: Your Custom Group
  patterns:
    - regex: "YOUR_REGEX_HERE"
      description: "Description of what this regex finds"
    - regex: "ANOTHER_REGEX"
      description: "Another description"
```

# docsify-template

<div style="display:flex; align-items: center;">
  <a href="https://docsify.js.org/#/">
    <img
      style="height: auto; width: 60px;"
      src="./docs/assets/icon.svg"
    >
  </a>
  <span style="margin-left: 10px; font-size: 20px;">
    A simple template to help bootstrap a Docsify project as quickly as possible, configured with my favorite setup.
  </span>
</div>

## Version

Current version: `1.0.0`

## Features

- **Quick Bootstrap**: Preconfigured project structure to get you started instantly.
- **Customizable Components**: Easily swap out the logo (`cw_rocks.png`), favicon (`favicon.ico`), and footer content to personalize your site.
- **Enhanced Functionality**:
  - Integrated [docsify-copy-code](https://github.com/jperasmus/docsify-copy-code) for effortless code snippet copying.
  - Includes [docsify-footer](https://github.com/alertbox/docsify-footer) for consistent document footers.
  - Search functionality powered by [docsify-search](https://github.com/docsifyjs/docsify).
  - Themed using [docsify-theme-github](https://github.com/LIGMATV/docsify-theme-github)
  - GitHub corner provided by [docsify-corner](https://github.com/Koooooo-7/docsify-corner)
- **Simple Local Preview**: Run a Python server to preview your site locally with a single command.

---

## Project Structure

```plaintext
./docs/
├── assets/
│   ├── copycode.js      # Copy Code script (enables code copy/paste)
│   ├── docsify.js       # Core Docsify script
│   ├── corner.js        # Corner script (enables GitHub corner)
│   ├── footer.js        # Footer script (enables footer on every page)
│   ├── icon.svg         # Docsify logo
│   ├── index.css        # Theme stylesheet
│   ├── search.js        # Search script (enables search)
├── _footer.md           # Defines the document footer
├── .nojekyll            # Tells GitHub to bypass Jekyll
├── CNAME                # Adds custom domain to my pages site (replace or delete)
├── cw_rocks.png         # Logo (replace with your own)
├── favicon.ico          # Favicon (replace with your own)
├── index.html           # Main entry point for the Docsify site
├── license.md           # MIT license file
├── makefile             # Includes a command to run a local preview
└── README.md            # Project documentation
```

## Usage

### 1. Clone the Repository

```bash
git clone https://github.com/maverickg59/docsify-template.git
cd docsify-template
```

### 2. Start the Local Server

To preview your site locally, use the `makefile`:

```bash
cd docs

make dev
```

This runs a Python server at `http://localhost:3005`.

Alternatively, run the server manually:

```bash
python3 -m http.server 3005
```

### 3. Customize

- Replace `cw_rocks.png` with your logo.
- Replace `favicon.ico` with your favicon.
- Modify `_footer.md` to update the footer content.
- Update the Docsify config inside `index.html`.
- Modify the features to your hearts content.
- Visit [Docsify docs](https://docsify.js.org/#/?id=docsify) to get started developing content.

---

## Built With

- [docsify](https://github.com/docsifyjs/docsify): A magical documentation site generator.
- [docsify-copy-code](https://github.com/jperasmus/docsify-copy-code): Adds a copy button to code blocks.
- [docsify-footer](https://github.com/alertbox/docsify-footer): Allows customization of the footer.
- [docsify-search](https://github.com/docsifyjs/docsify): Provides in-page search functionality.
- [docsify-theme-github](https://github.com/LIGMATV/docsify-theme-github): The minimal amount of CSS to replicate the GitHub Markdown style.
- [docsify-corner](https://github.com/Koooooo-7/docsify-corner): Provides the GitHub corner to help users find your repo quickly and easily.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue on [GitHub](https://github.com/maverickg59/docsify-template).

---

## Author

Developed by [Chris White](https://chriswhite.rocks). Find me on [GitHub](https://github.com/maverickg59).

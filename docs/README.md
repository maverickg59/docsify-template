# docsify-template

A simple template to help bootstrap a Docsify project as quickly as possible, configured with my favorite setup.

## Features

- **Quick Bootstrap**: Preconfigured project structure to get you started instantly.
- **Customizable Components**: Easily swap out the logo (`cw_rocks.png`), favicon (`favicon.ico`), and footer content to personalize your site.
- **Enhanced Functionality**:
  - Integrated [docsify-copy-code](https://github.com/jperasmus/docsify-copy-code) for effortless code snippet copying.
  - Includes [docsify-footer](https://github.com/alertbox/docsify-footer) for consistent document footers.
  - Search functionality powered by [docsify-search](https://github.com/docsifyjs/docsify).
  - Themed using [docsify-theme-github](https://github.com/LIGMATV/docsify-theme-github)
- **Simple Local Preview**: Run a Python server to preview your site locally with a single command.

---

## Project Structure

```plaintext
docs/
├── assets/
│   ├── copycode.js      # Enables code snippet copying
│   ├── docsify.js       # Core Docsify configuration
│   ├── footer.js        # Footer customization script
│   ├── index.css        # Styling for your Docsify site
│   ├── search.js        # Adds search functionality
├── _footer.md           # Defines the document footer
├── .nojekyll            # Tells GitHub to bypass Jekyll
├── CNAME                # Adds custom domain to my pages site (replace or delete)
├── cw_rocks.png         # Logo (replace with your own)
├── favicon.ico          # Favicon (replace with your own)
├── index.html           # Main entry point for the Docsify site
├── LICENSE              # MIT license file
├── makefile             # Includes a command to run a local preview
└── README.md            # Project documentation (this file)
```

## Usage

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/docsify-template.git
cd docsify-template
```

### 2. Start the Local Server

To preview your site locally, use the `makefile`:

```bash
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

---

## Built With

- [docsify](https://github.com/docsifyjs/docsify): A magical documentation site generator.
- [docsify-copy-code](https://github.com/jperasmus/docsify-copy-code): Adds a copy button to code blocks.
- [docsify-footer](https://github.com/alertbox/docsify-footer): Allows customization of the footer.
- [docsify-search](https://github.com/docsifyjs/docsify): Provides in-page search functionality.
- [docsify-theme-github](https://github.com/LIGMATV/docsify-theme-github): The minimal amount of CSS to replicate the GitHub Markdown style.

---

## License

This project is licensed under the MIT License.

---

## Contributing

Contributions are welcome! Feel free to submit a pull request or open an issue on [GitHub](https://github.com/maverickg59/docsify-template).

---

## Author

Developed by [Chris White](https://chriswhite.rocks). Find me on [GitHub](https://github.com/maverickg59).

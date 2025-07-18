# Static Site Generator

A minimal static site generator written in Python. Convert Markdown content into styled HTML pages with ease.

## Features

- Converts Markdown files to HTML
- Supports custom templates and CSS
- Recursively processes content directories
- Copies static assets (images, CSS) automatically

## Usage

1. Place your Markdown files in the `content/` directory.
2. Run the build script:

   ```sh
   ./build.sh
   ```

3. Serve the generated site:

   ```sh
   cd docs
   python3 -m http.server 8888
   ```

## Project Structure

- `content/` - Your Markdown files
- `static/` - Static assets (CSS, images)
- `docs/` - Generated HTML site
- `src/` - Source code

## Credits

Built as part of the [Boot.dev](https://www.boot.dev/courses/build-static-site-generator-python) static site generator course.

---

Clean, fast, and easy—perfect for learning

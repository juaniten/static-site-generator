# Static Site Generator

A simple HTML generator that converts Markdown pages into static HTML files.

## Features

- Converts Markdown files to HTML.
- Utilizes a customizable HTML template for consistent page structure.
- Processes all Markdown files in the `content` directory and outputs HTML files to the `public` directory.
- Copies static assets from the `static` directory to the `public` directory.

## Requirements

- Python 3.x
- `markdown` module (`pip install markdown`)

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/juaniten/static-site-generator.git
   cd static-site-generator
   ```

2. **Prepare your content:**

   - Place your Markdown files in the `content` directory.
   - Add any static assets (e.g., CSS, JavaScript, images) to the `static` directory.

3. **Customize the template (optional):**

   - Modify `template.html` to change the HTML structure or include additional elements.

4. **Generate the site:**

   - Run the main script:

     ```bash
     ./main.sh
     ```

   - This script will:
     - Convert all Markdown files in the `content` directory to HTML.
     - Apply the `template.html` to each converted file.
     - Output the resulting HTML files to the `public` directory.
     - Copy all files from the `static` directory to the `public` directory.

5. **View your site:**

   - Open the generated HTML files in the `public` directory with your preferred web browser.

## Testing

A `test.sh` script is provided to run tests and ensure the generator functions correctly. To execute the tests:

```bash
./test.sh
```

## License

This project is licensed under the MIT License.

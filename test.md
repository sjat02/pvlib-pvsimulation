# EMS Documentation

This folder contains the technical documentation for the Energy Management System (EMS), written in AsciiDoc.

## Format

- **Format:** `.adoc` (AsciiDoc)
- **DocType:** `book`
- **TOC:** Left-aligned, 3 levels
- **Images:** Stored in the `images/` subfolder

## View Locally

To view the documentation, follow these steps:

### Option 1: Command Line

1. Install [Asciidoctor](https://asciidoctor.org) by running the following command:

    ```bash
    gem install asciidoctor
    ```

2. Convert the `.adoc` file to HTML using this command:

    ```bash
    asciidoctor ems-doc.adoc
    ```



This will generate an HTML file in the same folder, which you can open in a browser.  
The document follows a structured layout with sections for architecture, deployment, communication, and more.

You can also convert the documentation to PDF by installing Asciidoctor PDF separately:

```bash
gem install asciidoctor-pdf
asciidoctor-pdf ems-doc.adoc

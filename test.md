# EMS Documentation

This folder contains the technical documentation for the Energy Management System (EMS), written in AsciiDoc.

## Format

- **Format:** `.adoc` (AsciiDoc)
- **DocType:** `book`
- **TOC:** Left-aligned, 3 levels
- **Images:** Stored in the `images/` subfolder

## View Locally

Ensure you have **Asciidoctor version 2.0.23** (with Ruby 3.3.7 or later) installed on your system.

To view the documentation, follow these steps:

1. Install [Asciidoctor](https://asciidoctor.org) by running the following command:

    ```bash
    gem install asciidoctor
    ```

2. Convert the `.adoc` file to HTML using the following command:

    ```bash
    asciidoctor ems-doc.adoc
    ```

3. Convert the `.adoc` file to PDF using the following command:

    ```bash
    gem install asciidoctor-pdf
    asciidoctor-pdf ems-doc.adoc
    ```

Both PDF and HTML files will be generated in the same folder.

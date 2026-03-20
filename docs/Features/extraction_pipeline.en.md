# Content Extraction Pipeline

**Available with:** KNOWRON Core

When you upload a document to KNOWRON, the system automatically processes it to extract its content and make it searchable. This processing step — the content extraction pipeline — runs in the background without any action required from you. Once complete, the document's content is indexed and available to both Search and the AI Assistant.

!!! note "Fully automatic"
    There is nothing to configure or trigger. Upload a document and the extraction runs automatically. You can start searching the content as soon as processing is complete.

---

## What the pipeline extracts

The standard extraction pipeline is designed for documents where content exists as readable text. It works well for:

- Technical manuals and service documentation
- Product specifications
- Standard text-based PDFs and Word documents

For these document types, the pipeline extracts the text present in the file and uses the document's existing structure — headings, sections, paragraph breaks — to preserve context and make results easier to navigate. Basic table extraction is also included.

<!-- IMAGE: Diagram or screenshot showing the upload-to-search flow: document uploaded → extraction → indexed and searchable -->

---

## What it does not cover

The standard extraction pipeline does not extract text from images embedded in a document, unless that text is also encoded separately as actual text in the file. It is not the right fit for documents where the primary content is visual, such as:

- Complex circuit diagrams
- Mechanical drawings
- Highly graphical or image-heavy technical documents

If a document of this type is uploaded, the file will be stored and retrievable, but the visual content inside it will not be searchable through standard means.

---

## For most technical documentation use cases, this is enough

If you are working primarily with manuals, specifications, and text-rich PDFs, you can expect good extraction quality out of the box. The standard pipeline covers the vast majority of standard industrial and technical documentation.

---

## Specialized extraction for complex document types

If your use case involves document types that go beyond standard text-based content — for example, circuit diagrams or mechanical drawings that need to be made searchable — expanded extraction capabilities are available.

Contact your Sales or Customer Success contact to discuss what's possible for your specific document types.

---

## Related

- [Documents](documents.md) — how to upload and manage documents in the Control Suite
- [Document Upload Guidelines](../Admin%20Documentation/documents_upload_guidelines.md) — how to prepare documents for the best extraction results
- [Search](search.md) — how KNOWRON's search works with extracted content

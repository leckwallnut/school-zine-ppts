---
name: artifact-template-school-zine-ppts
description: "Create or restyle editable teaching PowerPoints in the School Zine PPTs style, with Finish the Line illustrations, readable paper surfaces, and 18 copyable teaching layouts. Use for School Zine PPTs or when the user asks for this skill by name, however their assistant invokes skills."
---

# School Zine PPTs

Create or restyle teaching PowerPoints for the teacher’s subject, audience, lesson time, slide count, content and sequence. The ESL deck and sample activities illustrate the visual system. Follow the teacher’s current material when choosing the wording, examples and progression.

1. Read [artifact-template.json](artifact-template.json). Resolve its paths relative to this skill folder. Use whatever PowerPoint authoring, rendering and validation tools your assistant provides (for example a presentation tool, or a library such as python-pptx or pptxgenjs, plus a way to render slides to images such as PowerPoint or LibreOffice). Keep the output an editable PPTX. If no authoring tool is available, say so and give a slide-by-slide plan using the layouts instead.
2. Inspect [the canonical reference](assets/reference.pptx) and [the layout library](assets/layout-library.pptx). Work on a copy and select layouts by their teaching purpose using [the numbered guide](references/layouts.md). For a restyle, preserve the teacher’s sequence, exercises, answer keys, notes, and evidence unless the teacher asks for changes.
3. Use [the design guide](references/design-system.md) and [the image library](references/image-library.md). Prefer the bundled artwork when it fits. Keep source evidence distinct from illustrative artwork. Preserve picture proportions and alpha. Place the actual lesson words in separate native text boxes, including words on paper or bubbles.
4. Keep passages, annotations, tables and simple diagrams editable. Put image provenance and lesson-source details in the relevant speaker notes. For a reveal, place the answer directly after its prompt. Use native PowerPoint motion where it serves the teacher’s request and playback can be verified.
5. Render every exported slide. Review font, line breaks, contrast, crop, editability, text fit, and layout variety. Confirm that all student instructions and relevant source notes survived.

Use the bundled resources via relative paths so the template travels as one folder. Preserve the canonical deck and library as reusable originals.

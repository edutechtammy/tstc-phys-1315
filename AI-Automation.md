# AI-Powered Text Enhancement Prompt

Use the following prompt with your AI text rewriting tool to automatically upgrade lesson introductions, content, and activity instructions for engagement and student focus:

---

**Prompt:**

Rewrite the following lesson text to be more engaging, motivational, and student-centered. Speak directly to the student, spark curiosity, and connect the content to real-world relevance. For instructions and practice activities, encourage active participation and confidence. Avoid jargon and keep the tone friendly, clear, and supportive. Preserve all technical accuracy and required information.

**Text to rewrite:**
<insert original lesson text here>

---

**Tips:**
- Use this prompt for introductions, lesson content, and all instructions for practice/apply activities.
- Review AI-generated rewrites for accuracy and tone before finalizing.
# Risk Mitigation for Automated Content Extraction & Mapping

## Extraction & Mapping Checklist
- [ ] Confirm all required sections (intro, objectives, readings, media, practice, enrichment) are present in the source.
- [ ] Check for consistent section headers and class names in source files.
- [ ] Validate that all images, videos, and links are accessible and not broken.
- [ ] Ensure JSON keys match expected template placeholders.
- [ ] Map each extracted block to the correct template location.

## Troubleshooting Tips
- If a section is missing, check for alternate spellings or unexpected HTML structure.
- For interactive elements, verify that all scripts and dependencies are included or replaced with template-compatible versions.
- If mapping fails, log the problematic section and continue with the rest, flagging for manual review.

## Example Input/Output
**Input (source HTML):**
```html
<div class="introduction"> ... </div>
<div class="objectives"> ... </div>
```
**Output (template):**
```html
<section class="dp-content-block kl_introduction"> ... </section>
<section class="dp-content-block kl_objectives2"> ... </section>
```

## Manual Review Guidance
- After automated mapping, review the output for:
  - Missing or duplicated sections
  - Content in the wrong section
  - Broken or missing media
  - Incomplete or awkwardly phrased motivational language
- Use a checklist to confirm all required elements are present and correct.

## Automated Tests & Scripts
- Implement scripts to:
  - Compare the number and order of sections in source and output
  - Flag missing or empty sections
  - Validate all links and media
  - Check for required JSON keys and values
- Run these tests as part of the conversion process and generate a report for each lesson.
# AI-Automation: Workflow for Themed Lesson Conversion

## 1. Standardize Inputs
- Ensure all source lessons (HTML or other formats) and supporting JSON (quotes, credits, objectives, etc.) follow a predictable structure.
- Confirm that all required assets (images, videos, readings) are accessible and their locations are consistent.

## 2. Template-Driven Conversion
- Develop a master HTML template for the new theme, with clear placeholders for:
  - Header, introduction, objectives, readings, media, practice (conceptual & computational), enrichment, etc.
- Use this template as the base for all conversions.

## 3. Automated Content Extraction & Mapping
- Build or use scripts (Python, Node.js, etc.) to:
  - Parse the original lesson HTML and extract key content blocks (intro, objectives, readings, media, practice problems).
  - Map extracted content to the corresponding placeholders in the new template.
  - Pull in quotes, credits, and enrichment from the provided JSON.

## 4. Content Enhancement & Consistency
- Integrate motivational and student-focused language automatically, using a library of pre-approved phrases or AI-generated suggestions.
- Standardize section spacing and inline styles (e.g., margin-bottom) as done in M1L1 and M2L1.
- Insert accessibility features (alt text, semantic tags) by default.

## 5. Interactive & Practice Elements
- Detect and convert interactive elements (e.g., CidiLabs sort, quizzes) to the new format, using reusable code snippets or components.
- Ensure answer formatting guidance and feedback are included.

## 6. Validation & Quality Checks
- Run automated checks for:
  - Section order and completeness (all required sections present)
  - Broken links or missing media
  - Consistent use of styles and accessibility tags
- Optionally, use AI to review for tone, clarity, and engagement.

## 7. Manual Review & Tweaks
- Provide a summary report of each conversion, highlighting any sections needing manual attention (e.g., ambiguous content, missing images).
- Allow for easy manual edits before finalizing.

## 8. Output & Versioning
- Save the new lesson HTML in the correct output directory, following the established naming convention.
- Optionally, generate a changelog or diff for each conversion.

---

### What I Need From You
- Source lesson files and supporting JSON for each lesson.
- Any unique requirements or exceptions for specific lessons.
- Approval of the master template and motivational language library (if using AI-generated enhancements).

---

### How I’ll Work
- I’ll automate as much as possible: extraction, mapping, enhancement, and validation.
- I’ll flag anything that needs your review.
- I’ll keep the process transparent, repeatable, and easy to adjust as the template or requirements evolve.

---

Would you like a sample script or a more detailed breakdown of any step?

## Goals
- Rename the docs to "VexRender" and present a professional, comprehensive guide for AI video and image generation.
- Make usage crystal clear with step-by-step workflows, parameter guidance, examples, and best practices so users don’t need to ask questions.
- Align docs with your product focus: Text to Video, Image to Video, Motion Brush, Style Transfer, Upscaler, and 4K export.

## Information Architecture
- Guides
  - Overview (homepage for docs)
  - Quickstart (3 steps: sign in → generate → enhance & export)
  - How VexRender Works (concepts: prompts, references, parameters)
- Tools
  - Text to Video
  - Image to Video
  - Motion Brush
  - Style Transfer (rename from Style Change)
  - Upscaler
  - Export & Formats
- Resources
  - Prompts Library (examples & negative prompts)
  - FAQs (limits, credits, resolutions, content guidelines)
- Remove/Hide API Reference for now (no public API yet).

## Branding & Configuration Changes
- Update site name to "VexRender" in `docs.json`.
- Optional: adjust colors to match brand and update `logo/light.svg` and `logo/dark.svg` paths if you have custom logos.
- Update navbar CTA (e.g., "Start Free" or "Try Text to Video") and footer socials.

## Page Content Plans
### Overview
- Value proposition: "Create stunning AI-generated videos and images — no experience needed."
- Feature highlights: Text to Video, Image to Video, Motion Brush, Style Transfer, 4K export.
- CTA cards linking to Quickstart and each tool page.
- Showcase grid with 3–6 short demo clips/images (with prompt captions).

### Quickstart
- Step 1: Sign in and create a project.
- Step 2: Generate your first asset
  - Text to Video: enter prompt, choose duration/frame rate, generate.
  - Image to Video: upload image, set motion, generate.
- Step 3: Enhance & Export
  - Upscaler, Motion Brush, Style Transfer → export in MP4/WebM, up to 4K.

### Text to Video
- Overview and benefits.
- Parameters (name, meaning, defaults, recommended ranges):
  - `durationSeconds`, `frameRate`, `stabilizationStrength`, `styleIntensity`, `guidanceScale`.
- Workflow: prompt → tune params → generate variations → review continuity → export.
- Examples (prompt + description of output):
  - "A futuristic space battle with laser beams and explosions, cinematic lighting, 24fps, 8s"
  - "Slow-motion ocean waves at sunset, warm color grading, 15s"
- Tips: prompt structure, negative prompts, continuity hints.

### Image to Video
- Source image guidelines (resolution, composition, subject clarity).
- Parameters: motion strength/direction, duration, frameRate, stabilization.
- Workflow: upload → set motion → generate takes → refine with Motion Brush.
- Examples with prompts and reference notes.

### Motion Brush
- Brush size/softness, mask add/subtract, motion direction/speed.
- Use cases: hair sway, light flicker, background parallax.
- Workflow and preview loop, best practices to avoid artifacts.

### Style Transfer
- Rename from Style Change for consistency.
- Style preset selection, intensity blending, structure fidelity, batch processing.
- Examples: "Cyberpunk neon", "Studio-grade film look".

### Upscaler
- 2×/4× upscaling, artifact reduction, face restore.
- Side-by-side comparison advice; when to use each setting.

### Export & Formats
- Formats: MP4/WebM; aspect ratios (1:1, 9:16, 16:9); bitrates.
- 4K export notes: performance considerations and recommended settings.

### Prompts Library
- Categorized examples (nature, city, sci-fi, product, people).
- Negative prompts list to avoid artifacts.
- Guidance on style tokens and camera terms.

### FAQs
- Accounts and projects; credits/limits; max resolutions; content guidelines; support links.

## Assets & Examples
- Collect 6–10 short demo clips and images to embed; add captions with the actual prompts used.
- Place assets under `images/` and `videos/` and reference them in MDX.

## SEO & Quality
- Page-level meta titles/descriptions tailored to features.
- Consistent naming ("Style Transfer"), tone guide (clear, professional, concise), accessible headings, alt text.
- Internal cross-links between related tools and workflows.

## Implementation Steps
1) Update `docs.json` name to `VexRender`, remove/hide API tab, refine navigation per IA.
2) Rewrite `index.mdx` and `quickstart.mdx` to match copy above.
3) Create/expand tool pages with parameters, workflows, and examples.
4) Add Prompts Library and FAQs pages.
5) Drop in demo assets and captions.
6) Start local preview, verify navigation, links, and accessibility; refine copy.

## Deliverables
- Fully structured VexRender docs with professional tone and detailed guidance.
- Clear workflows, parameter explanations, and example prompts with output descriptions.
- No API references until you choose to add them.

Confirm and I’ll implement this plan end-to-end in your repo and provide a preview URL for review.
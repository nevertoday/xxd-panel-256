---
name: xxd-panel-256
description: "XXD Panel 256｜Naive Folk Art: reduces a photo to one subject, one feeling and one metaphor and paints it as a contemporary artist's naïve folk illustration — rounded simplified forms, childlike lines, flat colour shapes with a hand-cut feel, irregular edges, layered paint, paper texture and visible hand error, a few touches of gold leaf as the symbolic highlight, a soft bright palette of warm white, cream, powder blue, misty blue, plant green, soft yellow, coral orange and pale pink from the photo, the subject at or near the centre in a large field of paper, and a small, elegant handmade-style title or note. Outputs PNG top-bottom or left-right comparisons, design-only images, or phone/tablet/desktop/watch wallpapers, from one photo or a folder. Use when the user invokes xxd-panel-256 or asks for naive art, modern folk illustration or gold-leaf artist illustration from a photo."
---

# XXD Panel 256

Create finished PNG artwork from the current user-supplied photograph or image directory. Read `references/original-prompt/zh-CN.md` completely immediately before every generation. That Chinese source brief is the sole creative and aesthetic authority; never summarise, translate, blend, or replace it with this file, a README, a sample, or another Panel.

Read `references/soldier-runtime.md` completely immediately before building every generation request. It is the sole family runtime contract for parameters, preference reuse, directory batches, preflight, prompt assembly, bitmap execution, output isolation, and acceptance. This Skill must not write a second art direction or a second runtime.

## Panel-specific overlay

The transformed design is one illustrated moment, not a full depiction. Keep a single subject near the center as the only focus, built from simplified forms, symbolic contours and flat color. Leave a large field of paper. Edges may be irregular, with paint coverage, paper texture and hand error. Reject a complex background, several narrative elements, digital perfection and a filled page.

These overlay rules add to `references/soldier-runtime.md`. They never replace the source brief or the family runtime contract.

Write every selected final PNG directly inside one fresh task directory under `~/Desktop/xxd/xxd-panel-256/` (or the explicit `--out` root). Use collision-safe filenames; do not create source, mode, or size subdirectories and do not generate an automatic contact sheet.

## References

- `references/soldier-runtime.md` — family runtime contract used at generation time
- `references/original-prompt/zh-CN.md` — canonical source brief used at runtime
- `references/original-prompt/README.md` — translation index and authority note
- `references/runtime-preferences.md` — safe delivery-preference reuse
- `references/sample-workflow.md` — sample-artwork maintenance only; never a runtime prerequisite
- `references/xxd-panel-256-prompt.zh-CN.md` and `.en.md` — delivery adapter notes matching the family runtime blocks

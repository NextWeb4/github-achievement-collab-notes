# AGENTS.md

## 1. Project structure
- This fork is documentation-only. The root README files are the project; there are no source, package, asset, or workflow directories.
- Keep `README.md`, `README.zh-CN.md`, and `README.ja.md` equivalent in scope and navigation.

## 2. Run commands
- No run command was found in the current repository; do not describe this repository as an application.

## 3. Test commands
- No test command was found in the current repository; add one before claiming automated regression coverage.
- Review rendered Markdown and links manually after every change.

## 4. Build commands
- No build command was found in the current repository.

## 5. Code style
- Keep the exact centered Shields language selector in all root README files; its visible SVG labels are `English`, `简体中文`, and `日本語` so browser translation cannot rewrite them.
- Keep English, Simplified Chinese, and natural Japanese content in the same section order with identical paths, links, facts, counts, limitations, and code fences.
- No lint / format command was found in the current repository.
- Use UTF-8 Markdown, short sections, descriptive link text, and nonempty image alt text.
- Keep commands and GitHub terms identical across translations.

## 6. Module boundaries
- Purpose, learning goals, the recommended exercise, verification, scope, upstream attribution, maintenance, network behavior, and license status belong in all three root README files.
- Repository maintenance constraints belong in `AGENTS.md`; do not turn the README into an internal process log.

## 7. Prohibited changes
- Do not fabricate pull requests, reviews, merges, contributions, or Achievement results.
- Do not add empty commits or meaningless changes to simulate activity.
- Do not remove attribution to `rayfon99999/github-achievement-collab-notes`.
- Do not add dependencies, workflows, or executable code for a documentation-only change.

## 8. Completion criteria
- All three README languages contain the same factual scope and working language links.
- Upstream attribution and the absence of a declared license remain explicit.
- Every Markdown link and badge uses the correct repository identifier.
- The documentation remains useful without private context and never implies that a particular GitHub Achievement is guaranteed.

## 9. Review criteria
- Verify the language selector renders through GitHub without browser-translatable text and all three README versions keep the same facts, commands, links, and images.
- Compare claims with the public Git history and reject anything that cannot be verified.
- Check the rendered README at narrow and wide widths; avoid wide decorative tables.
- Confirm `git diff --check` passes before publishing.

## 10. Common risks
- Fork documentation can drift from upstream; distinguish local notes from upstream behavior.
- GitHub Achievement rules can change and are not guaranteed by a documented action.
- Dynamic Shields images require network access when the README is rendered.

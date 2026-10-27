# Meko Visuals

Photography portfolio website for Meko Visuals, live at https://mekovisuals.com.

## Structure
- `index.html`: the entire site in one file (HTML, CSS, and JS inline). There is no build step and no framework.
- `mekovisualsLogoTrans.png`: logo with a transparent background.
- `CNAME`: custom domain for GitHub Pages. Do not delete it, or the domain stops working.
- `.github/workflows/`: Claude GitHub Actions (`claude.yml` handles `@claude` mentions, `claude-code-review.yml` auto-reviews PRs).

## Page sections (in order)
Nav, hero, marquee, statement, services (`#services`), image break (`#work`), process (`#process`), stats, gallery (`#gallery`), testimonial, CTA (`#contact`), footer. There is also an album modal (`#modalTitle`).

## Design
- Dark and gold theme. New sections should match the existing colors, fonts, and spacing.
- Elements animate in on scroll through the `reveal` class (with `stagger-N` for delays).
- Must work on mobile.

## Hosting and workflow
- Hosted on GitHub Pages from the `main` branch. Anything pushed to `main` goes live within about a minute.
- Repo: `MekoMansy0/Meko-Visuals` (git remote uses SSH).
- When `@claude` is mentioned on GitHub, it works on a `claude/...` branch. Those changes only go live after they are merged into `main`.

## Notes
- The owner is new to git and GitHub. Explain steps in plain language.

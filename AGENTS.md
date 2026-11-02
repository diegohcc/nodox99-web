<!-- LOVABLE:BEGIN -->
> [!IMPORTANT]
> This project is connected to [Lovable](https://lovable.dev). Avoid rewriting
> published git history — force pushing, or rebasing/amending/squashing commits
> that are already pushed — as it rewrites history on Lovable's side and the
> user will likely lose their project history.
>
> Commits you push to the connected branch sync back to Lovable and show up in
> the editor, so keep the branch in a working state.
<!-- LOVABLE:END -->

## Project rules
- Single-page marketing site: sections live in `src/components/site/*`, all copy/data in `src/content/site.ts` — keeps text editable in one place.
- Contact form has no backend; it opens WhatsApp with a prefilled message via `src/lib/whatsapp.ts` (covered by `src/test/whatsapp.test.ts`).

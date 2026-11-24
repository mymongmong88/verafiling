[README.md](https://github.com/user-attachments/files/35360302/README.md)
# VeraFiling

Static bilingual website. The deployable root is `dist/`.

- `/ko/` and `/en/`: Korean and English landing pages.
- Theme preference follows the system by default and can be changed in the header.
- Contact tool prepares a mailto draft; it does not send email or store inquiry data.
- Primary contact: admin@verafiling.com; fallback: admin.verafiling@gmail.com.
- Prior HTML pricing retained: facility $395, renewal $295, first listing from $175.
- Verify final commercial scope, legal operating entity, domain email delivery and contract terms before public customer launch.
- Custom domain is not configured by these files. Update canonical, alternate, sitemap and Open Graph origins in build.py when assigning the final domain.

Run `python3 build.py` after copy changes, then `python3 check.py`.
Preview: `python3 -m http.server 8766 --directory dist`.

Browser checks: Korean/English navigation, light/dark switching, 390px mobile layout and menu, draft generation (no email sent). Local file/link checks and JavaScript syntax checks passed.

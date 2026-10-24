# Persian Web Skills — اسکیل‌های وب فارسی

AI-agent skills for building **Persian (RTL) and multilingual websites** — with professional
fonts, correct right-to-left layout, and landing pages that actually convert.

اسکیل‌های آماده برای ساخت **سایت فارسی و چندزبانه** با فونت حرفه‌ای، چیدمان درست
راست‌به‌چپ و لندینگ پربازده — نه قالب لاتینِ فقط ترجمه‌شده.

## Why this repo is different

Most web-design skills are built for Latin layouts and assume English typography.
Persian sites break that assumption: fonts, direction, numerals, forms and even
phone numbers follow different rules. These skills encode those rules explicitly:

- **Vazirmatn typography** — proper Persian font stack, weights, line-height and loading
- **Real RTL** — CSS logical properties (`margin-inline-start`, …), mirrored directional
  icons, RTL navigation — never a translated Latin layout
- **Multilingual done right** — `hreflang`, per-language fonts, `dir` per locale
- **Persian forms** — Iranian mobile validation (`09…`, 11 digits), Persian labels and errors
- **Local conversion** — click-to-call numbers and WhatsApp CTAs Iranian users actually use

## Skills

| Skill | What it does | Use it when… |
| --- | --- | --- |
| [persian-rtl-web-design](skills/persian-rtl-web-design/SKILL.md) | Persian (RTL) and multilingual sites with professional fonts | Building a Persian, Arabic-script or multilingual site or landing page |
| [persian-landing-builder](skills/persian-landing-builder/SKILL.md) | High-converting Persian landing pages for service businesses | Building a Persian landing page — IT support, CCTV, repair, local services |

## Install

Copy a skill folder into your agent's skills directory. Examples:

```bash
# Muse
cp -r skills/persian-rtl-web-design ~/workspace/custom-skills/

# Claude Code
cp -r skills/persian-rtl-web-design ~/.claude/skills/
```

No build step, no dependencies, no paid service — just Markdown.

## Usage examples

- «یک لندینگ فارسی برای خدمات نصب دوربین مداربسته در چابهار بساز»
  → uses **persian-landing-builder**: hero, trust signals, services, pricing,
  FAQ, lead form with phone + WhatsApp CTA.
- «یک سایت فارسی و انگلیسی با فونت حرفه‌ای بساز»
  → uses **persian-rtl-web-design**: Vazirmatn, RTL logical properties,
  `hreflang`, per-language fonts.

## Author

**Omid Razmkhah** ([@Edward6699](https://github.com/Edward6699)) — IT support &
network technician from Chabahar, Iran, building practical tools for Persian
web builders.

## License

MIT — see [LICENSE](LICENSE).

---

If these skills help you, a ⭐ star helps other Persian builders find them.

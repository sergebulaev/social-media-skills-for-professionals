# Social Media Skills for Professionals: Claude and Codex Skills by Profession

<p align="center">
  <img src="https://img.shields.io/badge/Claude_Code-Compatible-D97757?logo=anthropic&logoColor=white" alt="Claude Code Compatible">
  <img src="https://img.shields.io/badge/Codex-Compatible-111827" alt="Codex Compatible">
  <img src="https://img.shields.io/badge/Claude-Skills-8A63D2" alt="Claude Skills">
  <img src="https://img.shields.io/badge/License-MIT-22C55E.svg" alt="MIT License">
</p>

**Open skill bundles that do social media for one profession each.** Every
bundle knows where that profession's post ideas come from (a weather alert, a
rate survey, a recall, the Visa Bulletin, the lectionary), writes the post in
your voice, checks it against the rules of your profession (Fair Housing, Reg
Z, attorney advertising, HIPAA, contractor licensing...), adds a data card as
the picture, and leaves a draft in [Publora](https://publora.com/?utm_source=social-media-skills-for-professionals&utm_medium=skill&utm_content=readme) for
you to approve. One signature move per profession: a post that starts itself
when the data changes.

Each bundle is a separate repo with 3 skills (a monthly planner, a post writer
with the profession's compliance check, and the signature skill), 100+ post
ideas, a year calendar, and an optional autopilot that only ever creates
drafts.

## The bundles

| Profession | Repo | Signature skill | Checks |
|---|---|---|---|
| Roofing contractors and roofers | [`roofing-social-media-skills`](https://github.com/sergebulaev/roofing-social-media-skills) | Storm Watch | license and storm-claim |
| Veterinarians and veterinary clinics | [`veterinary-social-media-skills`](https://github.com/sergebulaev/veterinary-social-media-skills) | Pet Risk Radar | owner consent, no-diagnosis and claims |
| Real estate agents, REALTORS® and brokers | [`realtor-social-media-skills`](https://github.com/sergebulaev/realtor-social-media-skills) | Market Report | Fair Housing and brokerage |
| Dentists and dental practices | [`dental-social-media-skills`](https://github.com/sergebulaev/dental-social-media-skills) | Benefits Countdown | HIPAA and ADA Code |
| Restaurant owners, chefs and restaurant managers | [`restaurant-social-media-skills`](https://github.com/sergebulaev/restaurant-social-media-skills) | Menu Calendar | FTC reviews, fees and alcohol |
| Immigration lawyers and immigration law firms | [`immigration-lawyer-social-media-skills`](https://github.com/sergebulaev/immigration-lawyer-social-media-skills) | Visa Bulletin Day | ABA advertising rules and no-notario |
| Mortgage loan officers and mortgage brokers | [`mortgage-social-media-skills`](https://github.com/sergebulaev/mortgage-social-media-skills) | Thursday Rate Desk | Reg Z and NMLS |
| Churches, pastors and church communications teams | [`church-social-media-skills`](https://github.com/sergebulaev/church-social-media-skills) | Sermon Week | 501(c)(3) and music license |

## How every bundle works

1. **Memory.** A short interview once: business, city and ZIPs, state,
   license or ID numbers, voice. Saved as markdown in your folder.
2. **Sources.** Public feeds with exact URLs (and a paste-it fallback when a
   site blocks scripts). Every number in a post must come from them or from
   your memory.
3. **The check.** The profession's rules plus the FTC rules on reviews,
   endorsements and fees, shown on every post with what was fixed. "Just post
   it" does not skip it.
4. **A draft, not a post.** Scheduling only after you say yes to a read-back.

Install any bundle the same way:

```
/plugin marketplace add sergebulaev/<repo>
npx skills add sergebulaev/<repo>
```

Not legal advice: the rules are each bundle's reading of public sources, with
the source and the date it was checked.

---

MIT License.

Built by Serge Bulaev, founder of Publora.

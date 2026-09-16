<p align="center">
  <img src="https://raw.githubusercontent.com/FindsYou-Work/.github/main/assets/org-banner.png" alt="FindsYou — stop looking. It finds you work." width="100%">
</p>

<p align="center">
  <a href="https://findsyou.work"><img src="https://img.shields.io/badge/FINDSYOU.WORK-LIVE-E3D3A4?style=for-the-badge&labelColor=0E0B10" alt="findsyou.work"></a>
  <img src="https://img.shields.io/badge/WAITLIST-SHIPPING-ECE6EA?style=for-the-badge&labelColor=0E0B10" alt="Waitlist: shipping">
  <img src="https://img.shields.io/badge/THE%20PRODUCT-PLANNED-8F878F?style=for-the-badge&labelColor=0E0B10" alt="The product: planned">
</p>

<p align="center">
  <sub>
    <a href="https://findsyou.work">Site</a> &nbsp;·&nbsp;
    <a href="https://findsyou.work/#wall">The wall of no</a> &nbsp;·&nbsp;
    <a href="https://findsyou.work/#remote">Remote, honestly</a> &nbsp;·&nbsp;
    <a href="https://findsyou.work/#how">How it works</a> &nbsp;·&nbsp;
    <a href="https://findsyou.work/#waitlist">Waitlist</a> &nbsp;·&nbsp;
    <a href="https://findsyou.work/llms.txt">llms.txt</a> &nbsp;·&nbsp;
    <a href="https://factory0.ventures">Factory Zero</a>
  </sub>
</p>

---

## Stop looking. It finds you work.

You have applied to ninety jobs. Eleven of them would ever have hired you. The
other seventy-nine were never possible — wrong residency, wrong hours, full-time
only, no sponsorship, or not a real opening at all — and nothing told you that
before you spent the evening on them.

FindsYou reads the boards so you do not have to, throws out the jobs you could
never actually take, and hands back the few that survive with the reason for
every rejection shown rather than hidden.

---

## Nothing is built yet, and this org says so

This matters more than anything else on this page, so it is first.

| | What it is | Status |
| :--- | :--- | :--- |
| **The site** | [`website`](https://github.com/FindsYou-Work/website) — one page, one stylesheet, one script, no build step, on Cloudflare Pages. | `SHIPPING` |
| **The waitlist** | [`waitlist-backend`](https://github.com/FindsYou-Work/waitlist-backend) — a Cloudflare Worker on the [Cratefield](https://cratefield.com) harness `waitlist` module, with a database of its own. | `SHIPPING` |
| **The product** | The scan, the eligibility filter, the evaluation, the documents, the tracker. | `PLANNED` |

The product is not built. Not a line of it. Everything on the site that
describes it carries a `planned` chip, the figures in the funnel are labelled an
illustration, and [`llms.txt`](https://findsyou.work/llms.txt) repeats all of it
in plain text so an answer engine cannot describe a planned feature as
available.

Two labels are used everywhere, and they govern the tense of the sentence around
them:

- `SHIPPING` — built, deployed, usable now. Present tense allowed only here.
- `PLANNED` — named, unbuilt. Conditional tense, and a chip wherever it appears.

---

## The one idea

Every other tool in this category optimises for **more** applications. This one
optimises for **fewer**.

The product is the rejection, not the volume. A list of five jobs with no
explanation is indistinguishable from a bad search; five jobs and four hundred
and sixty-five labelled rejections is a filter you can trust.

```
483  scanned
 34  eligible      ← the part nobody else does
 18  worth it
  5  applied
```

---

## Eligibility, not relevance

Job boards lie about "remote". The listing says remote; the fine print says you
must reside in Germany, or travel 60% of the time, or be online at 9am in
California five days a week. The listing is remote. **The job is not remote for
you.**

Six answers — passport, residency, how you invoice, hours, travel, timezone —
eliminate most of the internet before relevance is even considered. No other
tool asks a single one of them.

Eligibility is not qualification. Whether you are good enough comes second,
because a perfect match you cannot legally take is worth less than nothing.

---

## It will not make things up

Your CV said "two years". A draft tried to write "2 years". It refused to print
until they matched.

Every number in every generated document traces to a line in your own CV, and
the gate has no override — a gate with an override is a suggestion. In a market
filling up with invented résumés, being able to defend every figure in an
interview is worth more than the generation itself.

---

## Built on

[Cratefield](https://cratefield.com) for the backend — Rust compiled to
WebAssembly on Cloudflare Workers, with a database of its own — and
[Factory Zero](https://factory0.ventures)'s shared services for identity,
billing, deployment and observability. New code is written only where no module
already exists.

<p align="center"><sub>a <a href="https://factory0.ventures">Factory Zero</a> venture · <a href="https://findsyou.work">findsyou.work</a></sub></p>

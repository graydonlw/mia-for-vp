# Still needed from Mia

Live at **https://mia-for-vp.vercel.app**. Every push to `main` redeploys it.

**Nothing is outstanding from Mia.** She answered the form on 2026-09-22 and
every blocking item below is closed. What is left is Graydon's, and it is one
physical check.

## How the answers came back (2026-09-22)

A Google Form was sent to Mia (miagracew8@gmail.com) on 2026-09-21. She
submitted it **2026-09-22 10:04 AST**, and supplied a photo of a handwritten
note giving the concrete mechanism behind each of the three promises.

- **Form:** https://docs.google.com/forms/d/e/1FAIpQLSdMnv-fsg5GE329k5JPGCbjT3U2RD_0C_E-0cDmMShSq3IcvA/viewform
- **Responses land in Drive sheet** `1L2EQedcdKGk5QhGM50GN84ARakxgTENL91Ii1Muj-KE`
  ("Mia for VP: what the site still needs (Responses)").

**No agent is notified when she submits.** Nothing pushes; the sheet has to be
read on request. If she submits again, read that sheet via the Drive connector.

Her exact answers, so nobody has to re-open the sheet:

| Question | Her answer |
|---|---|
| Election date | `2026-09-29` (a Tuesday) |
| Promise 1 | "You ask, We listen" · *suggestion box* |
| Promise 2 | "Make School More Fun" · *lunch surprise* |
| Promise 3 | "Celebrate Fellow Students" · *morning announcements, different students; student of the month* |
| Office | Yes, Vice President |
| How voting works | "6th-12th grade votes; votes in homeroom; fill in the ballot" |
| Instagram | none |
| Slogan "Lead with Grace" | keep |
| "I won't go M.I.A." line | keep |
| Anything else to change | "nothing" |

The italics are from her handwritten note, not the form. The form gave the
three headlines; the note gave what each one actually is. The site uses the
headline as the card title and the mechanism as the card body.

## Closed

- [x] ~~**Election date.**~~ Done 2026-09-22. `ELECTION_DATE = "2026-09-29"`.
      Fills the hero countdown, the How to vote card, the CTA, the footer and
      the page title.
- [x] ~~**The three promises.**~~ Done 2026-09-22, in `#platform`, her words.
- [x] ~~**A photo.**~~ Done 2026-09-21. Three supplied and wired in: the hero
      arch, the About arch, and the round portrait in the vote CTA. `og:image`
      is set, so link previews are no longer blank.
- [x] ~~**Voting logistics.**~~ Done 2026-09-22, in the three `#vote` cards.
- [x] ~~**Campaign Instagram.**~~ Closed 2026-09-22. She has none. `INSTAGRAM`
      stays `null` and both links stay hidden. Set a URL if that ever changes.
- [x] ~~**Confirm the office is Vice President.**~~ Confirmed 2026-09-22.
- [x] ~~Delete `<div id="draft-banner">`.~~ Done 2026-09-22.
- [x] ~~Delete every element with `class="todo"`.~~ Done 2026-09-22.
- [x] ~~Search the file for `[` and make sure no bracketed placeholder
      survived.~~ Done 2026-09-22. The only `[` left are the `[hidden]` CSS
      selector and JS array indexing.

## Left, and it is Graydon's

- [ ] **Scan the QR code on a real phone before printing any of them.** The
      codes live in `brand/assets/qr/` and the printable sheet is
      `brand/preview/qr.html`. Open it and print to PDF. It decodes in
      software down to 150px, but a real camera is the only test that counts.
      **The election is 2026-09-29.** If posters are part of the plan, this is
      the long pole.
- [ ] **Re-generate the QR codes if the URL ever changes.** They are pointed at
      `https://mia-for-vp.vercel.app`. A custom domain, or anything else that
      moves the site, makes every printed code dead paper.

## Decisions already made, so nobody relitigates them

- Slogan is **"Lead with Grace"**, confirmed by Mia, 2026-09-22. "I won't go
  M.I.A." stays as one line at the end of the About section; she confirmed keep.
- The page is **four sections**: hero, platform, about, how to vote (2026-09-20).
  "The job", her letter, the quotes block and the feedback section were cut as
  extra pages. If feedback comes back, it goes through a **Google Form**, not an
  on-page form: a public repo makes any form endpoint key scrapeable.
- No phone numbers or personal email addresses on the page, and no other
  students' names or faces without a parent's okay.
- **Promise copy is hers, not ours** (2026-09-22). The card bodies describe only
  the mechanism she wrote down: a suggestion box, a lunch surprise, student of
  the month, rotating announcement readers. No deadline, count or venue was
  invented to make them sound more specific. If a promise needs a date on it,
  ask her; do not supply one.

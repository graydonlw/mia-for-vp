# Still needed from Mia

Live at **https://voteformia.vercel.app** — every push to `main` redeploys it.

Everything below is placeholder copy sitting in `index.html`, marked
`[in brackets]` on the page, per `AGENTS.md` rule 6 and `brand/DESIGN.md`
Don't #9: no invented promises, quotes, numbers or dates. Tick these off as
they come in.

## Blocking a real launch

These four are the difference between a draft and something you can put a QR
code on.

- [ ] **Election date.** Set `ELECTION_DATE` in the config block at the bottom of
      `index.html` (format `"2026-10-08"`). It fills the date into the hero
      countdown, the How to vote cards, the CTA, the footer, and the page title.
      One edit, five places.
- [ ] **The three promises.** Specific and checkable, in her words. "A vending
      machine in the north hall by November" beats "more school spirit." Goes in
      `#platform`.
- [ ] **A photo.** Headshot, roughly 4:5 portrait crop. Drop it in
      `brand/assets/`, put an `<img>` inside the `.mv-photo` div in `#about`,
      and add an `og:image` meta tag so link previews aren't blank.
- [ ] **Her letter.** About 150 words, first person, why she's running. This is
      the only part of the site that sounds like a person, so it has to be her
      writing, not anyone else's. Goes in `#letter`.

## Needed, but the page survives without them

- [ ] **What the VP actually does** — three duties, one line each, from the
      student handbook or the StuGov advisor. Do not write these from memory.
      Goes in `#job`. If nobody can produce them, delete the section.
- [ ] **Voting logistics** — the room or period, which grades vote, whether
      students need anything with them. Goes in the three `#vote` cards.
- [ ] **Three quotes** from named people: a teammate, a teacher or coach, a
      friend. Each person has to be okay with their name on a public website.
      Goes in `#people`. **Delete the section rather than invent any of it.**
- [ ] **The Google Form URL** for the feedback section. Three questions, no
      email field, first name optional. Paste into the `Leave feedback` button
      in `#feedback`.

## Optional

- [ ] **Campaign Instagram.** If she has one, set `INSTAGRAM` in the config
      block and the links turn on by themselves. If not, leave it `null` and
      they stay hidden.
- [ ] **Confirm the office is Vice President.** The whole site says VP because
      the brand kit did. Nobody has actually confirmed it.

## Before it goes public

- [ ] Delete `<div id="draft-banner">` at the top of `index.html`.
- [ ] Delete every element with `class="todo"`. Those are the grey notes-to-self
      under each section; there are six of them.
- [ ] Search the file for `[` and make sure no bracketed placeholder survived.
- [ ] Scan the QR code on a real phone before printing any of them.
- [ ] Record the pass in `PROJECT_TRACKER.md` (§2, §6, §10, §11). The tracker is
      a symlink into the local vault and is gitignored, so it cannot be updated
      from the project thread — it has to happen on the machine that has it.

## Decisions already made, so nobody relitigates them

- Slogan is **"Lead with Grace"**. "I won't go M.I.A." is kept as one line at the
  end of the About section. Cut it if Mia doesn't like it.
- Feedback goes through a **Google Form**, not an on-page form. A public repo
  means any form endpoint key is scrapeable, and a Google Form can be switched
  off in one click if it gets abused.
- The feedback form asks for a **first name**. Fully anonymous feedback from high
  schoolers, on a site with her name on it, is a bad trade.
- No phone numbers or personal email addresses on the page, and no other
  students' names or faces without a parent's okay.

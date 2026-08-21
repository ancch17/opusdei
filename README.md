# In Conversation with Mgr Mariano Fazio

A one-page invitation and donation appeal for a free public evening in Singapore
on **Friday 28 August 2026, 7.30–9.30pm**, with Monsignor Mariano Fazio
(Auxiliary Vicar of Opus Dei) in conversation with Sharon Tong.

Admission is free. The page invites those who can to cover the cost of a seat
via PayNow.

## What's here

- `index.html` — the entire site. One self-contained file: all CSS, JavaScript
  and the PayNow QR code (embedded as a base64 PNG) live inside it. No build
  step, no dependencies, nothing to install.

The only external request the page makes is to Google Fonts for the two
typefaces (Newsreader and Source Sans 3). It degrades to system serif and
sans-serif if that request is blocked.

## Publishing with GitHub Pages

1. Push `index.html` to the `main` branch of this repo.
2. **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
3. Save. The site goes live at **https://ancch17.github.io/opusdei/** within a
   minute or two.

Free GitHub Pages requires the repository to be **public**. If the repo is
private you'll need a paid GitHub plan, or make it public.

## Payment details shown on the page

| | |
|---|---|
| Payee | OPUS DEI SINGAPORE |
| PayNow UEN | 200304256M |
| Reference | PRELATURE DONATION |
| Amount | Chosen by the giver (the QR has no fixed amount) |

The QR was regenerated from the original PayNow image and verified to decode
byte-for-byte identically. The page collects nothing from visitors — no card
details, no accounts, no analytics, no cookies. Payment happens entirely inside
the giver's own banking app.

## Updating the event

The countdown, the date and the registration link are hard-coded. To change the
event, edit these in `index.html`:

- the two `new Date('2026-08-28T…+08:00')` values in the countdown script
- the registration URL (`https://tinyurl.com/InConversationDonMariano`)
- the date and time text in the hero and in the "Friday, and how to be there"
  table

## Note

This is a supporter's page, not the official website of Opus Dei. The official
site for Singapore is https://opusdei.org/en-sg/

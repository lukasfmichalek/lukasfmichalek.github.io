# lukasfmichalek.github.io

Personal academic website of Lukas F. Michalek, built with plain Jekyll on GitHub Pages.

The earlier lab-style "Frontier Metrology" version is kept on the branch `claude/archive-frontier-metrology` as a starting point for a future group website.

## Structure

| Page | File |
| --- | --- |
| Home | `index.html` |
| Research | `_pages/research.html` |
| Publications | `_pages/publications.html` (reads `_data/publications.yml`) |
| Teaching & Mentoring | `_pages/teaching.html` |
| Service & Outreach | `_pages/service.html` |
| CV | `_pages/cv.html` |

Old URLs (`/about/`, `/contact/`, `/methods/`, `/resources/`) redirect to their new places.

## Updating content

- **Publications:** edit `_data/publications.yml`. Keep year order; within a year, lead-author papers first. `roles` (first, second, last, corresponding) adds the badge and the lead-author filter; `selected: true` puts a paper on the homepage.
- **News:** edit `_data/news.yml`, newest first. The homepage shows the latest seven.
- **Navigation:** `_data/navigation.yml`.

## Images

Image slots show a placeholder until a file exists at the slot's path. To swap an image, replace the file at the same path with one of the same shape (at least 1600 px on the long side).

| Path | Where it appears | Shape |
| --- | --- | --- |
| `assets/images/research/theme-1-interfaces.jpg` | Home cards, Research theme 1 | 4:3 |
| `assets/images/research/theme-2-soft-electronics.jpg` | Home cards, Research theme 2 | 4:3 |
| `assets/images/research/theme-3-nanomechanics.jpg` | Home cards, Research theme 3 | 4:3 |
| `assets/images/research/theme-4-instruments.jpg` | Home cards, Research theme 4 (NRF overview schematic) | 4:3 |
| `assets/images/lab/portrait-instrument.jpg` | Research, Approach | 4:3 |
| `assets/images/teaching/training.jpg` | Teaching | 4:3 |
| `assets/images/service/service.jpg` | Service (IMC20 talk) | 4:3 |
| `assets/images/outreach/nnci-image-contest.jpg` | Service, Outreach gallery | 3:2 |
| `assets/images/outreach/outreach-1.jpg`, `outreach-2.jpg` | Service, Outreach gallery | 3:2 |
| `assets/images/personal/running.jpg` | Home, Beyond the lab | 4:5 portrait |
| `assets/images/cv/phd-thesis-award.jpg` | CV sidebar | 4:3 |
| `assets/images/cv/dfg-walter-benjamin.png` | CV sidebar | 1000:586 |
| `assets/files/CV_Michalek.pdf` | CV download button | PDF |

Not yet used: a mentoring or group photo for the Teaching page (`assets/images/teaching/mentoring-group.jpg`, 4:3) would need the slot added back in `_pages/teaching.html`.

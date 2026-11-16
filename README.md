# Noron Air / Arc Display Compatibility List

**Display Compatibility List** for [Noron Air](#) and [Noron Arc](#).

This public list is built by customers. Report which 42" or 43" monitor or TV you bought, in which country, and whether it works on Noron Air or Arc, so others can choose by region.

> First manufacturer-tested entry: Philips 438P1 (China and Australia). Community reports from the [NDX buyers spreadsheet](https://docs.google.com/spreadsheets/d/14gYCxoQaE_ZrAnFhPV41KW_xbj3A5Z86KZE-r6QMmNs/edit?gid=0#gid=0) have also been added. Please keep submitting the models available in your country.

---

<a id="requirements"></a>

## Requirements

Noron Air and Noron Arc only support **42" or 43"** monitors or TVs, and **all four** of the following must be true:

| Requirement | Detail |
| --- | --- |
| **VESA 200 × 200** | The mount holes must be 200 mm × 200 mm. Other patterns will not fit. |
| **Thickness at the mount < 78 mm** | Thickness at the mounting area, including any bulge, must be under 78 mm. |
| **Cables must exit from the side** | The bracket has **no rear cable opening**, so power and video cables must exit from the **side**. Rear-only ports will not route. |
| **Game Mode is required** | **Game Mode** (or an equivalent low-latency mode) is required. Without it, input lag will be unusable. |

Please check these four points before submitting. If a display fails one of them, we still want the report, with the reason, so others do not buy the same mistake.

---

## Submit yours

You do not need to write code. Open an issue, fill in the form, and attach photos if you can (VESA holes, thickness at the mount, side ports, and cable routing after install).

**→ [Open the form](https://github.com/noron-official/noron-display-compatibility/issues/new?template=report.yml)**

After review, confirmed reports are added to the list below and to [`data/displays.csv`](data/displays.csv).

---

## Compatibility list

Rows are grouped by country. The same model gets one row per country where it is sold.

Community rows imported from the [NDX buyers spreadsheet](https://docs.google.com/spreadsheets/d/14gYCxoQaE_ZrAnFhPV41KW_xbj3A5Z86KZE-r6QMmNs/edit?gid=0#gid=0) were tested on **NDX**, as reported there. Official depth figures are manufacturer specs without the stand, not a caliper measurement at the VESA face.

| Result | Country | Store | Model | Size | Game Mode | Cabinet | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Works | Australia | Local retail | Philips 438P1 | 43 | SmartImage Game | Air / Arc | Manufacturer test: perfect install, very low lag, excellent picture. 43-inch 4K 60Hz IPS. Official depth without stand 64 mm. HDMI / DP / power face down at the bottom; USB on the side. Enable SmartImage Game. Indicative price about USD 360 at the time of this report; check local retail. Community spreadsheet also lists this model in Australia at about $539 AUD: perfect fit, great performance, same monitor as in the NDX controller setup guide on YouTube. |
| Works | China | Local retail | Philips 438P1 | 43 | SmartImage Game | Air / Arc | Manufacturer test: perfect install, very low lag, excellent picture. 43-inch 4K 60Hz IPS. Official depth without stand 64 mm. HDMI / DP / power face down at the bottom; USB on the side. Enable SmartImage Game. Indicative price about USD 360 at the time of this report; check local retail. |
| Works | Italy | Local retail | Samsung Odyssey Neo G7 (LS43CG702NNXZA) | 43 | Game Mode | NDX | Community spreadsheet (verified on NDX). The spreadsheet row was titled Philips 438P1, but the model number LS43CG702NNXZA, 144 Hz, 1 ms, and Europe price match the Samsung Odyssey Neo G7, not the 60 Hz Philips 438P1 (listed separately). Community: 4K 144 Hz and 1 ms, expensive but worth it for 144 Hz; requires M8 screws, so the included screws will not fit; use a thread reducer or enlarge the spacers; spacers were also needed between the monitor and the controller to sit the screen as close as possible. Official VESA 200×200, official depth without stand 37.9 mm. Indicative price about 699,90 € in Italy/Europe (the sheet also listed 999.99 USD); check local retail. |
| Works | United States | Best Buy | Samsung M70H (UN43M70HAFXZA) | 43 | Game Mode | NDX | Community spreadsheet (verified on NDX): perfect fit, great performance, easily available at Best Buy and other US retailers, very little hollow space. Okay brightness; Smart TV UI is annoying. The NDX back mount only takes M6 screws, so M8-to-M6 thread reducers and longer M6 screws are required (this TV uses M8). Turn on Game Mode and disable power-saving features to maximize brightness. Reporter recommends mounting with the HDMIs at the top, to use the physical power button and shorten the power-cable run. 43-inch class 4K 60Hz Mini LED. Official depth without stand is 76.3 mm (under 78 mm, but close). Official VESA 200×200. Indicative price about USD 349.99 before tax and shipping at the time of this report; check local retail. |
| No | United States | Best Buy | TCL Q6 (43Q651G) | 43 |  |  | Community spreadsheet: mounting is uncentered and 100 mm × 200 mm, which causes it to sit short vertically. Official VESA is 100 × 200, which does not fit the 200 × 200 mount. 43-inch class 4K 60Hz. Indicative price about USD 239.99 before tax and shipping at the time of this report. |
| No | United States | Best Buy | LG NU700B (43NU700BPUC) | 43 |  |  | Community spreadsheet: 200 mm × 200 mm uncentered mounting, so it does not fit the NDX mount. Official VESA size is 200 × 200. 43-inch class 4K 60Hz. Indicative price about USD 249.99 before tax and shipping at the time of this report. |
| No | United States | Amazon | LG QNED73 (43QNED73BUA) | 43 |  |  | Community spreadsheet: 300 mm × 300 mm uncentered mounting. Official VESA is 300 × 300, which does not fit the 200 × 200 mount. 43-inch class 4K 60Hz. Indicative price about USD 359.99 before tax and shipping at the time of this report. |
| Issues | Unspecified | LG | LG UA80006LC (43UA80006LC) | 43 | Game Optimizer | NDX | Community spreadsheet (verified on NDX): heavy, which reduces wobble. Pretty thick but still fits. NDX mount railing is short by about 2 cm for a perfectly centered alignment, so the bezel sits a bit to the right; the reporter says this is not major, or you can file the mount railings to add the missing 2 cm. Cable access is not great — plug in everything needed before mounting. 43-inch 4K 60Hz. Official model number is 43UA80006LC (the spreadsheet wrote 43UA8006LC). Official depth without stand is 67.9 mm, official VESA 200×200. The spreadsheet cited “low input lag” from an RTINGS review of the related UT8000, not this exact model. Country was not listed. |

Result labels:

- **Works** — Install and Game Mode are both fine
- **Issues** — Installs, but with lag or other problems
- **No** — Does not work; see notes

---

## Maintainers

This repository is run by Yuancon / Noron. The list comes from customer reports. If a row is wrong, please open an issue.

Official pages and maintainer text stay in English. If a customer submits notes in another language, keep that text as written.

To edit the table directly, change [`data/displays.csv`](data/displays.csv) and open a pull request. Most customers only need the issue form.

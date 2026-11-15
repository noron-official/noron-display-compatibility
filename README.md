# Noron Air / Arc Display Compatibility List

**Display Compatibility List** for [Noron Air](#) and [Noron Arc](#).

This public list is built by customers. Report which 42" or 43" monitor or TV you bought, in which country, and whether it works on Noron Air or Arc, so others can choose by region.

> First manufacturer-tested entry: Philips 438P1 (China and Australia). Please keep submitting the models available in your country.

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

| Result | Country | Store | Model | Size | Game Mode | Cabinet | Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Works | China | Local retail | Philips 438P1 | 43 | SmartImage Game | Air / Arc | Manufacturer test: perfect install, very low lag, excellent picture. 43-inch 4K 60Hz IPS. Official depth without stand 64 mm. HDMI / DP / power face down at the bottom; USB on the side. Enable SmartImage Game. Indicative price about USD 360 at the time of this report; check local retail. |
| Works | Australia | Local retail | Philips 438P1 | 43 | SmartImage Game | Air / Arc | Manufacturer test: perfect install, very low lag, excellent picture. 43-inch 4K 60Hz IPS. Official depth without stand 64 mm. HDMI / DP / power face down at the bottom; USB on the side. Enable SmartImage Game. Indicative price about USD 360 at the time of this report; check local retail. |

Result labels:

- **Works** — Install and Game Mode are both fine
- **Issues** — Installs, but with lag or other problems
- **No** — Does not work; see notes

---

## Maintainers

This repository is run by Yuancon / Noron. The list comes from customer reports. If a row is wrong, please open an issue.

Official pages and maintainer text stay in English. If a customer submits notes in another language, keep that text as written.

To edit the table directly, change [`data/displays.csv`](data/displays.csv) and open a pull request. Most customers only need the issue form.

# Noron Air / Arc 显示器兼容清单

**Display Compatibility List** for [Noron Air](#) and [Noron Arc](#).

这是一份由客户一起维护的公开清单：在哪个国家买了哪款 **42 英寸或 43 英寸** 显示器或电视，能不能装到 Noron Air / Arc 上。后来的客户可以按国家挑选。

This public list is built by customers. Report which 42" or 43" monitor or TV you bought, in which country, and whether it works on Noron Air or Arc, so others can choose by region.

> 已收录第一条厂家实测：飞利浦 Philips 438P1（中国、Australia）。欢迎继续提交你所在国家买到的型号。
> First manufacturer-tested entry: Philips 438P1 (China and Australia). Please keep submitting the models available in your country.

---

<a id="requirements"></a>

## 安装要求 / Requirements

Noron Air 和 Noron Arc 只支持 **42 英寸或 43 英寸** 的显示器或电视，并且必须同时满足下面四条。缺任何一条都可能装不上，或延迟高到无法正常玩。

Noron Air and Noron Arc only support **42" or 43"** monitors or TVs, and **all four** of the following must be true:

| 要求 / Requirement | 说明 / Detail |
| --- | --- |
| **VESA 200 × 200** | 背面安装孔必须是 200 mm × 200 mm。其他孔距不能直接安装。 / The mount holes must be 200 mm × 200 mm. Other patterns will not fit. |
| **安装位厚度 < 78 mm** | 量屏幕背面到 VESA 安装面（含凸起）的厚度，必须小于 78 mm。 / Thickness at the mounting area, including any bulge, must be under 78 mm. |
| **必须侧面出线** | 固定显示器的支架**后面没有出线孔**，电源和 HDMI / DP 等线必须从**侧面**出来。只有后面出线的机型无法正常走线。 / The bracket has **no rear cable opening**, so power and video cables must exit from the **side**. Rear-only ports will not route. |
| **必须有游戏模式** | 需要 Game Mode（或同等低延迟模式）。没有游戏模式时，延迟会非常高，几乎无法接受。 / **Game Mode** (or an equivalent low-latency mode) is required. Without it, input lag will be unusable. |

提交前请先对照这四条。如果某条不满足，也欢迎报上来，并注明不能用的原因，避免其他人买错。

Please check these four points before submitting. If a display fails one of them, we still want the report, with the reason, so others do not buy the same mistake.

---

## 提交你的显示器 / Submit yours

不需要会写代码。打开 Issue、按表格填写即可，尽量附上照片（VESA 孔、安装位厚度、侧面接口、装好后的走线）。

You do not need to write code. Open an issue, fill in the form, and attach photos if you can (VESA holes, thickness at the mount, side ports, and cable routing after install).

**→ [填写表格 / Open the form](https://github.com/noron-official/noron-display-compatibility/issues/new?template=report.yml)**

我们收到后，会把核实过的记录整理进下面的清单和 [`data/displays.csv`](data/displays.csv)。

After review, confirmed reports are added to the list below and to [`data/displays.csv`](data/displays.csv).

---

## 兼容清单 / Compatibility list

按国家分行。同一型号若在多个国家有售，会各占一行。

Rows are grouped by country. The same model gets one row per country where it is sold.

| 结果 / Result | 国家 / Country | 渠道 / Store | 品牌型号 / Model | 尺寸 / Size | 游戏模式 / Game Mode | 机柜 / Cabinet | 备注 / Notes |
| --- | --- | --- | --- | --- | --- | --- | --- |
| 能用 / Works | 中国 | 当地零售 | Philips 438P1 | 43 | 有 SmartImage Game | Air / Arc | 厂家实测：完美安装，延迟非常低，显示效果很好。43 英寸 4K 60Hz IPS。官方无底座厚度 64 mm。HDMI / DP / 电源底部向下出线，USB 在侧面。请打开 SmartImage Game。提交时参考售价约 360 美元，请以当地零售为准。 |
| 能用 / Works | Australia | Local retail | Philips 438P1 | 43 | SmartImage Game | Air / Arc | Manufacturer test: perfect install, very low lag, excellent picture. 43-inch 4K 60Hz IPS. Official depth without stand 64 mm. HDMI / DP / power face down at the bottom; USB on the side. Enable SmartImage Game. Indicative price about USD 360 at the time of this report; check local retail. |

结果标记：

- **能用** — 安装和游戏模式都正常 / Works
- **勉强** — 能安装，但延迟或不方便 / Installs, with issues
- **不能用** — 请看备注里的原因 / Does not work; see notes

---

## 维护 / Maintainers

这份仓库由 Yuancon / Noron 建立，清单内容来自客户提交。如果你发现某条记录有误，请新开一个 Issue 说明。

This repository is run by Yuancon / Noron. The list comes from customer reports. If a row is wrong, please open an issue.

想直接改表格，可以编辑 [`data/displays.csv`](data/displays.csv) 后发 Pull Request。大多数客户用上面的表格提交即可。

To edit the table directly, change [`data/displays.csv`](data/displays.csv) and open a pull request. Most customers only need the issue form.

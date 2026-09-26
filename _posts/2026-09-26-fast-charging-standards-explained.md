---
layout: post
title: "Fast Charging Standards Explained: PD, QC, VOOC, and Wireless Qi2"
description: "USB Power Delivery, PPS, Quick Charge, SuperVOOC and Qi2 explained: what each standard does, which phones use it, and how to pick a charger that actually delivers full speed."
date: 2026-09-26 10:00:00 +0530
tags: [charging, usb-c, android, iphone]
---

Buy a new phone today and there's a good chance it doesn't come with a charger. So you head online and find a wall of options: 20W, 45W, 67W, 120W, "PD 3.0", "QC 4+", "SuperVOOC", "Qi2"... and a nagging worry that the wrong one will charge slowly, or worse, damage your phone.

The reassuring part first: **any modern USB-C charger is safe with any modern phone**. Chargers and phones negotiate before any real power flows, and they settle on the fastest mode they both understand. The only question is how fast that turns out to be. That's what the standards decide.

![USB-C cable and charging adapters on a marble surface](https://images.pexels.com/photos/3921630/pexels-photo-3921630.jpeg?auto=compress&cs=tinysrgb&h=650&w=940)
*Photo by ready made on Pexels*

## Power in one line: watts = volts × amps

Every fast-charging trick is a way of pushing more watts into the battery. You can raise the voltage, raise the current, or both. The standards differ in *how* they do it and who controls it.

## USB Power Delivery (USB-PD): the universal one

USB-PD is the open standard from the USB Implementers Forum, and it's the closest thing to a universal language for charging.

- Works over USB-C on both ends.
- Supports fixed voltage steps (5V, 9V, 15V, 20V) up to 100W, and up to **240W** with the newer Extended Power Range, which is mostly used by laptops.
- Used by iPhones, Google Pixels and most laptops, and supported by almost every other phone as a fallback.

**If you only buy one charger, make it a USB-PD charger.**

### PPS: the add-on that matters for Samsung

**Programmable Power Supply (PPS)** is part of the USB-PD spec. Instead of jumping between fixed voltages, the phone can ask for tiny adjustments (in 20 millivolt steps) as the battery fills up. That keeps the charger doing the voltage conversion instead of the phone, so the phone runs cooler and charges faster.

Samsung's "Super Fast Charging" (25W and 45W) requires **PD with PPS**. A plain PD charger will work on a Galaxy, but it will fall back to slower speeds. Look for "PPS" on the charger's label.

## Qualcomm Quick Charge (QC)

Quick Charge started as Qualcomm's way to raise voltage over old USB-A cables. It was huge in the micro-USB era.

- QC 3.0 is still common on older chargers and budget phones.
- **QC 4+ and QC 5 are compatible with USB-PD**, which is why the line between "QC charger" and "PD charger" has blurred.

Today QC matters less than it used to. Most phones that support Quick Charge also accept USB-PD.

## VOOC, SuperVOOC and other brand-specific systems

OPPO's **VOOC** and **SuperVOOC** (also used by OnePlus and Realme), Xiaomi's **HyperCharge**, and Honor's and vivo's own systems take a different approach: very high current, handled by chips in both the charger and the cable. That's how some phones reach 80W, 100W or even more.

The catch:

- You need the **brand's own charger and cable** to get the headline speed.
- With a normal USB-PD charger, these phones typically charge at roughly 18–45W depending on the model. That's still fine, just not the number on the box.

## Wireless: Qi, MagSafe and Qi2

**Qi** is the long-standing wireless standard, usually 5–15W. The weakness has always been alignment: put the phone slightly off-centre and it charges slowly or not at all.

**Qi2** builds magnets into the standard, based on Apple's MagSafe design. The phone snaps into the right spot every time, which makes wireless charging faster and more efficient in practice. Qi2 started at 15W, and newer versions allow higher speeds on supported phones.

![Black smartphone next to a charger](https://images.pexels.com/photos/20665776/pexels-photo-20665776.jpeg?auto=compress&cs=tinysrgb&h=650&w=940)
*Photo by Andrey Matveev on Pexels*

Wireless is always less efficient than a cable. More energy turns into heat, so it's best for overnight or desk top-ups rather than quick boosts.

## Quick reference table

| Standard | Typical phones | Top speed on phones | Needs special cable/charger? |
|---|---|---|---|
| USB-PD | iPhone, Pixel, most Android | ~20–45W | No, any PD charger |
| USB-PD + PPS | Samsung Galaxy | 25W / 45W | PPS-capable charger |
| Quick Charge 3/4+/5 | Older and budget Android | 18–100W | QC charger (QC4+/5 also PD) |
| SuperVOOC / HyperCharge etc. | OPPO, OnePlus, Realme, Xiaomi | 67–120W+ | Yes, brand charger and cable |
| Qi / Qi2 | Most flagships, iPhone | 5–25W wireless | Qi2 pad for magnetic alignment |

## How to pick the right charger

1. **Check what your phone supports.** The spec sheet will say PD, PPS, QC or a brand system.
2. **Buy a charger that matches or exceeds it.** A 65W PD charger won't force 65W into a 25W phone; the phone only takes what it can handle.
3. **Don't ignore the cable.** For anything above 60W on USB-C you need a cable rated for 5A (100W or 240W). Brand fast-charging systems need their own cable.
4. **One GaN charger for everything.** A 65W GaN charger with USB-PD and PPS will charge a laptop, an iPhone and a Galaxy at full speed, and it's small enough to travel with.

## Watch: every standard in one video

<div style="position:relative;padding-bottom:56.25%;height:0;overflow:hidden;"><iframe style="position:absolute;top:0;left:0;width:100%;height:100%;" src="https://www.youtube.com/embed/hScecDuwXLg" title="Every Fast Charging Standard Explained" frameborder="0" allowfullscreen></iframe></div>

## Does fast charging hurt the battery?

Heat is what ages lithium-ion batteries, not speed by itself. Phones manage this by charging fastest when the battery is low and slowing down past roughly 70–80%. If you're worried, use optimized/adaptive charging overnight and save the full-speed boost for when you actually need it.

## Comparing phones by charging speed

Charging speeds vary more between phones than almost any other spec: from about 20W on some flagships to over 100W on others. If fast top-ups matter to you, [infozme's fast-charging phone list](https://infozme.com/best-phones/fast-charging/) makes it easy to compare real charging specs across brands before you buy.

*This article was written with the help of AI.*

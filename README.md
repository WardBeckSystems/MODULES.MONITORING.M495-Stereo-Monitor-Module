# M495 Stereo Monitor Module · Monitoring

Ward-Beck Systems M495, 1972|5. Wiki page: [M495 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M495.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 77 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 10 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 11 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 294 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 4 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 22 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 50 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [11 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1975 - M495 - Stereo Monitor Module (2).pdf](MANUALS/1975%20-%20M495%20-%20Stereo%20Monitor%20Module%20(2).pdf) page 2 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Gain** | 2 dB.±0.5 dB maximum. |
| **Frequency response** | ±0.25 dB, from 30 Hz to 20 kHz. |
| **Noise** | 80 dB below nominal output of ~ dBm. (20 Hz to 20 kHz). |
| **Harmonic distortion** | Less than 0.25 % THD from 30 Hz to 20 kHz at +18 dBm output or less. Less than 0.1% at mid-band at +18 dBm output. |
| **Source impedances** | 600 ohms~r less, balanced/unb~lanced. |
| **Input impedances** |  |
| &nbsp;&nbsp;Monitor | 30,000 ohms, balanced. |
| &nbsp;&nbsp;Talk back | 30,000 ohms, balanced. |
| &nbsp;&nbsp;Input levels | +8 dBm nominal, +24 dBm maximum. |
| **Output impedances** | 600 ohms, balanced. |
| **Load impedances** | 600 ohms, balanced. |
| **Output levels** | 0 dBm nominal, +20 dBm maximum. |
| **Channel separation** | Better than 50 dB, from 30 Hz to 20 kHz, better than 70 dB at 1 kHz. |
| **Phasing** | -----r n-put ---aifdoilt pirt --t e r mi n-a1s designated by numbers are in phase. |
| **Power requirements** | ±25 volts dc, 45 rnA nominal, 60 rnA maximum. |
| **Ambient temperature** | 0 to 60 degrees Celsius. |
| **Dimensions** | 1.6&quot; wide X 7&quot; high X 6.5&quot; deep. (41 mm X 178 mm X 165 mm). |

## Circuit description

From [1975 - M495 - Stereo Monitor Module (2).pdf](MANUALS/1975%20-%20M495%20-%20Stereo%20Monitor%20Module%20(2).pdf) pages 3-6 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

The M495 allows the selection of five stereo si9na1 sources from within a console system. Provision is made for simultaneous level adjustment and muting of both channels as maybe required. The module outputs are designed for driving an external monitor amplifier as well as a 600 ohm headset feed.

Monitor Inputs Source selection is made with an interlocked two-channel, fivestation push-button assembly.

A separate input i s provided for ta1kback facilities and appears on the left channel only.

Preamplifiers ZI, Z2 and their associated components form the balanced, high input impedance preamplifier used for the LEFT channel. The output of Z2 is coupled through C13 to one half of the level control (R25). From the level control, the signal is coupled through C15 and R27 to pin E2 of the 5-101B booster amplifier. The RIGHT channel signal is processed in an identical manner via Z3, Z4, C14 and the second half of the level control (R26). From R26, the signal is routed through C16 and R29 to pin E6 of the 5-101B amplifier. A balance trim control R2B is inserted between C16 and R29.

Outputs A 5-101B dual booster amel if-ier--is -emp-loye d-i-n-.t he-·-{) ut putstage.

Two output feeds are provided for each of the two stereo channels, one of which is brought out directly from the 5-101B amplifier, whereas the second feed is routed through the contacts of a muting relay.

Muting

The muting relay Kl maybe operated either by the mute push

button SW6 or externally by aground closure at pin X of the

module connector. The LED DSI is illuminated when the muting

function is activated.

Power Supply Decoupling Cll through C20 together with R42 and R43 form a passive onboard power supply decoupling ·circuit. CRI and CR2 prevent module damage in the event of accidental polarity reversal of the supply voltages.

**PARTS LIST**

PART DESCRIPTION MFG MFG PART NUMBER C1 Capa~it or 4.7 uF/10 V Kem et T390B475M010AS

C7 10 p' F Ph~l ips 2222 -638-1 0109

Cll 0.047 uF Aselco CQ92 -MC-473M C1 2 &quot; &quot; &quot; C13 33 uF/10 V Keme t T390D 336M01 0A S

C17 22 uF/ 25 V Ph ~lips 426ET F22

C21 22 uF/ 25 V Kemet T390D22 6M025AS

CR1 Diode Motorola 1N400 3

CR3 Fa irc hil d 1N4148 CR4 Motorola 1N400 3 CR5 Fair child 1N4148 CR6 lewer ·-I N753A

OS 1 LED, red FLV1l7

K1 Relay Clare MRB 4A24

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdUNQOGZkdnZ0eDA/view?resourcekey=0-8sBV-3QQOvuf0TC9y567YQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdUNQOGZkdnZ0eDA&resourcekey=0-8sBV-3QQOvuf0TC9y567YQ" width="240" alt="1975 - M495 - Stereo Monitor Module.jpg"></a><br><sub>1975|8 · Stereo Monitor Module</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1975|8 · wbsps - module - m495 stereo monitor module_small](https://drive.google.com/file/d/0B0yR0b5T78SKY1h0MVpQUmZYNnM/view?resourcekey=0-Sb721EvQ1B1doCRbPrwfzw)

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcndLbU9wSGVNdDQ/view?resourcekey=0-catyrgU6n6GiZBkeGHhcSg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcndLbU9wSGVNdDQ&resourcekey=0-catyrgU6n6GiZBkeGHhcSg" width="240" alt="1975 - M495 - 461-03-015 - DUAL BOOSTER AMPLIFIER.jpg"></a><br><sub>1975|8 · 461-03-015 - DUAL BOOSTER AMPLIFIER · <a href="MECHANICAL/1975%20-%20M495%20-%20461-03-015%20-%20DUAL%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcmw0SENObmNzQ2M/view?resourcekey=0-k3u0FvVPYbYRyyxPyOo2Yw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcmw0SENObmNzQ2M&resourcekey=0-k3u0FvVPYbYRyyxPyOo2Yw" width="240" alt="1975 - M495 - 495-04-003 - THE ASSOC IATED LED WILL INDI- IGNA LEVE.jpg"></a><br><sub>1975|8 · 495-04-003 - THE ASSOC IATED LED WILL INDI- IGNA LEVE · <a href="MECHANICAL/1975%20-%20M495%20-%20495-04-003%20-%20THE%20ASSOC%20IATED%20LED%20WILL%20INDI-%20IGNA%20LEVE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M495.stl`](MECHANICAL/M495.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M495)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 1.6" wide X 7" high X 6.5" deep. (41 mm X 178 mm X 165 mm).)
- **From the drawing:** 7 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M495 - front panel.svg`)
- Made by `tools/module_models.py` (→ `MECHANICAL/M495.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1atCAI0NWJ7gvrsKuRBTZAEq3bn852SrS/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1atCAI0NWJ7gvrsKuRBTZAEq3bn852SrS" width="240" alt="1972 - M495 - DOC - 495-02-001 - STEREO MONITOR MODULE SCHEMATIC.jpg"></a><br><sub>1972|5 · DOC - 495-02-001 - STEREO MONITOR MODULE SCHEMATIC · <a href="SCHEMATICS/1972%20-%20M495%20-%20DOC%20-%20495-02-001%20-%20STEREO%20MONITOR%20MODULE%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdmVyOGNMZzE1MnM/view?resourcekey=0-xde-m-4VosmXboh47LULYQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdmVyOGNMZzE1MnM&resourcekey=0-xde-m-4VosmXboh47LULYQ" width="240" alt="1975 - M495 - 101-02-003 - ALL ICS LMGOI AND ALL DIODES.jpg"></a><br><sub>1975|8 · 101-02-003 - ALL ICS LMGOI AND ALL DIODES · <a href="SCHEMATICS/1975%20-%20M495%20-%20101-02-003%20-%20ALL%20ICS%20LMGOI%20AND%20ALL%20DIODES%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTXZ1YlJlZVFtdU0/view?resourcekey=0-_AnNFD6SS3AFN70WcEFmzA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTXZ1YlJlZVFtdU0&resourcekey=0-_AnNFD6SS3AFN70WcEFmzA" width="240" alt="1975 - M495 - 101-02-003 - XTERNAL CONNECTIDN.jpg"></a><br><sub>1975|8 · 101-02-003 - XTERNAL CONNECTIDN · <a href="SCHEMATICS/1975%20-%20M495%20-%20101-02-003%20-%20XTERNAL%20CONNECTIDN%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnBKOGtsUzd6V3M/view?resourcekey=0-FSy286psD8FpjMpQIv62iQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnBKOGtsUzd6V3M&resourcekey=0-FSy286psD8FpjMpQIv62iQ" width="240" alt="1975 - M495 - 101-02-003.jpg"></a><br><sub>1975|8 · 101-02-003 · <a href="SCHEMATICS/1975%20-%20M495%20-%20101-02-003%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeEJLMk5IMDlqZUk/view?resourcekey=0-b3SjKfI7F2jggYSqES7i1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeEJLMk5IMDlqZUk&resourcekey=0-b3SjKfI7F2jggYSqES7i1w" width="240" alt="1975 - M495 - 495-01-001 - ENG CKDRAL STEREO MONITOR MODULE.jpg"></a><br><sub>1975|8 · 495-01-001 - ENG CKDRAL STEREO MONITOR MODULE · <a href="SCHEMATICS/1975%20-%20M495%20-%20495-01-001%20-%20ENG%20CKDRAL%20STEREO%20MONITOR%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFJVQ3BFQklxcXM/view?resourcekey=0-srvUD8NG-6h7ZFpS9Cvd4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFJVQ3BFQklxcXM&resourcekey=0-srvUD8NG-6h7ZFpS9Cvd4w" width="240" alt="1975 - M495 - 495-01-001 - PRE MONITOR.jpg"></a><br><sub>1975|8 · 495-01-001 - PRE MONITOR · <a href="SCHEMATICS/1975%20-%20M495%20-%20495-01-001%20-%20PRE%20MONITOR%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdWU0dmZrSjhPZDA/view?resourcekey=0-k2JJ3fjnsqzb05nWzbP17w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdWU0dmZrSjhPZDA&resourcekey=0-k2JJ3fjnsqzb05nWzbP17w" width="240" alt="1975 - M495 - 495-02-001 - IBV LMZOL' RIS.jpg"></a><br><sub>1975|8 · 495-02-001 - IBV LMZOL' RIS · <a href="SCHEMATICS/1975%20-%20M495%20-%20495-02-001%20-%20IBV%20LMZOL%27%20RIS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTTB0TVRkXzlxOTA/view?resourcekey=0-8Nb47HCQA40cpGzg-sryxg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTTB0TVRkXzlxOTA&resourcekey=0-8Nb47HCQA40cpGzg-sryxg" width="240" alt="1975 - M495 - 495-02-001 - STEREO MONITOR MODULE.jpg"></a><br><sub>1975|8 · 495-02-001 - STEREO MONITOR MODULE · <a href="SCHEMATICS/1975%20-%20M495%20-%20495-02-001%20-%20STEREO%20MONITOR%20MODULE%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSjZ2SjhBbTYxeFU/view?resourcekey=0-8mLo5stMmY149Ib8x4pJtQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSjZ2SjhBbTYxeFU&resourcekey=0-8mLo5stMmY149Ib8x4pJtQ" width="240" alt="1975 - M495 - 495-06-001 - CKDRA STEREO MONITOR MODUE.jpg"></a><br><sub>1975|8 · 495-06-001 - CKDRA STEREO MONITOR MODUE · <a href="SCHEMATICS/1975%20-%20M495%20-%20495-06-001%20-%20CKDRA%20STEREO%20MONITOR%20MODUE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKME5wSVBNaTBKcXc/view?resourcekey=0-riqVdET3g80SmBzGo_5zqg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKME5wSVBNaTBKcXc&resourcekey=0-riqVdET3g80SmBzGo_5zqg" width="240" alt="1975 - M495 - 495-06-001 - LMZOI LMZOI.jpg"></a><br><sub>1975|8 · 495-06-001 - LMZOI LMZOI · <a href="SCHEMATICS/1975%20-%20M495%20-%20495-06-001%20-%20LMZOI%20LMZOI%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTW9lSWxaZ0tYR2s/view?resourcekey=0-kJtasrNLIRBJVIbV_rL_CQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTW9lSWxaZ0tYR2s&resourcekey=0-kJtasrNLIRBJVIbV_rL_CQ" width="240" alt="1975 - M495 - 5-101-06-003.jpg"></a><br><sub>1975|8 · 5-101-06-003 · <a href="SCHEMATICS/1975%20-%20M495%20-%205-101-06-003%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbk9TNXZtVEpWQkE/view?resourcekey=0-PBYrToT6FLBFNyFpqyEW4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbk9TNXZtVEpWQkE&resourcekey=0-PBYrToT6FLBFNyFpqyEW4w" width="240" alt="1975 - M495 - 5_101-02-003 - DUAL BOOSTER AMPLIFIER.jpg"></a><br><sub>1975|8 · 5_101-02-003 - DUAL BOOSTER AMPLIFIER · <a href="SCHEMATICS/1975%20-%20M495%20-%205_101-02-003%20-%20DUAL%20BOOSTER%20AMPLIFIER%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/14YqAMmWY67ClNiUGVpqIYMz3p16r2tE6/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=14YqAMmWY67ClNiUGVpqIYMz3p16r2tE6" width="240" alt="1992 - M495 - DOC - 920063-01-002 - PQWER DISIEIBUTIQN PSI.jpg"></a><br><sub>1992|25 · DOC - 920063-01-002 - PQWER DISIEIBUTIQN PSI · <a href="SCHEMATICS/1992%20-%20M495%20-%20DOC%20-%20920063-01-002%20-%20PQWER%20DISIEIBUTIQN%20PSI%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1lWgKv5_VD-Jsox-poUGGGBPi3xEVNMbG/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1lWgKv5_VD-Jsox-poUGGGBPi3xEVNMbG" width="240" alt="19xx - M495 - DOC - 600-02-004 - NOVOV MONITOR CHANNELS ARE WIRED IDENTICALLY EXTERNAL INPUTS.png"></a><br><sub>19xx - M495 - DOC - 600-02-004 - NOVOV MONITOR CHANNELS ARE WIRED IDENTICALLY EXTERNAL INPUTS · <a href="SCHEMATICS/19xx%20-%20M495%20-%20DOC%20-%20600-02-004%20-%20NOVOV%20MONITOR%20CHANNELS%20ARE%20WIRED%20IDENTICALLY%20EXTERNAL%20INPUTS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1uNZQpFQsRJmutVdnGzn-J-Fj0CyRnUUP/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1uNZQpFQsRJmutVdnGzn-J-Fj0CyRnUUP" width="240" alt="2006 - M495 - DOC - 920063-01-001 - MONIORMQDULE SWTCHED DIRECT SSUE REMSION.jpg"></a><br><sub>2006|39 · DOC - 920063-01-001 - MONIORMQDULE SWTCHED DIRECT SSUE REMSION · <a href="SCHEMATICS/2006%20-%20M495%20-%20DOC%20-%20920063-01-001%20-%20MONIORMQDULE%20SWTCHED%20DIRECT%20SSUE%20REMSION%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/109KQyA72uuIDv0gHiqS2qh5Zof3KCBMs/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=109KQyA72uuIDv0gHiqS2qh5Zof3KCBMs" width="240" alt="2017 - M495 - DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME.jpg"></a><br><sub>2017|50 · DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME · <a href="SCHEMATICS/2017%20-%20M495%20-%20DOC%20-%20920170-01-001%20-%20SWTCHED%20DIRECT%20MONITOR%20OUTPUTS%20DDZME%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `1975 - 5-101-02-003 - 5-101B DUAL BOOSTER AMPLIFIER SCHEMATIC - DRN DM - ISS 2.jpg`, `1978 - 495-01-001 - STEREO MONITOR MODULE FUNCTIONAL DIAGRAM - DRN MRW - ISS 1.jpg`, `1980 - 495-02-001 - STEREO MONITOR MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 3.jpg`

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQkFqYkkwN2FNTVk/view?resourcekey=0-RFAvL1om4gdfQBD0DtVoxg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQkFqYkkwN2FNTVk&resourcekey=0-RFAvL1om4gdfQBD0DtVoxg" width="240" alt="1975 - M495 - 495-04-002 - RYY CONNECTOR REAR VIEW ALE.jpg"></a><br><sub>1975|8 · 495-04-002 - RYY CONNECTOR REAR VIEW ALE · <a href="PINOUTS/1975%20-%20M495%20-%20495-04-002%20-%20RYY%20CONNECTOR%20REAR%20VIEW%20ALE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

Not on Google Drive yet: `M495 - RTO-144 Connections.pdf`

## RTO-144 pinout

Read from 1 pinout picture (each its own `.pinout.json` beside it); the RTO-144 sheet agrees on 20 of 20 contacts. Every contact, with where it was read: [`RTO.json`](RTO.json). How a picture becomes this table: [the pinout decision tree](https://github.com/WardBeckSystems/WBSps.ca/blob/main/2026/Engineering/PINOUTS.md).

| Pin | Signal | Kind | Port | Confidence |
|---|---|---|---|---|
| 1 | RIGHT IN 5 | in | RIGHT IN 5 R | high |
| 2 | LEFT IN 5 | in | LEFT IN 5 L | high |
| 3 | RIGHT IN 4 | in | RIGHT IN 4 R | high |
| 4 | LEFT IN 4 | in | LEFT IN 4 L | high |
| 5 | RIGHT IN 3 | in | RIGHT IN 3 R | high |
| 6 | LEFT IN 3 | in | LEFT IN 3 L | high |
| 7 | RIGHT IN 2 | in | RIGHT IN 2 R | high |
| 8 | LEFT IN 2 | in | LEFT IN 2 L | high |
| 9 | RIGHT IN 1 | in | RIGHT IN 1 R | high |
| 10 | LEFT IN 1 | in | LEFT IN 1 L | high |
| 11 | TALKBACK IN | in | TALKBACK IN | high |
| 12 | N/C | nc |  | high |
| 13 | N/C | nc |  | high |
| 14 | N/C | nc |  | high |
| 15 | LEFT UNMUTED OUT | out | LEFT UNMUTED OUT L | high |
| 16 | RIGHT UNMUTED OUT | out | RIGHT UNMUTED OUT R | high |
| 17 | LEFT MUTED OUT | out | LEFT MUTED OUT L | high |
| 18 | RIGHT MUTED OUT | out | RIGHT MUTED OUT R | high |
| 19 | -25 V | power |  | high |
| 20 | 25 V COM | ground |  | high |
| 21 | +25 V | power |  | high |
| 22 | CHASSIS | ground |  | high |
| A | RIGHT IN 5 | in | RIGHT IN 5 R | high |
| B | LEFT IN 5 | in | LEFT IN 5 L | high |
| C | RIGHT IN 4 | in | RIGHT IN 4 R | high |
| D | LEFT IN 4 | in | LEFT IN 4 L | high |
| E | RIGHT IN 3 | in | RIGHT IN 3 R | high |
| F | LEFT IN 3 | in | LEFT IN 3 L | high |
| H | RIGHT IN 2 | in | RIGHT IN 2 R | high |
| J | LEFT IN 2 | in | LEFT IN 2 L | high |
| K | RIGHT IN 1 | in | RIGHT IN 1 R | high |
| L | LEFT IN 1 | in | LEFT IN 1 L | high |
| M | TALKBACK IN | in | TALKBACK IN | high |
| N | N/C | nc |  | high |
| P | N/C | nc |  | high |
| R | N/C | nc |  | high |
| S | LEFT UNMUTED OUT | out | LEFT UNMUTED OUT L | high |
| T | RIGHT UNMUTED OUT | out | RIGHT UNMUTED OUT R | high |
| U | LEFT MUTED OUT | out | LEFT MUTED OUT L | high |
| V | RIGHT MUTED OUT | out | RIGHT MUTED OUT R | high |
| W | MUTE ASSIGN | control_in | MUTE ASSIGN | high |
| X | MUTE CONTROL | control_in | MUTE CTL | high |
| Y | +24 V | power |  | high |
| Z | CONTROL COMMON | ground |  | high |

**Straps:** JMP.Z.20: Z 20 · JMP.Y.21: Y 21

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWlhKRS1VUl84Q0U/view?resourcekey=0-rmbGO4V5BCTDV48TiaaosQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWlhKRS1VUl84Q0U&resourcekey=0-rmbGO4V5BCTDV48TiaaosQ" width="240" alt="1975 - M495 - P001 - Title Page.jpg"></a><br><sub>1975|8 · P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaEtZNTlpeS1aOG8/view?resourcekey=0-pab4_OjpqVNz9vZ51J4v6w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaEtZNTlpeS1aOG8&resourcekey=0-pab4_OjpqVNz9vZ51J4v6w" width="240" alt="1975 - M495 - P002 - 1-1.jpg"></a><br><sub>1975|8 · P002 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYTJXUWRZei1fR1U/view?resourcekey=0-Qk4IbqDOz-HZoMPt-7YxpA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYTJXUWRZei1fR1U&resourcekey=0-Qk4IbqDOz-HZoMPt-7YxpA" width="240" alt="1975 - M495 - P003 - 2-1.jpg"></a><br><sub>1975|8 · P003 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX0RVTHA0bU9sbDQ/view?resourcekey=0-5Ln0_AO9MZaP4BniFlm5gw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX0RVTHA0bU9sbDQ&resourcekey=0-5Ln0_AO9MZaP4BniFlm5gw" width="240" alt="1975 - M495 - P004 - 2-2.jpg"></a><br><sub>1975|8 · P004 - 2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKU2ZUMUZtS1lBdW8/view?resourcekey=0-gkVDmtrMG4BnqJ2Idh3q7A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKU2ZUMUZtS1lBdW8&resourcekey=0-gkVDmtrMG4BnqJ2Idh3q7A" width="240" alt="1975 - M495 - P005 - 3-1.jpg"></a><br><sub>1975|8 · P005 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN1hHcVZEWXFETUE/view?resourcekey=0-AdFp9XHaS-TsxTjbn8nMig" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN1hHcVZEWXFETUE&resourcekey=0-AdFp9XHaS-TsxTjbn8nMig" width="240" alt="1975 - M495 - P006 - 3-2.jpg"></a><br><sub>1975|8 · P006 - 3-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdVJ4blp1MHhiYzQ/view?resourcekey=0-pegkOtYvJ0qmSRjBB75jdw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdVJ4blp1MHhiYzQ&resourcekey=0-pegkOtYvJ0qmSRjBB75jdw" width="240" alt="1975 - M495 - P007 - 3-3.jpg"></a><br><sub>1975|8 · P007 - 3-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVVUaTZhX2V1U28/view?resourcekey=0-wk7rPoCHlwE8m5t_xz7eiw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVVUaTZhX2V1U28&resourcekey=0-wk7rPoCHlwE8m5t_xz7eiw" width="240" alt="1975 - M495 - P008 - 3-4.jpg"></a><br><sub>1975|8 · P008 - 3-4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKel9kbTFwbV8wb2s/view?resourcekey=0-ZkFNJOCWviTlWZ9xzra6gg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKel9kbTFwbV8wb2s&resourcekey=0-ZkFNJOCWviTlWZ9xzra6gg" width="240" alt="1975 - M495 - P009 - 5-101-1-1.jpg"></a><br><sub>1975|8 · P009 - 5-101-1-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTWVYVkllOEZrYW8/view?resourcekey=0-vQsjRCuwHWQg-uc0JkSm5A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTWVYVkllOEZrYW8&resourcekey=0-vQsjRCuwHWQg-uc0JkSm5A" width="240" alt="1975 - M495 - P010 - 5-101-1-2.jpg"></a><br><sub>1975|8 · P010 - 5-101-1-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSFp3YXBZUGlSRUU/view?resourcekey=0-g-SSPYA2tQauUn__ug_miA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSFp3YXBZUGlSRUU&resourcekey=0-g-SSPYA2tQauUn__ug_miA" width="240" alt="1975 - M495 - P011 - 5-101-2-1.jpg"></a><br><sub>1975|8 · P011 - 5-101-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKcnM1SFJ6MU1kR0k/view?resourcekey=0-rmzbOIWPXQjEiX9cdw_TXw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKcnM1SFJ6MU1kR0k&resourcekey=0-rmzbOIWPXQjEiX9cdw_TXw" width="240" alt="1975 - M495 - P012 - 5-101-2-2.jpg"></a><br><sub>1975|8 · P012 - 5-101-2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKX2tDZVB2UUF5VkU/view?resourcekey=0-rRC6HVFt2NriEc0E-FZ6eg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKX2tDZVB2UUF5VkU&resourcekey=0-rRC6HVFt2NriEc0E-FZ6eg" width="240" alt="1975 - M495 - P013 - 5-101-2-3.jpg"></a><br><sub>1975|8 · P013 - 5-101-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUVNDUUlFNmhuc1U/view?resourcekey=0-VQvvg8W-TIJCzFHAwXynOQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUVNDUUlFNmhuc1U&resourcekey=0-VQvvg8W-TIJCzFHAwXynOQ" width="240" alt="1975 - M495 - P014 - 5-101B-2-1.jpg"></a><br><sub>1975|8 · P014 - 5-101B-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaGxuLW4za3d5c1E/view?resourcekey=0-0HubM1yIJae9v9lB04hGWA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaGxuLW4za3d5c1E&resourcekey=0-0HubM1yIJae9v9lB04hGWA" width="240" alt="1975 - M495 - P015 - 5-101B-2-2.jpg"></a><br><sub>1975|8 · P015 - 5-101B-2-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbHFWOFRJVUpraWM/view?resourcekey=0-FT3L3aQogYqLUjAsOLgMGg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbHFWOFRJVUpraWM&resourcekey=0-FT3L3aQogYqLUjAsOLgMGg" width="240" alt="1975 - M495 - P016 - 5-101B-2-3.jpg"></a><br><sub>1975|8 · P016 - 5-101B-2-3</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLTlQcFBNVkpQbTg/view?resourcekey=0-YCLKPnYtsPZF4njEtxu3Dg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLTlQcFBNVkpQbTg&resourcekey=0-YCLKPnYtsPZF4njEtxu3Dg" width="240" alt="1975 - M495 - Stereo Monitor Module (2).pdf"></a><br><sub>1975|8 · Stereo Monitor Module (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKallHWk9vUGI3MUE/view?resourcekey=0-8Rh67cZeGRXoNkd3LxYxwg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKallHWk9vUGI3MUE&resourcekey=0-8Rh67cZeGRXoNkd3LxYxwg" width="240" alt="1975 - M495 - Stereo Monitor Module.pdf"></a><br><sub>1975|8 · Stereo Monitor Module</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1LS5Pu1uPfYrlYCCATocygCJuvLmW6plE/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1LS5Pu1uPfYrlYCCATocygCJuvLmW6plE" width="240" alt="1992 - M495 - DOC - 2021-3-16-22-36-12.jpg"></a><br><sub>1992|25 · DOC - 2021-3-16-22-36-12</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVFBmX2RsU3ZpMmM/view?resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVFBmX2RsU3ZpMmM&resourcekey=0-HxddTfJi3Ix3Fjzk54EIdQ" width="240" alt="19xx - M495 - DOC - R1400-R2400 - 007.jpg"></a><br><sub>19xx - M495 - DOC - R1400-R2400 - 007</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMmxvZGRGcWFZV0E/view?resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMmxvZGRGcWFZV0E&resourcekey=0-RFjMOyC4g8PP7m1AatUkNg" width="240" alt="19xx - M495 - DOC - R1400-R2400 - 012.jpg"></a><br><sub>19xx - M495 - DOC - R1400-R2400 - 012</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSmRCMHJZdHFONlE/view?resourcekey=0-z4xRxlDDk3Kw1hbJYqH60w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSmRCMHJZdHFONlE&resourcekey=0-z4xRxlDDk3Kw1hbJYqH60w" width="240" alt="19xx - M495 - DOC - R1400-R2400 - 013.jpg"></a><br><sub>19xx - M495 - DOC - R1400-R2400 - 013</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSl92a2Vxa2NMc2s/view?resourcekey=0-2dfokMOlctdKaW5lsZMp_g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSl92a2Vxa2NMc2s&resourcekey=0-2dfokMOlctdKaW5lsZMp_g" width="240" alt="19xx - M495 - DOC - R1400-R2400 - 014.jpg"></a><br><sub>19xx - M495 - DOC - R1400-R2400 - 014</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1RfSw2kLEkjmzn61B4MBmvmmEhPNKtRw2" width="240" alt="19xx - M495 - DOC - WILMA - Aux and main summing.jpg"></a><br><sub>19xx - M495 - DOC - WILMA - Aux and main summing</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/195lEahX2BRue_z8U5Hva6TGEM8oOl0-i/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=195lEahX2BRue_z8U5Hva6TGEM8oOl0-i" width="240" alt="2015 - M495 - DOC - PSCILLATOE MQDULE UNE SELECTOR INPUTS.jpg"></a><br><sub>2015|48 · DOC - PSCILLATOE MQDULE UNE SELECTOR INPUTS</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [1990|23 · DOC - CHIN Radio R14000001](https://drive.google.com/file/d/0B0yR0b5T78SKYld2RThnMU1tLW8/view?resourcekey=0-ZPb2apzcpMkiRBWF0YEm7Q)

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1972 - M495 - DOC - 495-02-001 - STEREO MONITOR MODULE SCHEMATIC.kicad_sch](KICAD/1972%20-%20M495%20-%20DOC%20-%20495-02-001%20-%20STEREO%20MONITOR%20MODULE%20SCHEMATIC.kicad_sch)
- [1975 - 5-101-02-003 - 5-101B DUAL BOOSTER AMPLIFIER SCHEMATIC - DRN DM - ISS 2.kicad_sch](KICAD/1975%20-%205-101-02-003%20-%205-101B%20DUAL%20BOOSTER%20AMPLIFIER%20SCHEMATIC%20-%20DRN%20DM%20-%20ISS%202.kicad_sch)
- [1975 - M495 - 101-02-003 - ALL ICS LMGOI AND ALL DIODES.kicad_sch](KICAD/1975%20-%20M495%20-%20101-02-003%20-%20ALL%20ICS%20LMGOI%20AND%20ALL%20DIODES.kicad_sch)
- [1975 - M495 - 101-02-003 - XTERNAL CONNECTIDN.kicad_sch](KICAD/1975%20-%20M495%20-%20101-02-003%20-%20XTERNAL%20CONNECTIDN.kicad_sch)
- [1975 - M495 - 101-02-003.kicad_sch](KICAD/1975%20-%20M495%20-%20101-02-003.kicad_sch)
- [1975 - M495 - 495-01-001 - ENG CKDRAL STEREO MONITOR MODULE.kicad_sch](KICAD/1975%20-%20M495%20-%20495-01-001%20-%20ENG%20CKDRAL%20STEREO%20MONITOR%20MODULE.kicad_sch)
- [1975 - M495 - 495-01-001 - PRE MONITOR.kicad_sch](KICAD/1975%20-%20M495%20-%20495-01-001%20-%20PRE%20MONITOR.kicad_sch)
- [1975 - M495 - 495-02-001 - IBV LMZOL' RIS.kicad_sch](KICAD/1975%20-%20M495%20-%20495-02-001%20-%20IBV%20LMZOL%27%20RIS.kicad_sch)
- [1975 - M495 - 495-02-001 - STEREO MONITOR MODULE.kicad_sch](KICAD/1975%20-%20M495%20-%20495-02-001%20-%20STEREO%20MONITOR%20MODULE.kicad_sch)
- [1975 - M495 - 5_101-02-003 - DUAL BOOSTER AMPLIFIER.kicad_sch](KICAD/1975%20-%20M495%20-%205_101-02-003%20-%20DUAL%20BOOSTER%20AMPLIFIER.kicad_sch)
- [1975 - M495 - Stereo Monitor Module (2) p19.kicad_sch](KICAD/1975%20-%20M495%20-%20Stereo%20Monitor%20Module%20(2)%20p19.kicad_sch)
- [1975 - M495 - Stereo Monitor Module (2) p30.kicad_sch](KICAD/1975%20-%20M495%20-%20Stereo%20Monitor%20Module%20(2)%20p30.kicad_sch)
- [1975 - M495 - Stereo Monitor Module p19.kicad_sch](KICAD/1975%20-%20M495%20-%20Stereo%20Monitor%20Module%20p19.kicad_sch)
- [1975 - M495 - Stereo Monitor Module p30.kicad_sch](KICAD/1975%20-%20M495%20-%20Stereo%20Monitor%20Module%20p30.kicad_sch)
- [1978 - 495-01-001 - STEREO MONITOR MODULE FUNCTIONAL DIAGRAM - DRN MRW - ISS 1.kicad_sch](KICAD/1978%20-%20495-01-001%20-%20STEREO%20MONITOR%20MODULE%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20MRW%20-%20ISS%201.kicad_sch)
- [1980 - 495-02-001 - STEREO MONITOR MODULE SCHEMATIC - DRN MRW - ENG MRW - ISS 3.kicad_sch](KICAD/1980%20-%20495-02-001%20-%20STEREO%20MONITOR%20MODULE%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%203.kicad_sch)
- [1992 - M495 - DOC - 920063-01-002 - PQWER DISIEIBUTIQN PSI.kicad_sch](KICAD/1992%20-%20M495%20-%20DOC%20-%20920063-01-002%20-%20PQWER%20DISIEIBUTIQN%20PSI.kicad_sch)
- [19xx - M495 - DOC - 600-02-004 - NOVOV MONITOR CHANNELS ARE WIRED IDENTICALLY EXTERNAL INPUTS.kicad_sch](KICAD/19xx%20-%20M495%20-%20DOC%20-%20600-02-004%20-%20NOVOV%20MONITOR%20CHANNELS%20ARE%20WIRED%20IDENTICALLY%20EXTERNAL%20INPUTS.kicad_sch)
- [2006 - M495 - DOC - 920063-01-001 - MONIORMQDULE SWTCHED DIRECT SSUE REMSION.kicad_sch](KICAD/2006%20-%20M495%20-%20DOC%20-%20920063-01-001%20-%20MONIORMQDULE%20SWTCHED%20DIRECT%20SSUE%20REMSION.kicad_sch)
- [2017 - M495 - DOC - 920170-01-001 - SWTCHED DIRECT MONITOR OUTPUTS DDZME.kicad_sch](KICAD/2017%20-%20M495%20-%20DOC%20-%20920170-01-001%20-%20SWTCHED%20DIRECT%20MONITOR%20OUTPUTS%20DDZME.kicad_sch)
- [M495.kicad_sym](KICAD/M495.kicad_sym)
- [index.html](KICAD/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)

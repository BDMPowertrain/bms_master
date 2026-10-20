<p align="center" width="100%">
  <img alt="Logo" width="33%" src="Logos/bdm_logo.png">
</p>

<h1 align="center">BMS_MASTER</h1>
<p align="center">BMS Master</p>
<p align="center"><em>The BMS master board is the bridge between the TIM and the 16 BMS slave boards. It passes data both ways over a looped daisy chain, isolated by transformers so the battery’s high voltage never reaches the low-voltage side, and it signals the TIM the moment any slave reports a fault.</em></p>

<p align="center" width="100%">
  <a href="https://github.com/BDMPowertrain/bms_master/actions/workflows/ci.yaml">
    <img alt="CI Badge" src="https://github.com/BDMPowertrain/bms_master/actions/workflows/ci.yaml/badge.svg?branch=dev">
  </a>
</p>

<p align="center" width="100%">
    <img src="Logos/SAE_Electric_Logo.png" width="40%">
</p>

***

<p align="center">
  <img alt="3D Top" src="Images/bms_master-top.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="3D Bottom" src="Images/bms_master-bottom.png" width="45%">
</p>

***

## SPECIFICATIONS

| Parameter | Value |
| --- | --- |
| Dimensions | 0.0 × 0.0 mm |
| Company | Blue Devil Motor Sports |
| Designer | Aidan Brzezinski |
| Revision | + (Unreleased) |

***

## WORKING ON THIS BOARD

> This file is regenerated automatically on every CI run — don't edit it by
> hand. For the full contributor guide (setup, daily commands, commit
> conventions, PR etiquette, and what to do when something goes wrong), see
> the [board_template README](https://github.com/BDMPowertrain/board_template#readme).

**Change the stage or board info** (title, description, designer, company,
revision) — open the config menu and pick an option:

    py configure.py       # Windows (or double-click configure.py)
    ./configure.py        # Linux/macOS

Stages go DRAFT → PRELIMINARY → CHECKED as the board moves through Design →
Procurement → Fabrication. `configure.py --check` validates the config
before you push.

RELEASED is never set by hand — push a version tag and CI produces it
automatically:

    git tag 1.0.0
    git push origin 1.0.0

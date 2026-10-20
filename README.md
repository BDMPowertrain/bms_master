<p align="center" width="100%">
  <img alt="Logo" width="33%" src="Logos/bdm_logo.png">
</p>

<h1 align="center">BOARD_NAME</h1>
<p align="center">Board Name</p>
<p align="center"><em>One-line description of what this board does.</em></p>

<p align="center" width="100%">
  <a href="https://github.com/BDMPowertrain/PLACEHOLDER/actions/workflows/ci.yaml">
    <img alt="CI Badge" src="https://github.com/BDMPowertrain/PLACEHOLDER/actions/workflows/ci.yaml/badge.svg?branch=main">
  </a>
</p>

<p align="center" width="100%">
    <img src="Logos/SAE_Electric_Logo.png" width="40%">
</p>

***

<p align="center">
  <img alt="3D Top" src="Images/BOARD_TEMPLATE-top.png" width="45%">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="3D Bottom" src="Images/BOARD_TEMPLATE-bottom.png" width="45%">
</p>

***

## SPECIFICATIONS

| Parameter | Value |
| --- | --- |
| Dimensions | 0.0 × 0.0 mm |
| Company | Blue Devil Motor Sports |
| Designer | Author |
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

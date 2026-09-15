<div align="center">

<img src="https://neerova.ai/neerova-logo.png" alt="Neerova.ai" width="340">

### Flood intelligence for Indian cities

We build the layer that connects sensing, prediction and response —
fast enough to matter.

[![Website](https://img.shields.io/badge/neerova.ai-0F2233?style=flat-square)](https://neerova.ai)
[![Email](https://img.shields.io/badge/hello%40neerova.ai-17A398?style=flat-square)](mailto:hello@neerova.ai)

</div>

---

## The problem we work on

Urban flooding in India is rarely a surprise. The rain is forecast days ahead, the
drainage network is mapped, and the hotspots repeat in the same streets year after
year. What is usually missing is the connective tissue: the system that turns a
rainfall forecast into a pump that starts on time, a gate that opens early, and a
warning that reaches a resident in their own language while there is still time to
move.

That gap is measured in minutes, and minutes are where the damage happens. Manual
response to a rising sump typically takes around fifteen minutes from observation to
action. Automated threshold response takes under one.

Neerova.ai exists to close that gap.

## What we build

We design and deliver end-to-end urban flood early warning and decision support
systems for municipal corporations, disaster management authorities and water
resource departments. A complete deployment spans four layers.

**Sensing.** IoT networks across drainage hotspots, ghats, bridge piers, outfalls and
pump stations. Radar and ultrasonic water level recorders, tipping-bucket rain gauges
calibrated to IMD standard, automatic weather stations, electromagnetic flow meters,
pump health sensors, and slope stability instrumentation where terrain demands it.
Built for the monsoon, which means IP67 and IP68 enclosures, anti-tamper design, UPS
and solar backup, and multi-layer communication redundancy so the data keeps arriving
when cellular networks congest at exactly the moment they are needed most.

**Prediction.** Hydrological and hydraulic modelling turned into something operable.
Pre-run scenario libraries give instantaneous flood depth lookups instead of
model runs nobody has time for. IMD quantitative precipitation forecasts, upstream
dam-release telemetry and live sensor feeds combine into depth forecasts with honest
confidence intervals, because a decision-maker needs to know how much to trust a
number before acting on it.

**Control.** Bi-directional SCADA integration for remote pump start and stop, VFD
speed control, and automated command execution at defined thresholds. Pump sequencing
optimised against forecast and sump level, which lowers energy cost as a side effect
of running the system well.

**Response.** Multilingual alerting across SMS, WhatsApp, app push and public address,
CAP-compliant and routed by escalation tier so the right person is woken at the right
threshold. Hazard and risk atlases layered over census vulnerability and critical
infrastructure. Dynamic evacuation routing driven by live inundation extent.
Auto-generated compliance reporting for state and national authorities.

## FloodCtrl

FloodCtrl is our decision support platform, the unified operational layer that
integrates everything above into one dashboard.

| Module | Function |
| --- | --- |
| Real-time monitoring | Live telemetry across all hotspots on a municipal GIS base map, colour-coded by status |
| Forecasting engine | QPF and dam-release ingestion, H&H scenario lookup, depth prediction with confidence intervals |
| SCADA interface | Remote and automated pump control, sequencing optimisation, threshold-triggered execution |
| Hazard & risk atlas | Return-period flood maps, vulnerability overlays, dynamic evacuation routing |
| Community alerting | Multilingual multi-channel warnings, CAP-compliant, with crowd-sourced validation |
| O&M & compliance | Automated operational reporting, asset maintenance logs, one-click regulatory exports |

Mobile-first by design, because during an active event the people authorising
decisions are rarely at a desk.

## How we think about this work

**Lead time is the product.** Every architectural decision is judged against one
question: does this get a useful warning to the right person earlier?

**Field reality beats model elegance.** Sensors get vandalised, grids fail, networks
congest, and operators work eighteen-hour shifts during a monsoon. A system that
assumes ideal conditions is a system that fails on the day it is needed.

**Confidence intervals, not false precision.** A forecast presented without its
uncertainty invites either over-reaction or misplaced trust. Both cost lives.

**Built to be handed over.** These systems outlast contracts. Documentation,
maintainability and operator training are deliverables, not afterthoughts.

## This organisation

Most repositories here are private client infrastructure. What we publish openly is
tooling, integrations and reference material we think is useful to the wider water
and disaster management community.

- **Partnerships, pilots and enquiries:** [hello@neerova.ai](mailto:hello@neerova.ai)
- **Technical and integration questions:** [developer@neerova.ai](mailto:developer@neerova.ai)

We work with municipal corporations, state disaster management authorities, system
integrators and instrumentation partners. If you are working on flood resilience
anywhere in India, we would like to hear from you.

<div align="center">
<br>
<strong>Predict. Prepare. Protect.</strong>
<br><br>
<sub>Neerova.ai · Flood Intelligence</sub>
</div>

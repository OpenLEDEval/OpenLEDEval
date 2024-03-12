# Objectives

- Finish up delinquent projects
    - Tucker & Ritchie
        - Publish
            - [x]  Summary document/snapshot of all code/findings/credits/…
                - [x]  Credits: supporting vendors & individual contributors
            - [ ]  Push to ET Centric
        - 4 individuals/entities have now replicated our methodology
    - Tim K
        - Publish
            - [ ]  Add credits (names & companies)
            - [ ]  January 23, 2024

# Admin

- Can we find a project manager to keep us on track
    - [ ]  Github AI
- Target date(s) for
    - Tests (January 24, 2024 - January 26, 2024)
    - Publications
- Outline evaluation plan for each objective
- Smaller publications per finding/evaluation to get them out with less latency
    - Vendor PR
    - 
- Set up ETC equipment library
    - Request loaner gear for up to a year from supporting/sponsoring vendors
    - 1-2 panels/processors of each flavor
    - Possibly store at Fuse TG
    - For internal ETC use only?
    - For rental houses / intermediate groups / productions / studios
- Document support system
    - Paid access for core contributors only, not read-only access for general ETC consumers
    - Sponsorship for contributor tools?
    - Clickup (free tier?)
        - Evaluated at ASC MITC, seemed to suit purposes
    - Notion (free version has 1000 block limit)
    - Dropbox Paper
        - Evaluated at ACES
    - Media storage for footage etc.
    - Github ✅ / ~~Gitlab~~
        - [x]  Ritchie to make repo
        - [ ]  Tucker @tjdcs
        - [ ]  Payton @pschleh
        - [ ]  Jason @jtmetcalfe
        - [ ]  Erik @etcenter
        - [ ]  Marcus ?
- Meeting cadence
    - 2 week working group cadence
    - Move updates to quarterly
- Alignment with other groups (e.g., ASC, SMPTE, ESTA)
    - ETC provides topics & eval methodologies
    - ASC provides ‘recommended ranges’ for VP
    - ASC StEM3 VP
    - SMPTE provides ‘recommended ranges’ for broadcast/XR
    - …

# Topics/Tasks

- Comparison between MVR & Brompton & (insert your favorite Colorlight/Novastar/Linsn)
    - [ ]  Latency
    - [ ]  Color reproduction
    - [ ]  Shutter angle compatibility
    - [ ]  Multi-cam
        - [ ]  Overlapping frustums
        - [ ]  Things relevant
    - Product options
        - ROE will have a product with same drivers, module layout, etc on MVR/Brompton/Colorlight/Novastar
            - Two tiles of each
            - Based on BP2 - 2.6/2.8
            - Meant only for technical evals
            - Available roughly May timeframe
            - Colorlight (& friends) tend to have more variance in attention to detail on electronics design
        - LDM PCB layout can have impact on performance, and may change with processor choice
        - Sony Verona
- Improved/additional off-axis measurements
    - How far off axis can we go and still maintain DCI-P3?
        - Gamut will remain unchanged with viewing angle, but native WB and calibration will be off. Larger ∆E at angle
    - How far off axis can we go and still maintain 90% of luminance?
    - Threshold for 5∆E Off Axis
- Reflectance
    - What is actual impact on dynamic range of e.g., 3.5% to 2.5% improvement
        - Can be calculated, but best demonstrated with a footage test
    - Understand impact of real-world spill light, and when it overcomes content
- Evaluate shadow detail reproduction capability
    - Quantization / banding in shadow ranges
    - Color shift due to driver non-linearity
    - Linearity correction
        - PureTone & OptiTune
    - Effect of white point on low-end performance
    - Refresh rate impact
        - Scan methodologies
    - DCI/ISDCF recommendation/guideline for measuring *minimum active black*
        - Driver ability to overcome impedance/capacitance in lowest step out of black
        - What is the magnitude of the first step compared to the magnitude difference from step 1 to 2
- Product reliability
    - Establish better language around reliability
    - MTBF, MTBR
    - Repairability
    - Reliability failover time - how long does automated diagnosis & recovery take
    - X 9s uptime
    - Aging (calibration)
    - Product lifetime - address buyer’s remorse issues
        - Range of performance to be in, not just at the pinnacle
- Improved color response measurements from 2023 report
    - Display spectral measurements (RGB+++)
    - What is the “right approach” to the +es
    - What spectrums are the various products providing
    - Footage to correlate to metrics
    - Rewrite TPG outside of UE
        - [https://store.portrait.com/consumer-software/patterns.html](https://store.portrait.com/consumer-software/patterns.html)
        - [https://www.murideo.com/mu-six-g-8k.html](https://www.murideo.com/mu-six-g-8k.html)
- RGB+++ video & lighting integration (spectral match sufficiency)
    - What’s a useful minimum SSI to be looking at
    - TM-30
    - Tim K to write an explainer for the above
    - address by MITC
- Lighting/IBL frame rate / synchronization ability/analysis
- camera spectral response measurement
- ST2110
- post-calibration color accuracy LUTs
- PTP/timing
    - Eval difficulty of building a PTP setup
    - Lead-time issues getting server equipment to evaluate (DPUs)
    - Camera/display/lighting compatibility
    - Netgear switches are improved over Mellanox & Arista
    - Michael Kohler
- Curving smoothness
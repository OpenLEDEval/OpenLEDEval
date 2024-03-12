This stub file records some notes on color precision testing. It is currently championed by #tjdcs

### To Improve from 2023
- Display spectral measurements (RGB+++) ^79a981
- What is the “right approach” to the +es
- What spectrums are the various products providing
- Footage to correlate to metrics
- Rewrite TPG outside of UE
	- [https://store.portrait.com/consumer-software/patterns.html](https://store.portrait.com/consumer-software/patterns.html)
	- [https://www.murideo.com/mu-six-g-8k.html](https://www.murideo.com/mu-six-g-8k.html)

# Spectral Sufficiency
- What’s a useful minimum SSI to be looking at
- TM-30
- Tim K to write an explainer for the above 😉
- address by MITC
# Low Luminance Detail Quality
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

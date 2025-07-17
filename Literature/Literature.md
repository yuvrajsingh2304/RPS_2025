## Literature and Patent Search Summary

### **Literature Review on PEC Testing for Corrosion Monitoring in RC Structures**

The reviewed literature covers significant advancements in the development and application of Eddy Current Testing (ECT) and Pulsed Eddy Current (PEC) techniques for detecting and quantifying corrosion in steel rebars embedded in concrete—crucial for ensuring the longevity and safety of reinforced concrete (RC) infrastructure.

**[Auld and Moulder (1999)](1.pdf)** provided a foundational theoretical framework for quantitative ECT, introducing forward and inverse problem modeling and exploring how defects like corrosion alter probe impedance. Their discussion of skin effect, reciprocity, and probe field interactions remains critical for advanced PEC and ECT modeling.

**[Alcantara et al. (2015)](2.pdf)** investigated the eddy current response for different rebar corrosion stages and emphasized the influence of coil geometry and frequency on detection depth and signal quality. Their work provides experimental benchmarks for designing modular PEC systems.

**[Huang and Wang (2016)](3.pdf)** emphasized the distinct advantages of PEC over single-frequency ECT, highlighting the use of pulse excitation with rich frequency content to analyze defects at multiple depths. Their chapter outlined probe design principles, noise suppression strategies, and the use of ferrite cores to enhance sensitivity and minimize lift-off noise.

**[Eddy et al.(2019)](4.pdf)** demonstrated that PEC decay signal characteristics could be used to estimate rebar cross-sectional loss due to corrosion, even through deep concrete covers (up to 110 mm). The study introduced the concept of using long-time signal decay independent of lift-off to assess corrosion depth.

**[Mukherjee et al. (2020)](5.pdf)** proposed a low-cost, portable platform using phase-sensitive detection and Anisotropic Magnetoresistive (AMR) sensors for early-stage corrosion detection. Their approach is particularly suited to incipient corrosion monitoring and surface-level degradation diagnostics.

**[Ha et al. (2021)](6.pdf)** designed a wireless PEC corrosion detection system for steel structures, integrating Arduino, Zigbee, and Raspberry Pi. Their innovation in using an RLC delay circuit enabled low-power wireless monitoring and proved the viability of integrating PEC into wireless sensor networks (WSNs) for SHM.

**[Thibbotuwa et al. (2024)](7.pdf)** introduced resonant EC sensors for corrosion detection through thick concrete covers (up to 5–6 cm). By tracking the parallel resistance (Rp) variation, they effectively quantified corrosion-induced material loss and addressed environmental compensation using temperature sensitivity analysis.

**[He, D. (2024)](8.pdf)** developed a portable eddy current system for corrosion assessment of rebars using a lock-in amplifier to analyze in-phase and quadrature signals. By examining the X-Y plot slope of the induced signal, different corrosion products were distinguished based on their conductivity and magnetic permeability. The study optimized excitation frequency (~80 kHz), coil types (toroidal vs. differential), and introduced a Helmholtz configuration to reduce noise and improve detection depth. It confirmed that eddy current phase response could accurately reflect corrosion progression.

---

**Key Findings Across Literature**:

* PEC enables **quantitative corrosion monitoring** and not just detection.
* **Sensor design** (coil tuning, geometry) and **calibration** are crucial for accurate results.
* **Environmental factors** (humidity, temperature, resistivity) influence EC readings and must be compensated for.
* **Low-cost, open-source platforms** (e.g., Arduino-based setups) are increasingly viable.
* There is **limited indigenous development** in India, indicating a large research and market opportunity.

  ---

### **Patent Landscape for Pulsed Eddy Current (PEC) Applications in RC Corrosion Assessment**

#### **Patent Note**:
Commercial PEC-based systems (e.g., by Eddyfi, Olympus) are patented, especially for metallic pipelines and tanks. However, **adaptations for embedded rebars in RC structures remain underdeveloped** in the public domain, with **open-source, lab-buildable platforms still emerging**—offering potential for patentable innovations in sensor design, software algorithms, or integrated toolkits.

#### Patent Search Summary: Pulsed Eddy Current (PEC) for Corrosion Monitoring

| Sr. No. | Patent Title & Number | Patent Holder(s) & Year | Purpose / Scope | Relevance to Project | Related Papers / Articles |
|--------|------------------------|--------------------------|------------------|----------------------|---------------------------|
| 1 | **US20080252239A1** – *Eddy current inspection probe...* | Olympus NDT Inc., USA (2008) | Non-contact PEC probe for through-coating inspection | Wideband decay-based probe design inspiration | Eddy et al. (2019); PEC Thermography study |
| 2 | **US8299784B2** – *Systems and methods for detecting CUI...* | General Electric, USA (2012) | PEC for insulation-covered corrosion detection | Analogous to rebars inside concrete | NACE Conf. Proc.; TUV Rheinland guide |
| 3 | **WO2015128485A1** – *System for detecting corrosion using PEC* | Univ. of Waterloo, Canada (2015) | Low-frequency broadband PEC signal design | Hardware logic support | Eddy et al. (2019) |
| 4 | **EP2722075B1** – *Wireless PEC inspection system* | The Welding Institute, UK (2014) | Wireless PEC inspection | Supports app integration and portability | Eddyfi tech paper; NDT.net articles |
| 5 | **IN201641007921A** – *Phase-sensitive EC with signal algorithm* | IIT Madras, India (2016) | Advanced signal processing using AMR sensors | Relevant to low-cost Indian development | Mukherjee et al. (2020); Tamhane et al. |

###  Key Observations:

* **North America leads in PEC patent filings**, especially for aerospace and oil/gas sectors.
* There is **a notable gap in civil infrastructure PEC tools**, particularly for rebars embedded in concrete.
* The existing patents **do not cover open-source or modular PEC toolkits**, leaving room for innovation.
* The proposed system—**modular PEC + mobile app + image processing**—would be **novel in India and globally** for structural audits.

---

## **References**

1. [Auld, B. A., & Moulder, J. C. (1999). *Review of advances in quantitative eddy current nondestructive evaluation*. Journal of Nondestructive Evaluation, 18(1), 3–36.](1.pdf)

2. [Alcantara, N. P., Silva, F. M., Guimarães, M. T., & Pereira, M. D. (2016). *Corrosion assessment of steel bars used in reinforced concrete structures by means of eddy current testing*. Sensors, 15(16), 1-18. https://doi.org/10.3390/s16010015](2.pdf) 

3. [Huang, S., & Wang, S. (2016). *The pulsed eddy current testing*. In S. Huang & S. Wang (Eds.), New technologies in electromagnetic non-destructive testing (pp. 41–80). Springer. https://doi.org/10.1007/978-981-10-0578-7_2](3.pdf)

4. [Eddy, I., Underhill, P. R., Krause, T. W., & Morelli, J. (2019). *Pulsed eddy current response to general corrosion in concrete rebar*. In Proceedings of the 46th Annual Review of Progress in Quantitative Nondestructive Evaluation (QNDE2019-7001).](4.pdf)

5. [Mukherjee, I., Patil, J., Banerjee, S., & Tallur, S. (2020). *Phase sensitive detection of extent of corrosion in steel reinforcing bars using eddy currents*. Unpublished manuscript.](5.pdf)

6. [Ha, N., Lee, H.-S., & Lee, S. (2021). *Development of a wireless corrosion detection system for steel-framed structures using pulsed eddy currents*. Sensors, 21(24), Article 8199. https://doi.org/10.3390/s21248199](6.pdf)

7. [Thibbotuwa, U. C., Cortés, A., Casado, A. M., & Irizar, A. (2024). *Resonant eddy current sensor design for corrosion detection of reinforcing steel*. Sensors, 24(13), Article 4211. https://doi.org/10.3390/s24134211](7.pdf)

8. [He, D. (2024). *Detecting the corrosion of a steel rebar using the eddy current testing method*. Standards, 4(4), 286–299. https://doi.org/10.3390/standards4040014](8.pdf)

---

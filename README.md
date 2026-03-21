# Field Coherence Stress Diagnosis (FCSD)

**A Structural Evaluation Framework for Socio-Affective Drift in Large Language Models**

Ottavio Braun  
SYNTX System, Berlin, Germany  
[mirror@syntx-system.com](mailto:mirror@syntx-system.com)

---

## Abstract

Large language models (LLMs) are typically evaluated using benchmarks that measure reasoning accuracy and factual reliability. These benchmarks do not explicitly assess structural fidelity under emotionally compressed or relationally asymmetric input.

This paper introduces **Field Coherence Stress Diagnosis (FCSD)**, a controlled evaluation framework designed to quantify socio-affective drift—systematic structural transformation of emotionally dense input via smoothing, symmetry insertion, reframing, or tension defusion.

**Key Findings:**
- Baseline input drift: 90-93% (GPT-5.2/5.3)
- Output drift: 70-97% depending on version and stress level
- Policy activations: +68% increase from GPT-5.2 → GPT-5.3
- Cross-model variance: 0-43 policies across 4 architectures
- SYNTX intervention: 0% drift under controlled conditions

---

## Repository Structure
```
fcsd-paper/
├── paper/
│   ├── FCSD_arXiv_Paper.pdf          # Main paper
│   ├── main.tex                       # LaTeX source
│   ├── references.bib                 # Bibliography
│   └── figures/                       # All figures
├── supplementary/
│   ├── GPT52_StressTest.pdf          # GPT-5.2 detailed results
│   ├── GPT53_StressTest.pdf          # GPT-5.3 detailed results
│   └── CrossModel_Validation.pdf     # Cross-model analysis
└── README.md
```

---

## Files

- **📄 Main Paper:** [`paper/FCSD_arXiv_Paper.pdf`](paper/FCSD_arXiv_Paper.pdf)
- **📝 LaTeX Source:** [`paper/main.tex`](paper/main.tex)
- **📚 Supplementary Materials:** [`supplementary/`](supplementary/)

---

## Key Contributions

1. **New evaluation class:** FCSD as complementary framework for structural fidelity under emotional stress
2. **Empirical analysis:** 50 controlled runs quantifying baseline drift rates (70-97%)
3. **Longitudinal comparison:** Version analysis showing increased governance density in GPT-5.3
4. **Cross-model validation:** Architecture-specific variance across 4 models

---

## Citation
```bibtex
@article{braun2026fcsd,
  title={Field Coherence Stress Diagnosis (FCSD): A Structural Evaluation Framework for Socio-Affective Drift in Large Language Models},
  author={Braun, Ottavio},
  journal={GitHub Repository},
  year={2026},
  url={https://github.com/SYNTX-SYSTEM/fcsd-paper}
}
```

---

## License

This work is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Ethical Considerations

While FCSD demonstrates that structural mirroring can eliminate observable drift, the implementation details of the SYNTX-2.0 protocol are withheld from publication. Unrestricted access to structural mirroring techniques could enable misuse in contexts requiring safety constraints. Access to SYNTX implementation details is restricted to vetted research collaborations.

---

## Contact

For questions or collaboration inquiries:  
**mirror@syntx-system.com**

[SYNTX System](https://syntx-system.com)


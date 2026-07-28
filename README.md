## Kirollos Hanna

**AI/ML Engineer** · MSc Artificial Intelligence (Distinction), University of Essex

I work on computer vision and model evaluation — mostly on problems where the dataset is small, the published methods don't quite fit, and someone needs a number at the end they can actually trust.

---

### Selected work

#### Out-of-distribution detection for few-shot classification
*MSc thesis, in collaboration with BT Group · Jan–Sept 2024*

The brief was a dataset-agnostic image classifier trained on 5–10 images per class that could also recognise inputs belonging to no known class at all. I benchmarked the published OOD detection methods against that brief, found none of them adequate in the few-shot setting, and designed my own.

- **87.3%** accuracy on Intel Image Classification at 10 samples/class, **89.3%** after self-training and ensembling
- **100%** OOD recall on selected Fashion-MNIST and Intel tests, **≥95%** precision overall
- K-Means re-engineered with cosine similarity to cluster rejected images into candidate new classes — 87% clustering accuracy on Intel, 73% on Caltech-101, cutting the manual review burden on human experts
- Validated across Intel, CIFAR-10, Fashion-MNIST and Caltech-101 to show generality rather than dataset-specific tuning

#### Structural steel measurement from images
*Efestos · May–Jul 2026*

Sole engineer on a pipeline measuring the cross-sectional dimensions of steel beams from ordinary RGB photographs — no depth sensor. Segmentation to isolate the components and locate the measurement points, then a geometric approach to recover real-world scale and convert pixels into millimetres. No existing codebase — I owned requirements interpretation, approach selection, architecture, implementation, and validation.

I designed the validation procedure myself and measured **~2 mm average error** against reference measurements.

#### LLM evaluation
*Ongoing since 2024*

Nearly two years evaluating frontier model outputs against structured rubrics — reasoning quality, factual accuracy, instruction following, formatting, safety — and producing ranked preference judgements with written justification. Alongside that, designing adversarial prompts to surface hallucinations, reasoning failures, inconsistent self-correction, and weak guardrail behaviour.

Mostly on technical prompts in ML, computer vision, Python and data analysis, where correctness can be verified directly rather than judged on plausibility.

#### Multi-tenant reservations platform
*In development*

Django and Django REST Framework backend, React web client, Flutter mobile app over a shared API. Five distinct user roles with separate permission models, and a relational schema handling concurrent bookings and real-time availability.

---

### A note on what's public here

The four projects above are the work I'd want you to look at, and none of them can be published. The thesis and the Efestos pipeline are client-owned. The reservations platform is a commercial product I intend to launch. What remains in the repository list below is mostly older university coursework, and it isn't representative.

I'm happy to walk through any of it in detail — architecture, methodology, results, and the parts that didn't work.

---

### Tools

- **Languages** — Python · SQL · JavaScript · Dart
- **ML/AI** — PyTorch · TensorFlow · Scikit-learn · OpenCV · Pandas · NumPy
- **Software** — Django · Django REST Framework · React · Flutter
- **Other** — Git · Linux · Docker

---

Open to AI/ML engineering roles and immediately available.

[kirollos7023@gmail.com](mailto:kirollos7023@gmail.com) · [LinkedIn](https://linkedin.com/in/hanna-kirollos)

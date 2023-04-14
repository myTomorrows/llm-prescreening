> **Warning** Work in progress

# LLM-assisted pre-screening for clinical trials

Official repository for the paper [Improving Patient Pre-screening for Clinical Trials: Assisting Physicians with Large Language Models](https://www.mytomorrows.com)

## Abstract

> **Background** Physicians considering clinical trials for their patients are met with the laborious process of checking many text based eligibility criteria. Large Language Models (LLMs) have shown to perform well for clinical information extraction and clinical reasoning, including medical tests, but not yet in real-world scenarios. This paper investigates the use of InstructGPT to assist physicians in determining eligibility for clinical trials based on a patient’s summarised medical profile.
**Methods** Using a prompting strategy combining one-shot, selection-inference and chain-of-thought techniques, we investigate the performance of LLMs on 10 synthetically created patient profiles. Performance is evaluated at four levels: ability to identify screenable eligibility criteria from a trial given a medical profile; ability to classify for each individual criterion whether the patient qualifies; the overall classification whether a patient is eligible for a clinical trial and the percentage of criteria to be screened by physician.
**Findings** We evaluated against 146 clinical trials and a total of 4,135 eligibility criteria. The LLM was able to correctly identify the screenability of 72% (2,994/4,135) of the criteria. Additionally, 72% (341/471) of the screenable criteria were evaluated correctly. The resulting trial level classification as eligible or ineligible resulted in a recall of 0.5. By leveraging LLMs with a physician-in-the-loop, a recall of 1.0 and precision of 0.71 on clinical trial level can be achieved while reducing the amount of criteria to be checked by an estimated 90%.
**Interpretation** LLMs can be used to assist physicians with pre-screening of patients for clinical trials. By forcing instruction-tuned LLMs to produce chain-of-thought responses, the reasoning can be made transparent to and the decision process becomes amenable by physicians, thereby making such a system feasible for use in real-world scenarios.
**Funding** myTomorrows.

## Evaluation Samples

The synthetic patient profiles can be found [here](https://github.com/mytomorrows/llm-prescreening/tree/master/synthetic_profiles).

The medical professional evaluation files per profile can be found [here](https://github.com/mytomorrows/llm-prescreening/tree/master/evaluation_files).

The overall and per-patient performance metrics can be found [here](https://github.com/mytomorrows/llm-prescreening/tree/master/metrics).

## Citation

```
@misc{tbd,
  doi = {placeholder},
  url = {placeholder},
  author = {den Hamer, Danny and Schoor, Perry and Polak, Tobias and Kapitan, Daniel},
  keywords = {Computation and Language (cs.CL), Artificial Intelligence (cs.AI), Machine Learning (cs.LG), FOS: Computer and information sciences, FOS: Computer and information sciences, I.2.1; I.2.7},
  title = {Improving Patient Pre-screening for Clinical Trials: Assisting Physicians with Large Language Models},
  publisher = {arXiv},
  year = {2023},
  copyright = {placeholder}
}
```

# Mitigating Automated Obfuscation Attacks on Software Plagiarism Detection Systems

This repository contains the LaTeX source files for my [doctoral dissertation](https://doi.org/10.5445/IR/1000179018/v2).

## Citation

If you use or reference this dissertation, please cite it as:
```bibtex
@phdthesis{Saglam2025,
    author       = {Sa\u{g}lam, Timur},
    year         = {2025},
    title        = {Mitigating Automated Obfuscation Attacks on Software Plagiarism Detection Systems},
    doi          = {10.5445/IR/1000179018/v2},
    publisher    = {{Karlsruhe Institute of Technology (KIT)}},
    pagetotal    = {264},
    school       = {Karlsruhe Institute of Technology  (KIT)},
    language     = {english}
}
```

## Abstract

Plagiarism is a prevalent challenge in computer science education, especially in introductory programming courses. Educators rely on detection systems to tackle plagiarism at scale. However, state-of-the-art systems remain vulnerable to specific obfuscation techniques that alter the structure of a program while maintaining its behavior to evade detection. Automated obfuscation attacks exacerbate this problem, particularly with recent advancements in artificial intelligence that have made automated obfuscation more accessible. Furthermore, these detection systems do not apply to modeling assignments, highlighting the need for obfuscation-resilient plagiarism detection for both programming and modeling languages.

To address these challenges, in this dissertation, we enhance state-of-the-art software plagiarism detection systems with resilience against automated obfuscation attacks. To that end, we present three key contributions. First, we propose a comprehensive threat model for obfuscation attacks on software plagiarism detection systems, examining how such attacks disrupt detection by targeting the internal program representation of detection systems. Second, we outline an approach that enables token-based plagiarism detection for artifacts of modeling assignments, applying a well-established concept to modeling education. Third, we present three novel defense mechanisms against automated obfuscation attacks that can be integrated into state-of-the-art detection systems, including attack-specific mechanisms for targeted defense and attack-independent mechanisms for broad resilience.

An empirical evaluation demonstrates the effectiveness of these contributions across real-world datasets, including programming and modeling assignments, analyzing more than four million data points. Nine different obfuscation techniques, including algorithmic and AI-based obfuscation, are employed for this evaluation. The results show that the defense mechanisms significantly improve obfuscation resilience against all nine types of attacks compared to state-of-the-art methods and, in some cases, provide complete immunity.
These results demonstrate not only the feasibility and practicality of these contributions in addressing the growing challenges of automated obfuscation but also their capability to enable resilient software plagiarism detection for programming and modeling assignments. This dissertation equips educators with methods to address the emerging threats of automated obfuscation attacks. Integrating these contributions into a widely used detection system allows reliable software plagiarism detection in practice.


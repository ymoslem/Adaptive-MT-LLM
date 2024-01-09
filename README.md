# Adaptive-MT-LLM
Code for the paper "[Adaptive Machine Translation with Large Language Models](https://aclanthology.org/2023.eamt-1.22/)"

For fine-tuning LLMs for Adaptive MT, check this [repository]([url](https://github.com/ymoslem/Adaptive-MT-LLM-Fine-tuning)).

## Citation

```
@inproceedings{moslem-2023-adaptive,
  title={Adaptive Machine Translation with Large Language Models},
  author={Moslem, Yasmin and Haque, Rejwanul and D. Kelleher, John and Way, Andy},
  abstract="Consistency is a key requirement of high-quality translation. It is especially important to adhere to pre-approved terminology and adapt to corrected translations in domain-specific projects. Machine translation (MT) has achieved significant progress in the area of domain adaptation. However, real-time adaptation remains challenging. Large-scale language models (LLMs) have recently shown interesting capabilities of in-context learning, where they learn to replicate certain input-output text generation patterns, without further fine-tuning. By feeding an LLM at inference time with a prompt that consists of a list of translation pairs, it can then simulate the domain and style characteristics. This work aims to investigate how we can utilize in-context learning to improve real-time adaptive MT. Our extensive experiments show promising results at translation time. For example, LLMs can adapt to a set of in-domain sentence pairs and/or terminology while translating a new sentence. We observe that the translation quality with few-shot in-context learning can surpass that of strong encoder-decoder MT systems, especially for high-resource languages. Moreover, we investigate whether we can combine MT from strong encoder-decoder models with fuzzy matches, which can further improve translation quality, especially for less supported languages. We conduct our experiments across five diverse language pairs, namely English-to-Arabic (EN-AR), English-to-Chinese (EN-ZH), English-to-French (EN-FR), English-to-Kinyarwanda (EN-RW), and English-to-Spanish (EN-ES).",
  booktitle="Proceedings of the 24th Annual Conference of the European Association for Machine Translation, Research: technical",
  year="2023",
  publisher="European Association for Machine Translation",
  url="https://aclanthology.org/2023.eamt-1.22/"
}
```

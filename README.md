<h1 align="center"><b>Multi Modal-Cognitive Support Conversation (M2CoSC)</b></h1>

This is the official github repository for [Multimodal Cognitive Reframing Therapy via Multi-hop Psychotherapeutic Reasoning
](https://arxiv.org/abs/2502.06873) accepted at NAACL 2025 Main.


If this dataset helps you in your research, please cite the following publication:
```
@misc{kim2025multimodalcognitivereframingtherapy,
    title={Multimodal Cognitive Reframing Therapy via Multi-hop Psychotherapeutic Reasoning}, 
    author={Subin Kim and Hoonrae Kim and Heejin Do and Gary Geunbae Lee},
    year={2025},
    eprint={2502.06873},
    archivePrefix={arXiv},
    primaryClass={cs.CL},
    url={https://arxiv.org/abs/2502.06873}
}
```

## **Introduction**
The **M2CoSC** dataset is an initial study exploring how AI-driven psychotherapy can be enhanced by integrating text-based dialogues with visual cues. Traditional therapy models relying solely on text overlook crucial non-verbal emotional expressions. M2CoSC aims to bridge this gap by pairing therapy dialogues with facial expressions, enabling AI models to better interpret and respond to client emotions.

As a **first step** in this research direction, we created M2CoSC using GPT-4 as a virtual client and GPT-4 Vision as a therapist, following a four-stage therapy framework:

1. **Introduction**: Expressing empathy and encouraging problem exploration.
2. **Exploration**: Differentiating thoughts from situations.
3. **Brainstorming**: Considering alternative perspectives.
4. **Suggestion**: Providing constructive guidance.

Through **multi-hop psychotherapeutic reasoning**, M2CoSC helps AI models incorporate subtle emotional cues, leading to more empathetic and effective therapy interactions. Our experiments suggest that Vision-Language Models (VLMs) trained on M2CoSC have potential advantages over standard LLMs in delivering logical and emotionally aware interventions. We encourage further studies to expand on this work.


## **Dataset Access Instructions**
Due to AffectNet licensing restrictions, we provide only synthetic dialogues with image IDs. To access the full dataset, including images, researchers must obtain an AffectNet license and request access.

For dataset access, visit [here](https://huggingface.co/datasets/multimodal-reframing/M2CoSC).



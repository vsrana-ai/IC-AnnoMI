## IC-AnnoMI

```
This repository contains the source code and synthetic dataset generated through in-context zero-shot LLM prompting.

```
### Requirements
```
Python3
Keras
PyTorch
```

## IC-AnnoMI Dataset

IC-AnnoMI Dataset folder contains the following files:

* `Annotated_ID.csv`: This file contains the annotation of MI dialogues across each parameter psychological (MI_psych) and Linguistic (MI_lang) Dimensions.
* `IC-AnnoMI.csv`: This file contains the LLM-generated in-context MI dialogues corresponding to the AnnoMI train MI dialogues. 
* `IC-AnnoMI(test set).csv`: This file is a representative test set of IC-AnnoMI spanning over 16 topics and used as a test set for all the experiments. 

### Publication (Conference NLPAICS) 
#### Unlocking LLMs: Addressing Scarce Data and Inherent Bias Challenges in Mental Health and Therapeutic Counselling
URL: https://aclanthology.org/2024.nlpaics-1.26/ 
 
Cite as (BibTex): 
```bash
@inproceedings{kumar-etal-2024-unlocking,
    title = "Unlocking {LLM}s: Addressing Scarce Data and Bias Challenges in Mental Health and Therapeutic Counselling",
    author = "Kumar, Vivek  and
      Rajwat, Pushpraj Singh  and
      Medda, Giacomo  and
      Ntoutsi, Eirini  and
      Recupero, Diego Reforgiato",
    editor = "Mitkov, Ruslan  and
      Ezzini, Saad  and
      Ranasinghe, Tharindu  and
      Ezeani, Ignatius  and
      Khallaf, Nouran  and
      Acarturk, Cengiz  and
      Bradbury, Matthew  and
      El-Haj, Mo  and
      Rayson, Paul",
    booktitle = "Proceedings of the First International Conference on Natural Language Processing and Artificial Intelligence for Cyber Security",
    month = jul,
    year = "2024",
    address = "Lancaster, UK",
    publisher = "International Conference on Natural Language Processing and Artificial Intelligence for Cyber Security",
    url = "https://aclanthology.org/2024.nlpaics-1.26/",
    pages = "238--251",
    abstract = "abstract Large language models (LLMs) have shown promising capabilities in healthcare analysis but face several challenges like hallucinations, parroting, and bias manifestation. These challenges are exacerbated in complex, sensitive, and low-resource domains. Therefore, in this work, we introduce IC-AnnoMI, an expert-annotated motivational interviewing (MI) dataset built upon AnnoMI, by generating in-context conversational dialogues leveraging LLMs, particularly ChatGPT. IC-AnnoMI employs targeted prompts accurately engineered through cues and tailored information, taking into account therapy style (empathy, reflection), contextual relevance, and false semantic change. Subsequently, the dialogues are annotated by experts, strictly adhering to the Motivational Interviewing Skills Code (MISC), focusing on both the psychological and linguistic dimensions of MI dialogues. We comprehensively evaluate the IC-AnnoMI dataset and ChatGPT{'}s emotional reasoning ability and understanding of domain intricacies by modeling novel classification tasks employing several classical machine learning and current state-of-the-art transformer approaches. Finally, we discuss the effects of progressive prompting strategies and the impact of augmented data in mitigating the biases manifested in IC-AnnoM. Our contributions provide the MI community with not only a comprehensive dataset but also valuable insights for using LLMs in empathetic text generation for conversational therapy in supervised settings."
}
```













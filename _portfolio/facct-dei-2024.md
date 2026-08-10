---
title: "A Community Centered Approach to Bias Evaluation"
excerpt: "Using funds from FAccT 2024 Scholars program, I implemented a 1-year research project with 4 MSc and 3 BSc women students from Addis Ababa Institute of Technology and Addis Ababa Science and Technology University. The project was focused on evaluating gender bias in Machine Translation Datasets for three Ethiopian languages. Importantly, the project focused on bias in translation among the three languages (as opposed to the status quo of measuring bias when translating from English) and curated evaluation datasets and frameworks from the ground up relying on the languages' features and the community cultures. The PI, Dr. Hellina Hailu Nigatu, received the Wangari Maathai Impact Award at the 2026 Deep Learning Indaba conference for this work."
collection: portfolio
--- 
# Team Members:
PI: [Hellina Hailu Nigatu](https://hhnigatu.github.io/)

MSc Students: [Bontu Fufa Balcha](https://bontu-fufa.github.io/) * [Debora Taye Tesfaye](https://debsh.github.io) * [Ikram Behiru Nesiru](https://ikrambehiru.github.io/) * [Elbethel Daniel Zewdie](https://elbethel-dan.github.io/)

BSc Students: [Bethelhem Yemane Mamo](https://betabravah.github.io/) * [Jitu Ewnetu Hailu](https://jiituu.github.io/) * [Senait Mengesha Yayo](https://et.linkedin.com/in/senait-mengesha-72b586230) 

# Main Project

**Title**: Evaluating Machine Translation Datasets for Low-Web Data Languages: A Gendered Lens

**Abstract**: As low-resourced languages are increasingly incorporated into NLP research, there is an emphasis on collecting large-scale datasets. But in prioritizing quantity over quality, we risk 1) building language technologies that perform poorly for these languages and 2) producing harmful content that perpetuates societal biases. In this paper, we investigate the quality of Machine Translation (MT) datasets for three low-resourced languages–Afan Oromo, Amharic, and Tigrinya, with a focus on the gender representation in the datasets. Our findings demonstrate that while training data has a large representation of political and religious domain text, benchmark datasets are focused on news, health, and sports. We also found a large skew towards the male gender–in names of persons, the grammatical gender of verbs, and in stereotypical depictions in the datasets. Further, we found harmful and toxic depictions against women, which were more prominent for the language with the largest amount of data, underscoring that quantity does not guarantee quality. We hope that our work inspires further inquiry into the datasets collected for low-resourced languages and prompts early mitigation of harmful content.

[**Publication in ACL Findings 2026**](https://aclanthology.org/2026.findings-acl.330.pdf) * [**Github Link**](https://github.com/hhnigatu/EvaluatingMTDatasets)

# Project Extension 1

**Title**: Probing Gender Bias in Masked Language Models for Low-Web Data Languages

**Abstract**: Low-resourced languages are increasingly included in large multilingual models. While including more languages in pretrained models is a sign of progress, large models still underperform on low-resourced languages. In prioritizing scale over effective processing, we risk 1) deploying language technologies that misrepresent these languages and 2) amplifying gender biases embedded in training corpora. In this paper, we investigate how masked language models encode gender for three low-web-data languages, Afan Oromo, Amharic, and Tigrinya, and how these representations shift after continued pretraining on NLLB data. Using a controlled cloze-style probing setup, we examine prediction patterns. Our findings show consistent gender asymmetries and predictions aligned with stereotypical adjectives and occupations. After continued pretraining, we find that male-gendered predictions reach up to 68% in Amharic, while neutral predictions exceed 60% in Afan Oromo. Our work shows that expanding training data does not guarantee balanced gender representations without careful consideration in data curation.

[**Non-Archival Paper at AfricaNLP 2026**](https://openreview.net/attachment?id=atBsBqbT6x&name=pdf) * [**Github Link**](https://github.com/jiituu/Evaluating-bias-in-MT)

# Project Extension 2

**Title**: Yeswa-Stories: A Three-Way Parallel Dataset of Female African Figures in Low-Web Data Languages

**Abstract**: Language technologies used in everyday settings, such as machine translation systems, risk perpetuating societal bias. Prior work in creating benchmarks for gender bias in machine translation systems 1) focus primarily on high-resourced language pairs or a low-resourced language paired with a high-resource language, 2) use template based benchmarks that usually focus on occupational biases and stereotypes, and 3) translate high-resource benchmarks, which may lack cultural significance to low-resourced languages. In this paper, we introduce Yeswa-Stories, a three-way parallel dataset comprising 1,300 aligned sentences in Amharic, Afaan Oromo, and Tigrinya. We constructed the dataset in two ways: first, we collected English sentences from Wikipedia articles about notable African women and translated them into the three target languages using human translators. To improve cultural representativeness, we further augment the dataset with locally sourced content reflecting the cultural context where the languages are spoken. Our dataset contributes a new resource for studying gender-inclusive translation in low-resourced settings.

[**Publication in GITT Workshop 2026**](https://openpress.tilburguniversity.edu/system/actioncallout/f/f/2/ff291301-8f23-42f9-936d-e6176a30d181/attachment/0026f090e0342d98024b2a280fb42734.pdf#page=93) * [**Github Link**](https://github.com/hhnigatu/Yeswa-Stories) * [**Dataset Link**](https://huggingface.co/datasets/bethelhemyemane/yeswa-stories)

---
license: apache-2.0
task_categories:
- question-answering
language:
- en
pretty_name: AllyArc OpenAI Dataset Format
size_categories:
- 1K<n<10K
---


# Dataset Card for AllyArc/allyarc_oai_format

This dataset card provides a structured overview of the AllyArc/allyarc_oai_format dataset, designed for training conversational AI models tailored for educational purposes, with a special focus on supporting students with diverse learning needs, including those in Special Educational Needs (SEN) education.

## Dataset Details

### Dataset Description

The AllyArc/allyarc_oai_format dataset is comprised of conversational exchanges formatted to support the training of AI models for educational dialogues. It includes interactions that cover a wide range of educational support tasks, such as providing detailed explanations (breakdowns), adapting to various learning styles, incorporating student interests into lessons, and managing classroom dynamics tailored to SEN education.

- **Curated by:** Zainab Fahim
- **Language(s) (NLP):** English
- **License:** MIT License

### Dataset Sources

- **Repository:** Hugging Face Datasets

## Uses

### Direct Use

The dataset is intended for direct use in training conversational AI models to:
- Understand and respond to educational queries.
- Personalize interactions based on student needs and learning styles.
- Provide breakdowns of complex educational content.
- Engage students with tailored educational strategies.

### Out-of-Scope Use

This dataset is not intended for uses beyond educational support. Specifically, it should not be used for:
- Commercial advertising.
- Non-educational chatbot training.
- Any form of decision-making that could negatively impact students' wellbeing.

## Dataset Structure

The dataset is structured into dialogues, each containing multiple turns with roles (`system`, `user`, `assistant`) indicating the speaker. It includes fields for dialogue ID, turns, education level, subject matter, and feedback mechanisms, facilitating comprehensive educational dialogues.

## Dataset Creation

### Curation Rationale

The dataset was curated to address the nuanced needs of SEN education, focusing on creating a supportive, interactive, and adaptive learning environment through AI-driven dialogues.

### Source Data

#### Data Collection and Processing

Data collection involved simulating educational dialogues that reflect typical interactions between students and an educational AI. The process emphasized personalization, adaptability, and inclusivity, considering the diverse needs of SEN students.

#### Who are the source data producers?

The data was produced by educational specialists, SEN teachers, and AI developers, with input from SEN students to ensure authenticity and relevance.

### Annotations

#### Annotation process

The dialogues were annotated with educational intent, subject matter tags, and personalized learning strategies to facilitate model training on educational tasks.

#### Who are the annotators?

Educational specialists and SEN teachers annotated the dataset, ensuring that the dialogues accurately reflect educational best practices and SEN considerations.

## Bias, Risks, and Limitations

The dataset aims to minimize bias by including diverse educational needs and learning styles. However, users should be aware of the limitations in scope and ensure models trained on this dataset are used ethically and considerately in educational contexts.

## Citation

**APA:**

AllyArc Educational Team. (2023). AllyArc/allyarc_oai_format Dataset. Hugging Face. URL

**BibTeX:**

```bibtex
@misc{allyarc2023dataset,
  title={AllyArc/allyarc_oai_format Dataset},
  author={AllyArc Educational Team},
  year={2023},
  publisher={Hugging Face},
  howpublished={\url{}},
}
```

## Dataset Card Authors

Zainab Fahim

## Dataset Card Contact

For inquiries related to the AllyArc/allyarc_oai_format dataset, please contact: [Zainab Fahim](mailto:shafna.zainab.fahim@gmail.com)
# KolZchutQA

KolZchutQA is a closed-book question answering project that aims to advance the field of natural language processing (NLP) models in the Hebrew language. While significant progress has been made in recent years, there is a need to address the ethical implications and limitations of existing models, particularly within specific domains.

To bridge this gap, the KolZchutQA project introduces the Israeli Rights Domain Closed-Book Question-Answering Dataset. This dataset is carefully curated and encompasses a diverse range of questions pertaining to various legal rights and scenarios. The questions are sourced from the Israeli website [**זכות-כל**](https://www.kolzchut.org.il/), known for its comprehensive coverage of legal rights in Israel.

The process of constructing the dataset involved collecting paragraphs from relevant pages on the [**זכות-כל**](https://www.kolzchut.org.il/) website. Using this contextual information, we generated 450 questions along with their corresponding answers. Great care was taken to ensure the accuracy and fidelity of the questions, capturing the essence of the legal rights discussed on the website.

To evaluate the effectiveness of the closed-book question-answering system, we employed a finetuned HeBERT model. This model was previously trained on an automatic translation of the English SQuAD dataset. By leveraging the HeBERT model on our KolZchutQA dataset, we can assess its ability to accurately provide answers to the questions regarding Israeli legal rights.

For your convenience, the final model can be downloaded from the following link: [Final Model Download](https://drive.google.com/file/d/1mHThtqTl7nA4YEfG5Zu2qcuGrrkh98Tk/view?usp=share_link)

## Acknowledgements

I would like to express our gratitude to the creators of the [**זכות-כל**](https://www.kolzchut.org.il/) website for providing a valuable resource of legal rights information in Israel. Additionally, I extend my appreciation to Dr.Navot Akiva for his invaluable guidance all throughout the project.


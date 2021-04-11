# MIDS_NLP_Project

This repo contains my work on MIDS W266 final project in Spring 2021. Our paper and two Colab notebooks are in this repo.

### Title of my project:   
#### DeBERTa Model Fine-tuned for Commonsense Validation and Explanation

### Abstract:
In this paper, we explore how pre-trained DeBERTa models can be fine-tuned on SemEval-2020 Task 4, Commonsense Validation and Explanation (ComVE). ComVE includes three subtasks, and we introduce our systems for the first two subtasks: Subtask A is to distinguish a natural language statement that makes sense from one that does not, and Subtask B is to provide reasonable explanations for why the false statement does not make sense. We achieved an accuracy rate of 87.8\% for Subtask A and 89.7\% for Subtask B. 

No team competing in the contest has ever used DeBERTa model for the tasks. More importantly, since DeBERTa model does not have a built-in capability for directly solving multiple choice questions, our paper describes our approach to develop the multiple choice capability on top of DeBERTa, and fine-tune it on ComVE dataset. Our model out-performed the fine-tuned BertForMultipleChoice model. Our accuracy rate for Subtask B would have ranked us at top 10 among all submissions that did not resort to external knowledge base to complement their pretrained language models.

### Links to resources:

- My [presentation slides](https://docs.google.com/presentation/d/1n3uhe_zqPueJB5hH-A3azzbwVoJ7BkF_LGwkmr3FxYU/edit?usp=sharing)

- My git [repo](https://github.com/chenxicclu/MIDS_NLP_Project) containing my project code. 

- Githubs that I built on top of or consulted while writing my code:   
  - [BERT Fine-Tuning Tutorial with PyTorch](https://colab.research.google.com/drive/1pTuQhug6Dhl9XalKB0zUGf4FIdYFlpcX#scrollTo=6J-FYdx6nFE_) by Chris McCormick and Nick Ryan.

- The [official repo](https://github.com/wangcunxiang/SemEval2020-Task4-Commonsense-Validation-and-Explanation) of the SemEval 2020 Task 4 contest
- The [dataset](https://github.com/wangcunxiang/SemEval2020-Task4-Commonsense-Validation-and-Explanation/tree/master/ALL%20data) I used for my project


# HF_arxiv_labelling

Задача: дообучить distil-bert из библиотеки huggingface transformers на задачу multilabel классификации статей по их названию и abstract. 

Каждой статье сопоставляется набор тегов в соответствии с принятыми на arxiv. Обучение шло на датасете статей из arxiv до 2020 года.

Для хостинга модели используется huggingface пространство https://huggingface.co/spaces/dimsafin/HF_tune.articles, обертка написана при помощи streamlit.

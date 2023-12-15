# RuStoryGeneration
Репозиторий содержит ресурсы и модели, разработанные в рамках проекта [РНФ № 23-21-00330](https://rscf.ru/project/23-21-00330/):
- модель ruArtStyleGPT-3, генерирующая тексты в художественном стиле;
- обучающий корпус пар <текст – сюжетная линия> из 562 сказок на русском языке с выделенными сюжетными линиями и тестовый корпус из 25 сюжетных линий;
- модель ruSimBERT, обученная на задаче определения семантического сходства текстов;
- корпус из 10500 предложений на русском языке, размеченных по семантическому сходству.

## Библиографический список

* [Agirre et al., 2015] Agirre E., Banea C., Cardie C., Cer D., Diab M., Gonzalez-Agirre A., Guo W., Lopez-Gazpio I., Maritxalar M., Mihalcea R., Rigau G., Uria L., Wiebe J. SemEval-2015 Task 2: Semantic Textual Similarity, English, Spanish and Pilot on Interpretability // Proceedings of the 9th International Workshop on Semantic Evaluation (SemEval 2015), Denver, Colorado. 2015. P. 252–263.
* [Agirre et al., 2016] Agirre E., Banea C., Cer D., Diab M., Gonzalez-Agirre A., Mihalcea R., Rigau G., Wiebe J. SemEval-2016 Task 1: Semantic Textual Similarity, Monolingual and Cross-Lingual Evaluation // Proceedings of the 10th International Workshop on Semantic Evaluation (SemEval-2016), San Diego, California: Association for Computational Linguistics. 2016. P. 497–511.
* [Bowman et al., 2015] Bowman S.R., Angeli G., Potts C., Manning C.D. A large annotated corpus for learning natural language inference // Proceedings of the 2015 Conference on Empirical Methods in Natural Language Processing, Lisbon, Portugal. 2015. P. 632–642.
* [Campos et al., 2020] Campos R., Mangaravite V., Pasquali A., Jatowt A., Jorge A., Nunes C., Jatowt A. YAKE! Keyword Extraction from Single Documents using Multiple Local Features // Information Sciences Journal. 2020. Vol. 509. P. 257–289.
* [Carlsson et al., 2022] Carlsson F., Ohman J., Liu F., Verlinden S., Nivre J., Sahlgren M. Fine-grained controllable text generation using non-residual prompting // Proceedings of the 60th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2022. P. 6837-6857.
* [ChatGPT] Introducing ChatGPT. URL: https://openai.com/blog/chatgpt.
* [E5] E5 Large pretrained language model. URL: https://huggingface.co/intfloat/e5-large.
* [Hua & Wang, 2020] Hua X., Wang L. PAIR: Planning and iterative refinement in pre-trained transformers for long text generation // Computing Research Repository. 2020. – arXiv:2010.02301.
* [KeyBERT] KeyBERT. URL: https://github.com/MaartenGr/KeyBERT.
* [Mistral] Mistral pretrained language model. URL: https://mistral.ai/news/announcing-mistral-7b.
* [ruAlpaca] LLaMA 13B trained on the ru_turbo_alpaca, Russian instructions dataset. URL: https://huggingface.co/IlyaGusev/llama_13b_ru_turbo_alpaca_lora.
* [ruBERT] RuBERT Large pretrained language model. URL: https://cloud.ru/ru/datahub/rugpt3family/rubert-large.	
* [ruGPT-3] RuGPT-3 Large pretrained language model. URL: https://cloud.ru/ru/datahub/rugpt3family/rugpt-3-large.
* [Rutermextract] Rutermextract. URL: https://github.com/igor-shevchenko/rutermextract.
* [ruRoberta] RuRoBERTa large pretrained language model. URL: https://sbercloud.ru/ru/datahub/rugpt3family/ruroberta-large.
* [Saiga] Saiga 13B, Russian LLaMA-based chatbot. URL: https://huggingface.co/IlyaGusev/saiga_13b_lora.
* [SBERT] SBERT large pretrained language model. URL: https://developers.sber.ru/en/portal/products/sbert.
* [Škrlj et al., 2019] Škrlj B., Repar A., Pollak S. RaKUn: Rank-based Keyword extraction via Unsupervised learning and Meta vertex aggregation // Statistical Language and Speech Processing: 7th International Conference, SLSP 2019, Ljubljana, Slovenia, October 14–16, 2019, Proceedings 7. 2019. PP. 311–323.
* [Taori et al., 2023] Taori R., Gulrajani I., Zhang T., Dubois Y., Li X., Guestrin C., Liang P., Hashimoto T.B. Alpaca: A Strong, Replicable Instruction-Following Model // Stanford Center for Research on Foundation Models. 2023. Vol. 3(6). P. 7.
* [TextRank] Implementation of TextRank for keyword Extraction. URL: https://github.com/JRC1995/TextRank-Keyword-Extraction.
* [Touvron et al., 2023] Touvron H., Lavril T., Izacard G., Martinet X., Lachaux M.-A., Lacroix T., Roziere B., Goyal N., Hambro E., Azhar F., Rodriguez A., Joulin A., Grave E., Lample G. LLaMA: Open and Efficient Foundation Language Models // Computing Research Repository. 2023. – arXiv:2302.13971.
* [Vychegzhanin et al., 2023a] Vychegzhanin S., Kotelnikova A., Sergeev A., Kotelnikov E. MaxProb: Controllable Story Generation from Storyline // Computational Linguistics and Intellectual Technologies: Proceedings of the International Conference "Dialogue 2023". Issue 22. P. 564–576.
* [Vychegzhanin et al., 2023b] Vychegzhanin S., Kotelnikova A., Sergeev A., Kotelnikov E. Controllable Story Generation based on Perplexity Minimization // Analysis of Images, Social Networks and Texts (AIST 2023). Lecture Notes in Computer Science (in print).
* [Welleck et al., 2020] Welleck, S., Kulikov, I., Roller, S., Dinan, E., Cho, K., Weston, J. Neural text generation with unlikelihood training // Proceedings of the 8th International Conference on Learning Representations. 2020. P. 1–18.
* [Xu et al., 2015] Xu W., Callison-Burch C., Dolan W.B. SemEval-2015 Task 1: Paraphrase and Semantic Similarity in Twitter (PIT) // Proceedings of the 9th international workshop on semantic evaluation (SemEval 2015). 2015. С. 1–11.
* [Zehtab-Salmasi et al., 2021] Zehtab-Salmasi A., Feizi-Derakhshi M.-R., Balafar M.-A. FRAKE: Fusional Real-time Automatic Keyword Extraction // Computing Research Repository. 2021. – arXiv:2104.04830.


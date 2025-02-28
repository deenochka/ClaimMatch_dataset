# ClaimMatch
The dataset for the paper "Zero-shot and Few-shot Learning with Instruction-following LLMs for Claim Matching in Automated Fact-checking"

The dataset relies on the texts from the fully available public dataset (Nakov et al., 2022: https://ceur-ws.org/Vol-3180/paper-29.pdf). We use the multi-domain English subset of
the data.

ClaimMatch dataset, used in the experiments on Large Language models, contains 1,000 claim pairs: 
500 for the positive class (two claims in a pair are matching: label 1) 
and 500 for the negative class (two claims in a pair are not matching: label 0).
There are three tab-separated columns: claim1, claim2, label.
You can read more about the dataset in the following paper: https://aclanthology.org/2025.coling-main.650/ or https://arxiv.org/abs/2501.10860 .

# Citation:      

    @inproceedings{pisarevskaya-zubiaga-2025-zero,
    title = "Zero-shot and Few-shot Learning with Instruction-following {LLM}s for Claim Matching in Automated Fact-checking",
    author = "Pisarevskaya, Dina  and
      Zubiaga, Arkaitz",
    editor = "Rambow, Owen  and
      Wanner, Leo  and
      Apidianaki, Marianna  and
      Al-Khalifa, Hend  and
      Eugenio, Barbara Di  and
      Schockaert, Steven",
    booktitle = "Proceedings of the 31st International Conference on Computational Linguistics",
    month = jan,
    year = "2025",
    address = "Abu Dhabi, UAE",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2025.coling-main.650/",
    pages = "9721--9736",
    abstract = "The claim matching (CM) task can benefit an automated fact-checking pipeline by putting together claims that can be resolved with the same fact-check. 
    In this work, we are the first to explore zero-shot and few-shot learning approaches to the task. We consider CM as a binary classification task and experiment 
    with a set of instruction-following large language models (GPT-3.5-turbo, Gemini-1.5-flash, Mistral-7B-Instruct, and Llama-3-8B-Instruct), investigating prompt 
    templates. We introduce a new CM dataset, ClaimMatch, which will be released upon acceptance. We put LLMs to the test in the CM task and find out that it can be 
    tackled by leveraging more mature yet similar tasks such as natural language inference or paraphrase detection. We also propose a pipeline for CM, which we 
    evaluate on texts of different lengths."}

or 

      @misc{pisarevskaya2025zeroshotfewshotlearninginstructionfollowing,
      title={Zero-shot and Few-shot Learning with Instruction-following LLMs for Claim Matching in Automated Fact-checking}, 
      author={Dina Pisarevskaya and Arkaitz Zubiaga},      
      year={2025},      
      eprint={2501.10860},      
      archivePrefix={arXiv},      
      primaryClass={cs.CL},      
      url={https://arxiv.org/abs/2501.10860}, }

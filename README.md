# Artificial Intelligence as an Archival Science
## CS7180: Special Topics in AI: Spring 2024

**Class meeting:** Mondays and Thursdays, 11:45am &ndash; 1:25pm

**Instructor:** David Smith (Office hours: TBA; WVH 356 or via zoom)

#### Course Description

A common mode for understanding artificial intelligence systems, from popular fiction to textbooks in computer science, has been the metaphor of an agent that perceives, forms beliefs about, and intervenes in the world. In the past year, some scholars have instead framed large pretrained language and vision models as _cultural technologies_ (Gopnik; Farrell and Shalizi, 2023). Other researchers have pointed out that the builders of large AI models must take on some curatorial tasks in order to be successful and should learn from archival practice (Jo and Gebru, 2020).

In this seminar, we will read and discuss papers addressing large language and vision models as tools to investigate human language, history, and culture; analyzing and auditing corpus creation for model training; and exploring and mitigating biases and gaps in the archives of the past.  Students will take turns presenting and leading discussion of papers along with the relevant background material. All students will write short reviews of the papers we read and work on writing research papers on a topic of their choice.

#### Prerequisites

There are no official prerequisites; however, it is expected that students have some background either in NLP, computer vision, or other machine learning field, or in working computationally with large collections of text and images in the humanities or social sciences.

#### Syllabus

Each week, we will read about two papers on a common theme. The papers could be tied together by methodology&mdash;e.g., model or inference method&mdash;, by subject matter, or by media or archive type.

A list of the first few sets of papers is forthcoming. Further readings will be added by input from seminar participants.  General topics include:

* Computational models as archives
* Archival documentation for models and datasets, &ldquo;collections as data&rdquo;
* Text and Natural Language Processing
  - Literary and narrative archives
  - Documentary archives
* Vision
  - OCR and textual archives: e.g., manuscripts, typewritten records, government archives
  - OCR and visual archives: e.g., text found on images, maps, photographs
  - Image recognition for journalistic and documentary collections
  - Image recognition for art archives
  - Action recognition and audiovisual archives
* Sound
  - Speech recognition: oral history, radio archives
  - Sound classification: music and ambient sound
* Generative Models: Abundance and Loss
  - Missing data
  - Bias, error, and inference
  - Text correction and restoration
  - Image inpainting and video generation
  - Narrative generation
  - Critical fabulation

Readings scheduled so far are as follows:

* January 8: Prolegomena: The Sociology of Information. We'll talk about the structure and organization of the course. We'll introduce some of its themes, drawing on these background readings.
  - Generating and processing information: Part I of: Suzanne Briet. [_What Is Documentation?_](https://roday.pages.iu.edu/what%20is%20documentation.pdf). Translated by Ronald E. Day et al., Scarecrow Press, 2006. [Original text (1951)](http://martinetl.free.fr/suzannebriet/questcequeladocumentation/briet.pdf)
  - States, markets, and AI: Henry Farrell and Cosma Shalizi. [Shoggoths amonst us](https://crookedtimber.org/2023/07/03/shoggoths-amongst-us/). July 3, 2023.

* January 11: Archival Perspectives on AI
  - Eun So Jo and Timnit Gebru. [Lessons from Archives: Strategies for Collecting Sociocultural Data in Machine Learning.](https://doi.org/10.1145/3351095.3372829) Proceedings of the 2020 Conference on Fairness, Accountability, and Transparency, ACM, 2020, pp. 306–16. [Giulia]
  - Meera Desai, Abigail Jacobs, and Dallas Card. [An Archival Perspective on Pretraining Data](https://openreview.net/forum?id=9xhUufywBX). 2023. [Shijia]
  - An example of documenting an LLM training set: Luca Soldaini. [AI2 Dolma: 3 Trillion Token Open Corpus for Language Model Pretraining](https://blog.allenai.org/dolma-3-trillion-tokens-open-llm-corpus-9a0ff4b8da64). August 18, 2023.

* January 15: MLK Holiday (no class)

* January 18: Cultural Technologies
  - Eunice Yiu, Eliza Kosoy, and Alison Gopnik. [Imitation versus Innovation: What Children Can Do That Large Language and Language-and-Vision Models Cannot (Yet)?](https://arxiv.org/abs/2305.07666). 2023. [Sheridan]
  - Chapter 2 of: Albert Lord. [_The Singer of Tales_](https://chs.harvard.edu/read/lord-albert-bates-the-singer-of-tales/). Harvard University Press, 2nd edition 2000, 1st edition 1960. [David]

* January 22: Cultural Evolution
  - Levin Brinkmann et al. [Machine Culture](https://arxiv.org/pdf/2311.11388). _Nature Human Behaviour_, Nov. 2023, pp. 1–14. [Jaydeep]
  - Alberto Acerbi and Joseph M. Stubbersfield. [Large Language Models Show Human-like Content Biases in Transmission Chain Experiments.](https://doi.org/10.1073/pnas.2313790120) _Proceedings of the National Academy of Sciences_, vol. 120, no. 44, Oct. 2023, p. e2313790120. [Sheridan]

* January 25: Head Canons
  - Kent K. Chang, Mackenzie Cramer, Sandeep Soni, and David Bamman. [Speak, Memory: An Archaeology of Books Known to ChatGPT/GPT-4](https://aclanthology.org/2023.emnlp-main.453/). In _EMNLP_ 2023. [Christopher]
  - Lyra D'Souza and David Mimno. [The Chatbot and the Canon: Poetry Memorization in LLMs](https://ceur-ws.org/Vol-3558/paper5712.pdf). In _CHR_ 2023. [Shijia]

* January 29: Data Archaeology
  - Bonnie Mak. [Archaeology of a Digitization](https://doi.org/10.1002/asi.23061). _Journal of the Association for Information Science and Technology_, 65(8), Aug. 2014, pp. 1515–26. [Giulia]
  - Benjamin Lee et al. [The Newspaper Navigator Dataset: Extracting And Analyzing Visual Content from 16 Million Historic Newspaper Pages in Chronicling America](http://arxiv.org/abs/2005.01583). arXiv:2005.01583 May 2020. [Luna]
  - See also: Lee, Benjamin. [Compounded Mediation: A Data Archaeology of the Newspaper Navigator Dataset](https://www.digitalhumanities.org/dhq/vol/15/4/000578/000578.html). _Digital Humanities Quarterly_, vol. 015, no. 4, Dec. 2021.


* February 1: Privacy and Secrecy
  - Jie Huang, Hanyin Shao, and Kevin Chen-Chuan Chang. [Are Large Pre-Trained Language Models Leaking Your Personal Information?](https://aclanthology.org/2022.findings-emnlp.148.pdf). In _Findings of EMNLP_, 2022. [Jaydeep]
  - Renato Rocha Souza, Flavio Codeco Coelho, Rohan Shah, and Matthew Connelly. [Using Artificial Intelligence to Identify State Secrets](https://arxiv.org/abs/1611.00356). arXiv:1611.00356 November 2016. [David]
  - See also: [America's Most Redacted](http://www.history-lab.org/declassificationengine/americas-most-redacted)

* February 5: Discuss paper ideas

* February 8: The flight to quality
  - Suchin Gururangan, Dallas Card, Sarah K. Dreier, Emily K. Gade, Leroy Z. Wang, Zeyu Wang, Luke Zettlemoyer, and Noah A. Smith. [Whose Language Counts as High Quality? Measuring Language Ideologies in Text Data Selection](https://doi.org/10.48550/arXiv.2201.10474). arXiv:2201.10474. January 2022. [Sheridan]
  - Li Lucy, Suchin Gururangan, Luca Soldaini1, Emma Strubell1, David Bamman, Lauren Klein, and Jesse Dodge. [AboutMe: Using Self-Descriptions in Webpages to Document the Effects of English Pretraining Data Filters](https://doi.org/10.48550/arXiv.2401.06408). arXiv:2401.06408, January 2024. [Christopher]

* February 12: Textual Restoration
  - Shruti Rijhwani, Daisy Rosenblum, Antonios Anastasopoulos, and Graham Neubig. [Lexically Aware Semi-Supervised Learning for OCR Post-Correction](http://arxiv.org/abs/2111.02622). arXiv:2111.02622 [Cs], Nov. 2021. [David]
  - Nikolai Vogler, Jonathan Parkes Allen, Matthew Thomas Miller, Taylor Berg-Kirkpatrick. [Lacuna Reconstruction: Self-Supervised Pre-Training for Low-Resource Historical Document Transcription](https://doi.org/10.18653/v1/2022.findings-naacl.15). Findings of NAACL, pp. 206–16, 2022. [Jaydeep]

* February 15: Auditing Image Datasets
  - Abeba Birhane, Vinay Prabhu, Sang Hau, Vishnu Naresh Boddeti, Alexandra Sasha Luccioni. [Into the LAIONs Den: Investigating Hate in Multimodal Datasets](https://doi.org/10.48550/arXiv.2311.03449). arXiv:2311.03449, 6 Nov. 2023. [Shijia]
  - Ali Shirali and Moritz Hardt. [What Makes ImageNet Look Unlike LAION?](https://doi.org/10.48550/arXiv.2306.15769) arXiv:2306.15769, 27 June 2023. [Giulia]

* February 19: Presidents Day holiday (no class)

* February 22: Image and Video Restoration
  - Raphaela Heil and Fredrik Wahlberg. [Restoration of Archival Images Using Neural
Networks](https://ceur-ws.org/Vol-3232/paper06.pdf). In _Digital Humanities in the Nordic and Baltic Countries Conference (DHNB)_, 2022. [David]
  - Lorenzo Agnolucci, Leonardo Galteri, Marco Bertini, and Alberto Del Bimbo. [Reference-Based Restoration of Digitized Analog Videotapes](http://arxiv.org/abs/2310.14926). arXiv:2310.14926, 3 Nov. 2023. [Chris]

* February 26: Googling for Data
  - Nicholas Carlini, Jamie Hayes, Milad Nasr, Matthew Jagielski, Vikash Sehwag, Florian Tramèr, Borja Balle, Daphne Ippolito, and Eric Wallace. [Extracting Training Data from Diffusion Models
](https://arxiv.org/abs/2301.13188). arXiv:2301.13188, 30 Jan. 2023. [Sheridan]
  - Milad Nasr, Nicholas Carlini, Jonathan Hayase, Matthew Jagielski, A. Feder Cooper, Daphne Ippolito, Christopher A. Choquette-Choo, Eric Wallace, Florian Tramèr, Katherine Lee. [Scalable Extraction of Training Data from (Production) Language Models](http://arxiv.org/abs/2311.17035). arXiv:2311.17035, Nov. 2023. [Jaydeep]

* February 29: Sounds and Symbols
  - Anne-Sophie Ghyselen, Anne Breitbarth, Melissa Farasyn, Jacques Van Keymeulen, and Arjan van Hessen. [Clearing the Transcription Hurdle in Dialect Corpus Building: The Corpus of Southern Dutch Dialects as Case Study](https://www.frontiersin.org/articles/10.3389/frai.2020.00010). _Frontiers in Artificial Intelligence_ 3, 2020. [Chris]
  - Martijn Bartelds, Wietse de Vries, Faraz Sanal, Caitlin Richter, Mark Liberman, and Martijn Wieling. [Neural Representations for Modeling Variation in Speech]( https://doi.org/10.1016/j.wocn.2022.101137). _Journal of Phonetics_ 92 (May): 101137, 2022. [Shijia]

* March 4: Spring break (no class)

* March 7: Spring break (no class)

* March 11: Draft project outlines (no class)

* March 14: Present project outlines

* March 18: Causal Employment
  - Egami, Naoki, Christian J. Fong, Justin Grimmer, Margaret E. Roberts, and Brandon M. Stewart. [How to Make Causal Inferences Using Texts](https://doi.org/10.1126/sciadv.abg2652). _Science Advances_, October 2022. [Shijia]
  - Field, Anjalie, Doron Kliger, Shuly Wintner, Jennifer Pan, Dan Jurafsky, and Yulia Tsvetkov. [Framing and Agenda-Setting in Russian News: A Computational Analysis of Intricate Political Strategies](https://doi.org/10.18653/v1/D18-1393). In _Proceedings of the 2018 Conference on Empirical Methods in Natural Language Processing_, 3570–80, 2018. [Chris]

* March 21: Imaging Bias
  - Wang, Angelina, Alexander Liu, Ryan Zhang, Anat Kleiman, Leslie Kim, Dora Zhao, Iroha Shirai, Arvind Narayanan, and Olga Russakovsky. [REVISE: A Tool for Measuring and Mitigating Bias in Visual Datasets](https://doi.org/10.48550/arXiv.2004.07999). In _ECCV_, 2020. [David]
  - Tang, Ruixiang, Mengnan Du, Yuening Li, Zirui Liu, Na Zou, and Xia Hu. [Mitigating Gender Bias in Captioning Systems](https://doi.org/10.48550/arXiv.2006.08315). In _WWW_, 2021. [David]

* March 25: Memorizing and Forgetting
  - Eldan, Ronen, and Mark Russinovich. [Who’s Harry Potter? Approximate Unlearning in LLMs](https://doi.org/10.48550/arXiv.2310.02238). arXiv 2310.02238, Oct. 2023. [Jaydeep]
  - Gandikota, Rohit, Joanna Materzynska, Jaden Fiotto-Kaufman, and David Bau. [Erasing Concepts from Diffusion Models](http://arxiv.org/abs/2303.07345). arXiv, 2023. [Sheridan]

* March 28: The Ecology of Manuscript Culture
  - Kestemont, Mike, Folgert Karsdorp, Elisabeth De Bruijn, Matthew Driscoll, Katarzyna A. Kapitan, Pádraig Ó Macháin, Daniel Sawyer, Remco Sleiderink, and Anne Chao. [Forgotten Books: The Application of Unseen Species Models to the Survival of Culture](https://doi.org/10.1126/science.abl7655). _Science_ 375 (6582): 765–69, 2022. NB main paper and supplementary materials. [Jaydeep]
  - Camps, Jean-Baptiste, and Julien Randon-Furling. [Lost Manuscripts and Extinct Texts: A Dynamic Model of Cultural Transmission.](https://ceur-ws.org/Vol-3290/long_paper3261.pdf) In _Computational Humanities Research_, 2022. [Shijia]

* April 1: Gaps and Errors
  - Hopkins, Daniel J., and Gary King. [A Method of Automated Nonparametric Content Analysis for Social Science](https://doi.org/10.1111/j.1540-5907.2009.00428.x). _American Journal of Political Science_ 54 (1): 229–47, 2010. [Chris]
  - Egami, Naoki, Musashi Hinck, Brandon M. Stewart, and Hanying Wei. [Using Imperfect Surrogates for Downstream Inference: Design-Based Supervised Learning for Social Science Applications of Large Language Models](https://doi.org/10.48550/arXiv.2306.04746). In _NeurIPS_, 2023. [David]

* April 4: Critical Fabulation
  - Saidiya Hartman. [Venus in Two Acts](https://muse.jhu.edu/article/241115). _Small Axe_ 12 (2): 1–14, 2008.
  - Nina Begus. [Experimental Narratives: A Comparison of Human Crowdsourced Storytelling and AI Storytelling](https://doi.org/10.48550/arXiv.2310.12902). arXiv, 2023. [Sheridan]

* April 8: Total Eclipse of the Class (no class)

* April 11: Cui Bono?
  - Colavizza, Giovanni, Tobias Blanke, Charles Jeurgens, and Julia Noordegraaf. [Archives and AI: An Overview of Current Debates and Future Perspectives](https://doi.org/10.1145/3479010). _Journal on Computing and Cultural Heritage_ 15 (1): 1–15. 2022. [Giulia]
  - Atari, Mohammad, Mona J. Xue, Peter S. Park, Damián Blasi, and Joseph Henrich. 2023. [Which Humans?](https://doi.org/10.31234/osf.io/5b26t) OSF preprint, Sept. 2023. [Sheridan]

* April 15: Patriots Day holiday (no class)

* April 18: Meta-Models
  - Jacob Andreas. [Language Models as Agent Models](https://doi.org/10.48550/arXiv.2212.01681). arXiv, Dec. 2022.
  - Harvey Lederman and Kyle Mahowald. [Are Language Models More Like Libraries or Like Librarians? Bibliotechnism, the Novel Reference Problem, and the Attitudes of LLMs](https://doi.org/10.48550/arXiv.2401.04854). arXiv, Feb. 2024.

* April 22: Present projects

* April 25: Submit papers (no class)

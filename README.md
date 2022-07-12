# **Emotion-Dataset-from-Indonesian-Public-Opinion**
**Authors**: Riccosan*, Karen E. S., Galih D. P., & Andry Chowanda

## Abstract
Opinion is a type of judgment or a person's point of view about something. Twitter is a popular social media platform that includes a lot of public opinion and would be a suitable location to mine data in text form. Indonesia, with its vast population and active Twitter user base, has the potential to be a source of opinion data mining. An opinion may be processed and resulting in the form of a person's emotion response towards something, such as whether they like, hate, love, or happy about it. Upon that basis, a dataset of Indonesian-language tweets conveying public opinion on a variety of topics was formed. The fact that there are so few public emotion text datasets in Indonesian language also supports our basis in this research to form our emotion dataset. The gathered data was cleaned and normalized in the pre-processing stage to the necessary form for study on the task of classifying emotions in Indonesian. The data formed is annotated with six emotional labels, namely anger, fear, joy, love, sad, and neutral.

**Key Words:** Emotion Classification, Dataset, Tweet, Indonesia

## Data Format
Raw, Filtered, Annotated

## About The Data
This dataset was formed from Indonesian tweet containing six emotion values, namely anger, fear, joy, love, sad, and neutral. The total data in this dataset is 7,080 and it is fully cleaned and fully annotated. Each label has a varied amount of data distribution, including 1,130 data for anger, 911 data for fear, 1,275 data for joy, 760 data for love, 1,003 data for sad, and 2,001 data for neutral.

| **Emotion Label** | Anger |  Fear  |  Joy  | Love |  Sad  | Neutral |
| ----------------- | ----- | ------ | ----- | ---- | ----- | ------- |
| **Total Data**    | 1,130 |   911  | 1,275 |  760 | 1,003 |  2,001  |

## Pre-processing Stage
Basic pre-processing [2] is applied to the acquired data in the form of:
1. Eliminating duplicates,
2. Lower-casing sentences,
3. Hastags removal,
4. Unused information removal (such as mentions, URLs, emoticons, non-emotion symbol).

Stop-words normalization were not implemented, and there was no token normalization (one-two characters, slang terms, informal words, and short words) in this study, with the goal of optimizing the acquisition of information for the emotion classification in the data.

**Notes:**
If you only want to perform feature/token extraction, it's recommended to perform data normalization first.

## Additional Information
To access this dataset research paper in order to get a more elaborate understanding, please access the DOI:
https://doi.org/10.1016/j.dib.2022.108465

## Paper References
1. P. R. Shaver, U. Murdaya, & R. Chris Fraley, Structure of the Indonesian Emotion Lexicon, Asian J. of Soc. Psyc. 4 (2001) 201-224. https://doi.org/10.1111/1467-839X.00086.
2. E. Nugraheni, Indonesian Twitter Data Pre-processing for the Emotion Recognition, 2019 International Seminar on Research of Info. Tech. & Intelligent Systems (ISRITI). (2019) 58-63. Yogyakarta, Indonesia: IEEE. https://doi.org/10.1109/ISRITI48646.2019.9034653.
3. M. S. Saputri, R. Mahendra, & M. Adriani, Emotion Classification on Indonesian Twitter Dataset, 2018 Int. Conf. on Asian Language Processing (IALP). (2018) 90-95. Bandung, Indonesia: IEEE. https://doi.org/10.1109/IALP.2018.8629262.
4. P. Shaver, J. Schwartz, D. Kirson, & C. O'Connor, 1987. Emotion Knowledge: Further Exploration of a Prototype Approach. Journal of Personality aid Social Psychology. 52, 6. 1061-1086. https://doi.org/10.1037//0022-3514.52.6.1061.
5. W. G. Parrott, Emotions in social psychology: Essential readings (Eds.), Psychology Press, New York, USA, 2001. ISBN: 9780863776823.
6. S. Kusal, S. Patil, J. Choudrie, K. Kotecha, D. Vora, & I. Pappas, 2022. A Review on Text-Based Emotion Detection -- Techniques, Applications, Datasets, and Future Directions. arXiv. 1-74. https://doi.org/10.48550/arXiv.2205.03235.
7. A. J. Viera & J. M. Garrett, 2005. Understanding Interobserver Agreement: The Kappa Statistic. Family Medicine. 37, 5. 360-363. PMID: 15883903.
8. J. Devlin, M. W. Chang, K. Lee, & K. Toutanova, BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding, Proc. of the 2019 Conf. of the North American Chapter of the Association for Computational Linguistics: Human Language Technologies. 1 (2019) 4171-4186. Minneapolis, Minnesota: Association for Computational Linguistics. http://dx.doi.org/10.18653/v1/N19-1423.


# Licensed
Shield: [![CC BY-NC-ND 4.0][cc-by-nc-nd-shield]][cc-by-nc-nd]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-NoDerivs 4.0 International License][cc-by-nc-nd].

[![CC BY-NC-ND 4.0][cc-by-nc-nd-image]][cc-by-nc-nd]

[cc-by-nc-nd]: http://creativecommons.org/licenses/by-nc-nd/4.0/
[cc-by-nc-nd-image]: https://licensebuttons.net/l/by-nc-nd/4.0/88x31.png
[cc-by-nc-nd-shield]: https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg

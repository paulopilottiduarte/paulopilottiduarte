# In-depth description of Automated Readability Index (ARI) and Flesch-Kincaid Grade Level (FK)

### Introduction

The Education team decided to use readability metrics as one of the ways to assess our texts' quality. After analyzing a set of available metrics, we decided to use two of them: Automated Readability Index (ARI) and Flesch-Kincaid Grade Level (FK). Our reasons for choosing readability overall and these specific metrics are described here.

In the next sections, we will provide an in-depth description of the two chosen metrics.

### Automated Readability Index (ARI)

1. **General background and explanation of both indexes (when it was created, by whom, for what purpose, how it works, how it was first published — paper, article etc.)**

The ARI index was created to create a more easy and automated  approach to measure the readability of articles. By collecting data from the texts and then organizing according to automated tabulations it was possible to measure the complexity of the text.

The ARI was first published in the article “AUTOMATED READABILITY INDEX” by E. A. Smith and R. J. Senter, both from the Aerospace Medical Research Laboratories from USAF.

The ARI is measured according to the number of letters per word and the sentence difficulty is measured by using the numbers of words per sentence to create a weight to the then.

After these measurements the text was indexed. The way the ARI was measured followed the reading of technical material by officers from the USAF to test the comprehension of these texts. It was clear that some texts were more complex and, with that, more difficult to comprehend and, by thus, it was found a correlation between the ARI index (the complexity measurements of the texts) and the grade of comprehension that was reached.

2. **Description of index itself (how it is measured (ex. 1-20), explanation of what each point of the index means (ex. 1 = very hard to read or equivalent to 2nd grade), any other specific characteristics)**

The method itself evaluates how hard a text is to read according to the level of literacy, this helps to create a table where it’s possible to associate the complexity grade of a text with the expected formation of the reader. For example, a US-Grade level 1 corresponds to a child with an age between 6 and 8 years old - or, in other words, a kindergarten student.

To calculate this index is used a simple formula, which will be used to create a table to correlate the score with the grade level the students require to understand.

![Formula ARI](assets/20220803_120407_Captura_de Tela 2022-08-03 às 12.03.53.png)

By this formula, the text will be classified according to the table below, every “level” of complexity corresponds to a level of literacy needed to fully understand the text. The ideal index is around 8 (that’s the literacy mean of an adult American). It’s valuable to note that we can have non-integer numbers when using the formula, when this happens, the number will be rounded to the nearest number up. Convey to observe that this considers the average level of an American that goes to a fully-english educational system.

Assuming this data, it’s a good practice that the aim when writing an article for a general audience should be at level 8 in order to reach the majority of our audience.


|      Age      | School level   | Index |
| :--------------: | ---------------- | ------- |
|  5-6 yrs. old  | Kindergarten   | 1     |
|  6-7 yrs. old  | First Grade    | 2     |
|  7-8 yrs. old  | Second Grade   | 3     |
|  8-9 yrs. old  | Third Grade    | 4     |
| 9-10 yrs. old | Fourth Grade   | 5     |
| 10-11 yrs. old | Fifth Grade    | 6     |
| 11-12 yrs. old | Sixth Grade    | 7     |
| 12-13 yrs. old | Seventh Grade  | 8     |
| 13-14 yrs. old | Eighth Grade   | 9     |
| 14-15 yrs. old | Ninth Grade    | 10    |
| 15-16 yrs. old | Tenth Grade    | 11    |
| 16-17 yrs. old | Eleventh grade | 12    |
| 17-18 yrs. old | Twelfth grade  | 13    |
| 18-22 yrs. old | College        | 14    |

It’s also relevant to understand that a text at level 8 cannot be considered a bad text, it could be just a simple and concise prose that can be read by a 8th grade in the same way any other adult, this just represents a mark to the minimum level of literacy needed.

### Flesch-Kincaid Grade Level (FK)

1. **General background and explanation of both indexes (when it was created, by whom, for what purpose, how it works, how it was first published — paper, article etc.**

This test is ideal for the web texts - initially it was thought to be a formula to determine the grade level required for students to read some certain types of texts. The test itself it’s derived from another readability text, Flesch Reading Ease (FRE), that was developed in the 1940’s, as an associated consultant with the press and developed the test to improve the readability of newspapers. The FK Grade Level was improved. The 1970’s by John P. Kincaid to the US Navy to determine if the manuals are easy to read and understand.

The main reason for this modification was that the Flash Reading Ease required a conversion table to determine whatever the reading level the text was classified. For this reason, the US Navy modified the test to be more direct, with a more direct approach with a correlational relation between the table and the level of the text.
Both tests use the same metrics to determine the score: number of words in a sentence and the length of a sentence, but the way they measure this number is reverse. The two tests are very close in an inverse correlation, with some weighing difference between the two texts, so, for example, a score that is high on FK will be a low score on the FRE, and the opposite will be valid too.

Finally, the FK testing was widely used in the US Navy as standard to manuals writing and many other documents, as insurance agreements using the main policy that the FK grade should be aimed to a ninth grade level (14/15 years-old student).

2. **Description of index itself (how it is measured (ex. 1-20), explanation of what each point of the index means (ex. 1 = very hard to read or equivalent to 2nd grade), any other specific characteristics)**

he same way the other tests, the GK text use formulas do determine the score, in the particular case, the test use the following formula to calculate the general score:
And, with the number obtained from this formula, the table will be created accordingly.

So, for instance, a text with a grade level around 80 will be an easy to read text, accessible and easy to understand to the majority of readers, in the other hand, a text with a low score, such as 15, will be a very hard to read text and will be accessible only to educated persons, like college graduate students.


|   Score   |           School Level           |
| :---------: | :--------------------------------: |
| 90 to 100 |            5th grade            |
| 80 to 90 |            6th grade            |
| 70 to 80 |            7th grade            |
| 60 to 70 |        8th and 9th grade        |
| 50 to 60 | 10th to 12th grade (high school) |
| 30 to 50 |             college             |
|  0 to 30  |         college graduate         |

The aim while writing a text is the 8th. level grade (the vast majority of Americans have this leve o literacy).

With this in mind, a way to improve your text is to use simple words and short sentences. This practice will improve the readability of your text. If the writer aims for this, he’ll achieve an easy to read text. The FKRA (Flesch Kincaid Read Age) is based on two other indexes: the ASL (Average Sentences Length) and ASW (Average Syllables per Word). These two indexes will help to improve the final score of the text and aim for better readability.

In the website of FK Grade Level Readability Calculator os given some tips to improve the writings:
Shorten your paragraphs. Five sentences per paragraph is a good guide.
Use simple words. Words used in everyday conversations are easier to understand.
Use simple sentences. Running sentences are a no-no. Break up your sentences if you need to.
Write for your audience. Research your target audience and their reading abilities. Write in their own language and lingo so they can easily comprehend your text.
The final conclusion is that this index is more suitable for educational and web texts.

There’s a lot of tools to verify your texts against the various readability indexes that can be accessed on the references.

### Final considerations

After considering the pros and cons of utilizing the readability methods to measure the level of our texts, we have decided the metrics will be used in conjunction with other measures to further determine the impact on SEO, readability, and focus on the readers we want to reach. Furthermore, we still need to analyze the impact using these metrics could have in the workflow for the dev writing activity.

By now, it is clear that using just one metric could be problematic, since we have to consider some particularities of different genres when writing. With that in mind, we've found the best way to develop this activity is to merge the two readability metrics with other text analysis, even though the readability indexes will be used and will serve as a guideline to our technical documentation writing process.

## Apendix

### Notes on the two articles against the readability tests

The main idea that these formulas are not very useful comes from the 80’s, mainly through Dr. Schriver. The biggest criticism is that the use of these formulas is not necessarily an indication of ease of reading or understanding, on the contrary, often the search for the score of these standards ends up leading the writers to error, for example, when using short words that don’t pass all the necessary meaning, don’t take into account the target audience of the text itself and, finally, don’t match the knowledge that should be passed on through these documents.

One of the main criticisms is that these indexes are not made thinking about technical texts and assume that short words, whatever they may be, are better than long words.
What should be taken into account is that the texts are written for a specific audience, so more than worrying about the indexes or the words being used, the important is to use an adequate terminology, suitable for that audience, that makes sense to the reader and that’s clear and able to convey the message to which it proposes. The text should, before seeking a good score in any index, seek to be readable to the people who will read it.

Another scholar of these indices, and a detractor of them, is Dr. Redish. He states that these indexes are not made seeking a technical text because they ignore that some writing techniques, such as the use of bullet-lists, facilitate the understanding of steps to be organized (as in an algorithm to be followed by the reader to solve or learn a certain subject). These indexes also fail to determine whether a text is properly using the correct terminology for its target audience, and especially whether the headings or titles are meaningful and clear - demonstrating what each section intends to teach.

An international group was formed to study what is called the “plain language”, and wrote what is called the ISO Plain Language Standard (which will be published in 2022). The group was formed by specialists speaking 17 languages and formed partnerships with a large number of organizations and people. Most of these researchers have been in this field for decades. And the only mention of readability indexes is that it should be ignored (all).

For this group, a text has a good readability when your reader is able to understand what is written effortlessly, find what they are looking for in the text and use this information for what they wanted to do. In addition, the group gives four principles on what the text must have to be a good (readable) text:

- Readers get what they want (relevant)
- Readers find what they’re looking for (findable)
- Readers understand what they found (understandable)
- Readers are able to use this information (usable)

The idea behind criticism of formulas is not to ignore all the work done to create them, but to show that just focusing on word size and sentence length is not always (or almost always) a good idea or strategy to follow when writing a text.

The problems are divided into seven main axes:

1. Formulas are unreliable: different formulas give us different results. There is a study showing that different programs can give different scores for the same text using the same formula.
1. The formulas do not measure what is really necessary for the text to be easy and useful to the reader. Most of these formulas do not give an indication of what should be done to improve the text, only triggers a number that is used within a simple conference table. This is usually not useful for most technical writers.
1. Most formulas do not take into account what words are used. Only the Dale-Chall index has a list of words that are most commonly used/known by US students (at a ratio of 80%). The others focus on determining the size of words and sentences. Even so, we need to be aware that these word lists are not always used with the same meaning. Cookies,
1. Enter and other words changed their meaning when computing first appeared.
   The idea of levels of studies (grade levels) is not always useful. What do you mean when saying that “you’re able to read like an eighth grader”? Or a 13-year-old student? On the contrary, a student with this reading level is an avid reader, reads well for his age and probably likes to read, on the other hand, an adult with this reading level does not like to read and has never advanced in his reading level, although, he carries an experience - and probably a vocabulary - much richer than the imaginary student.
1. The article also gives a practical example of this: during the writing of a rental contract, an English term was changed from “security deposit” to “promise money”. This change positively affected the score of the formulas. As a test, the authors took both versions of the contract to a community center and gave it to people to read. Everyone understood what “promise money” was, but most didn’t know what it meant and were agitated as they read it (thinking it would be a promise of money), whereas after the explanation that it was just another way of saying it was a “security deposit,” everyone calmed down because that was a term they were used to.
1. Thus, it is easy to see that measuring the reading level of adults according to their level of education can’t be a reliable metric, after all, many of these adults carry a terminology that is already usual for them and that is widely used in written documents, even if the words seem or sound more complex.
1. Reviewing the text to improve the score (just for that) does not make sense. According to the author, if you have long sentences and long words, which end up reducing your score, the problem is not necessarily in the size of the words or sentences. That’s the symptom. Thus, by shortening words and sentences we are only attacking the symptom and not the cause of the text problems.

The main conclusion, using both articles as reference, is that these indexes should not be used as the only metric do write, along with these metrics, we should be concerned with the following:

- Write to those who will read the text
- If possible, do a research with readers about that text (or create an “assumptive persona” to better analyze the text)
- Write clearly, use active voice whenever possible, etc.
- Use the indexes only as a guide, but don’t change your content just based on the score they give you.
- Test your text with others to validate what you have written (if it is easy to understand, to find information, to use, etc.).
- If possible, seek help from a person who is unfamiliar with the type of text you are writing.

### References

Derivation of new readability formulas (automated readability index, fog count and flesh reading ease formula) for Navy enlisted personnel. [https://apps.dtic.mil/sti/pdfs/ADA006655.pdf](https://apps.dtic.mil/sti/pdfs/ADA006655.pdf)

McClure G (1987). "Readability formulas: Useful or useless. (an interview with J. Peter Kincaid.)". IEEE Transactions on Professional Communication. 30: 12–15.

Flesch-Kincaid Grade Level Readability Calculator. [https://www.textcompare.org/readability/flesch-kincaid-grade-level/](https://www.textcompare.org/readability/flesch-kincaid-grade-level/)

REITH, George. Readability in B2B content: does your Flesch-Kincaid grade matter? [https://radix-communications.com/readability-in-b2b-content-flesch-kincaid-grade-score/](https://radix-communications.com/readability-in-b2b-content-flesch-kincaid-grade-score/)

Automatic Readability Checker (Our Free Text Readability Consensus Calculator). [https://readabilityformulas.com/free-readability-formula-tests.php](https://readabilityformulas.com/free-readability-formula-tests.php)

E. A. Smith; R. J. Senter. AUTOMATED READABILITY INDEX”. [https://apps.dtic.mil/sti/pdfs/AD0667273.pdf](https://apps.dtic.mil/sti/pdfs/AD0667273.pdf)

J. PETER KINCAID; LEROY J. DELIONBACH. Validation of the Automated Readability Index: A Follow-Up [https://journals.sagepub.com/doi/10.1177/001872087301500103](https://journals.sagepub.com/doi/10.1177/001872087301500103)

Ponomarenko, G. L.; Finatto, M. J.; Índices para cálculo de Leiturabilidade. [http://www.ufrgs.br/textecc/acessibilidadett/files/Indices-de-Leiturabilidade.pdf](http://www.ufrgs.br/textecc/acessibilidadett/files/Indices-de-Leiturabilidade.pdf)

Analyze My Writing. [https://www.analyzemywriting.com/readability_indices.html](https://www.analyzemywriting.com/readability_indices.html)

http://websites.umich.edu/~driving/publications/ZhouHeejinGreenHowConsistReadability.pdf

https://files.eric.ed.gov/fulltext/ED074343.pdf

https://www.plainlanguage.gov/guidelines/test/usability-testing/

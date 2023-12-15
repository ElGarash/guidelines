# Guidelines

Core guidelines that govern how things work inside ELGarash.

# What to work on?

1. Watch "You and Your Research" by Richard Hamming.

   [![Alt text](https://img.youtube.com/vi/a1zDuOPkMSw/0.jpg)](https://www.youtube.com/watch?v=a1zDuOPkMSw)

# How to manage experiments?

1. An experiment should be lightweight, with a clear end goal, takes at max a week, and easily disposable.

2. The end goal of the experiment should be clear, if the end goal is a UI for example, you should provide a mockup.

   a. the mockup should be simple, preferably done in tldraw.

   b. If the experiment is data transformation (e.g., removing tashkel), you should provide a few examples.

3. If the experiment is concerned with generating a new dataset, you should document the new dataset.

   a. Columns names.

   b. Naming schemes.

   c. etc...

4. Keep a file called `terminology.md` and keep updating it with new terminology, stick to single terminology (e.g., don't use `sheik` and `reciter` interchangeably stick to one).
5. Stick to a single notation

   a. In mathematics.

   b. Also for data annotation (e.g., the playback speed should be `x1.5`, don't use `1.5x` or `(1.5x)` interchangeably).

6. Figures should have titles below it with the following format:

   ```md
    <p align="center">
       <span style="color: #888888;">_Figure <experiment name><figure number>_: <description>.</span>
    </p>
    <p align="center">
        <img src="./media/<img_path>" alt="<alt>">
    </p>
   ```

   a. The `img_path` should match `<experiment name><figure number>`.

7. Tables should have titles above it with the following format:

   ```md
   <span style="color: #888888;">_Table <experiment name><table number>_: <description>.</span>
   ```

   a. Add descriptive column/row names.

   b. Units should be specified in the column/row not in values, and put in parentheses, for example, `WER (%)`, or `Execution time (s)`.

8. If you are comparing the result of two experiments, put the results of the old experiment in the current one, don't reference it.

9. Links of the associated notebooks should added to the experiment report.

10. If you are quoting, word to word, from a paper, you should use the quote syntax in markdown:

    ```md
    > This is a quote
    ```

11. Add references as the final section of the report.

12. No Experiment should go un-reviewed, open a PR, and someone else should review, sign-off, and approve your experiment.

13. No direct pushes to main.

14. Even if the experiment fails, it should be reported.

# How to write?

1. Keep your writings short and persuasive, and don’t use extra words → Hemingway app can help you with that.

2. **_Magician’s Mar Magician’s Mark_**: Whenever you feel like writing “due to the fact that,” “as a result,” “therefore,” “for that reason,” “accordingly,” or even “because,” consider using a colon instead to make the reader ask “why”:

3. **Seize** the chance to **pepper** our sentences with such verbs. Try swapping the underlined language for some visual and evocative action words.

4. **That Reminds Me**: use analogies.

5. Starting Gate: start sentences fast.

6. Parallels:

   > Parallel structure means using the same pattern of words to show that two or more ideas have the same level of importance. This can happen at the word, phrase, or clause level. The usual way to join parallel structures is with the use of coordinating **[conjunctions](https://owl.purdue.edu/owl/general_writing/punctuation/independent_and_dependent_clauses/index.html)**  such as "and" or "or."

7. Titles are 80% of the work, but you write it as the very last thing. It has to be a compelling opinion or important learning

8. Check out the resources in the [dev-writing repo](https://github.com/Nutlope/devwriting).

9. Check out [How to Write a Machine Learning Paper for (not so) Dummies](https://abdulrhmnghanem.notion.site/How-to-Write-a-Machine-Learning-Paper-for-not-so-Dummies-89e17d6fe034400abe7bee1abfaa1311?pvs=74)

10. Use the right scientific tense, check out [How to Use Tenses within Scientific Writing](https://www.unr.edu/writing-speaking-center/writing-speaking-resources/how-to-use-tenses-within-scientific-writing).

- Points 2, 3, 4, 5, and 6 are from _Five Ways to Write Like The Economist_.

# Code

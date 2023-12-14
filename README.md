# Guidelines

core guidelines that govern how things work inside ELGarash.

# Experiments

1. An experiment should be lightweight, with a clear end goal, takes at max a week, and easily disposable.
2. The end goal of the experiment should be clear, if the end goal is UI for example, you should provide a mockup.
   a. the mockup should be simple, preferably done in tldraw.
   b. If the experiment is data transformation (e.g., removing tashkel), you should provide a few examples.
3. If the experiment is concerned with generating a new dataset, you should document the new dataset.
   a. columns names.
   b. naming schemes.
   c. etc...
4. Keep a file called `terminology.md` and keep updating it with new terminology, stick to single terminology (e.g., don't use `sheik` and `reciter` interchangeably stick to one).
5. Stick to a single notation
   a. in mathematics.
   b. also for data annotation (e.g., the playback speed should be `x1.5`, don't use `1.5x` or `(1.5x)` interchangeably).
6. Figures should have titles below it with the following format:

   ```md
    <p align="center">
       <span style="color: #888888;">_Figure <experiment name><figure number>_: <description>.</span>
    </p>
    <p align="center">
        <img src="./media/<img_path>" alt="<alt>">
    </p>
   ```

   a. `img_path` should match `<experiment name><figure number>`.

7. Tables should have titles above it with the following format:

   ```md
   <span style="color: #888888;">_Table <experiment name><table number>_: <description>.</span>
   ```

   a. Add descriptive column/row names.

   b. units should be specified in the column/row not in values.

8. If you are comparing the result of two experiments, reference put the results of the old experiment in the current one, don't reference it.

9. Links of the associated notebooks should added to the experiment report.

10. If you are quoting, word to word, from a paper, you should use the quote syntax in markdown:

    ```md
    > This is a quote
    ```

11. Add references as the final section of the report.

12. No Experiments should go un-reviewed, open a PR, and someone else should review, sign-off, and approve your experiment.

13. No direct commits to main.

## Code

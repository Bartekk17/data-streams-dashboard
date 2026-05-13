## List of Implemented Changes and Updates

* *Comment:* "Hyperplane stream is quite limited (in terms of instance count) given the dimensionality of the data. Please extend the evaluation period."
* *Action taken:* The evaluation period for the Hyperplane stream has been extended to include 20 000 number of instances.

* *Comment:* "The report states that up to 20000 instances of a stream of 18 000 instances were used (weather data). Please fix."
* *Action taken:* The text now accurately reflects that the maximum number of instances used for the weather dataset aligns with its actual size (18 159 instances).

* *Comment:* "Please add the performance of the auxhiliary logistic regression model to panel 4 and make it clear in the other panels whether they rely on logisitic regression." and "Please clarify all relevant details, e.g. in which of the cases logistic regression and reference model is used etc."
* *Action taken:* The performance of the auxiliary Logistic Regression model is now plotted as a baseline alongside the main model in Panel 4. Additionally, the report explanations have been updated (including asterisks in the summary table) to clearly indicate which panels rely on the auxiliary model (Panels 1, 2, 3, and 4).

* *Comment:* "Prediction Confidence Margin - is this one based on logistic regression as well? Please clarify in report and GUI."
* *Action taken:* The title of Panel 6 has been updated to explicitly state *"Prediction confidence margin (Main model)"*. The report now clearly explains that this margin is calculated using the posterior probabilities of the main classifier, not the auxiliary logistic regression.

* *Comment:* "Please cross-check the language of your report to eliminate editorial issues such as 'deviatio monitor'."
* *Action taken:* Performed a thorough proofreading of the report to fix typographical errors and editorial issues.

* *Comment:* "Please explicitly refer to figure numbers e.g. in Sect. 4.2."
* *Action taken:* Updated the text across the report to ensure all figures are explicitly referenced by their numbers.

* *Comment:* "Please make figures larger in your report."
* *Action taken:* Adjusted the formatting of the document. All figures and dashboard screenshots have been enlarged.

## Pending work

Due to time/ constraints, the following suggested extensions have not been included in the current iteration.

* **Pseudocode Implementation (`algorithm2e`):** The addition of a formalized algorithm using `algorithm2e` to map out ADWIN operations and confidence margin calculations is pending.
* **Alternative Main Method (e.g., Adaptive Random Forest) & Wrapper Architecture:**

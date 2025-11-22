# AI Vinyl and Plushy image sorter

## Project Description
Google AI image project designed to identify vinyl records and stuffed animals.

## Classes Identified
List the objects your model was trained to identify:
* Class 1 Vinyl Records
* Class 2 Stuffed Animals

## Discussion & Reflection
*(Please answer the following questions thoughtfully)*

1.  **Model Performance & Iteration:**
    * How accurate was your first trained model? Very. It accurately identified each object within 90-95%.
    * What steps did you take to iterate and improve its performance? I added an extra object to each class to further improve accuracy.
    * How did these changes affect the model's accuracy and confidence scores? It did not change the accuracy by much, but it was still correct 100% of the time in my testing.

2.  **Challenges & Observations:**
    * Which objects were the easiest for your model to learn and distinguish? Why do you think that was? Probably the vinyl records due to the shape of them.
    * Which objects were the most challenging? What made them difficult? The stuffed animals had slightly less accuracy, but it was still always correct.
    * What happened when you showed the model an object it wasn't trained on? How did the confidence scores behave, and why is this significant? I showed my face and my phone, it thought I was a stuffed animal and thought my phone was a vinyl. It likely thought that due to the shapes.

3.  **Bias in AI:**
    * If you only trained your "mug" class with images of *your specific mug* (and didn't vary color, shape, etc.), how well do you think it would recognize other students' significantly different mugs? How does this illustrate the concept of bias being introduced through training data? If you trained your “mug” class only using images of your specific mug, the model would probably fail to recognize other students’ mugs—especially if they differ in shape, color or pattern material, handle size, or orientation.
    * Imagine all your training images were taken in very bright, direct lighting. What might happen if you tried to use the model in a dimly lit room or with strong shadows? How does this relate to the robustness and potential biases of AI models? If all your training images were taken in very bright, direct lighting, your model would learn to recognize objects only under those lighting conditions. When used in a dimly lit room or in strong shadows, its performance would likely drop because the visual features it relied on are no longer present.

4.  **Model Limitations & Usefulness:**
    * What are some key limitations of the model you created? Identifying anything other than what is was trained on.
    * Why is it useful to be able to download your trained model files (like `model.json`, `weights.bin`) and share them (e.g., via GitHub)? What does this enable? It enables users to reproduce your exact results.

5.  **Real-World Applications & Ethics:**
    * Brainstorm 2-3 real-world applications where a similar image classification model could be useful. It would be useful in identifying circuit boards that are defective and in medical x rays for identifying broken/injured bones.
    * Briefly discuss one ethical consideration that developers should keep in mind when building and deploying image recognition AI in the real world (e.g., related to fairness, privacy, misuse). One major ethical consideration is privacy, especially when image recognition AI is used in public spaces. Image classifiers can unintentionally capture and analyze people who did not consent to being recorded

## (Optional) Challenges Faced / Interesting Discoveries
* Add any other specific challenges you encountered or interesting things you discovered during this lab.

## (Optional) Screenshot
* You can embed a screenshot of your Teachable Machine interface here if you like.

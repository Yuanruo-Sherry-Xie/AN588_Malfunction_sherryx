# AN588_Malfunction_sherryx

-   Hi there! 😄

-   In this repo you should see the following:

    -   Orignial code (r markdown)

    -   Original code (html)

    -   Final code based off of the original code \^ (r markdown)

    -   Final code based off of the original code \^ (html)

    -   Peer commentary from Slyvie Adams (r markdown)

    -   Peer commentary from Slyvie Adams (html)

-   My orignial code and final code incorporates all questions asked in the HW 4 file as well as links for modules that I looked back on for this hw

-   Each section should be the title/ header before the notes and code are shown

-   I have comments in my code sections to help my readers and myself understand what's going on or my thought process in general, let me know if they are confusing

-   In my original code is also 5 struggles I encountered while doing homework 4

Thank you for reading this!👍

### 5 Struggles I Have Encountered Doing HW 4

1.  **Understanding the Rule of Thumb for Z.prop.test()** While implementing the `Z.prop.test()` function, I encountered difficulty recalling the rule of thumb conditions for valid normal approximation in a proportion test — specifically the conditions that n×p>5n \times p > 5n×p\>5 and n×(1−p)>5n \times (1 - p) > 5n×(1−p)\>5. These conditions are important for ensuring that the normal distribution can be appropriately applied to the data. Even though I successfully implemented the conditions by following the instructions, I felt unsure about their theoretical foundation. I realized I should have revisited the relevant module material or notes to better understand why these conditions are important. This experience taught me the importance of thoroughly reviewing foundational concepts rather than relying solely on instructions.
2.  **Structuring the Z.prop.test() Function Correctly.** While designing the structure of my `Z.prop.test()` function, I struggled to determine the best way to organize my code for clarity and functionality. I knew I needed to split the logic between one-sample and two-sample tests, but I wasn't sure how to proceed efficiently. I initially tried combining the logic for both scenarios in one code block, which became confusing and harder to debug. Eventually, I realized that separating the one-sample and two-sample conditions into distinct parts of the function improved readability and ensured the function performed correctly in both cases. This struggle highlighted the importance of structuring my code in a logical and organized manner to avoid confusion.
3.  **Difficulty Spotting Mistakes Without Peer Feedback.** While implementing the confidence interval calculation for my `Z.prop.test()` function, I mistakenly used `p1` instead of `p0` in the formula. Despite carefully reviewing my code, I overlooked this error. Fortunately, my peer commentator noticed the mistake and pointed it out to me. This experience emphasized that I sometimes struggle to identify errors on my own, especially in complex calculations. It reminded me of the value of peer review and collaboration, and it reinforced the importance of stepping away from my work before reviewing it with fresh eyes — a strategy I’ll apply in future coding tasks.
4.  **Predicting Values and Constructing CI/PI in Regression Analysis.** When adding 90% confidence and prediction intervals (CI and PI) to my regression plot, I struggled with the correct sequence of steps. Specifically, I wasn’t sure how to combine the predicted values with the CI and PI bands while ensuring they correctly aligned with the regression model. Although I eventually managed to construct the plot by combining the original data with the predicted values and corresponding intervals, I was uncertain whether I had done it correctly. This struggle highlighted that I need to develop a clearer understanding of how `predict()` outputs are structured and how to sequence those outputs effectively in `ggplot2`.
5.  **Predicting Longevity for a Brain Size of 800 gm.** Predicting the longevity of a species with a brain size of 800 gm presented some confusion. I was unsure if I had structured my predict() function input correctly, especially when calculating the prediction interval (PI). The syntax for predict() requires defining the data frame structure carefully, and I initially questioned whether I needed to separate one-sample and two-sample conditions for this prediction step, similar to how I split those steps in my Z.prop.test() function. Eventually, I realized that the predict() function handles this automatically, provided the correct structure for the new data is specified. This challenge showed me that understanding how different functions operate — especially in terms of input formatting — is essential to producing accurate results.

# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?

0.83 -> 0.60; Not accurate because the model isn't scaled

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.

0.83; Pretty accurate, a lot better than without StandardScaler, high enough for me becuase correlation is very strong. Only a few wrong.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?

The model did pretty well with only a handful of wrong results. There was no pattern in mine since the third value was 0.98 and -1.02 whether it was wrong or right.

[[ 2.03872775 -0.81465453  0.98019606]]
Predicted Gender: Female Actual Gender: Male

[[-0.34910049  1.24088543 -1.02020406]]
Predicted Gender: Male Actual Gender: Female

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.

She would not buy an SUV based on her data
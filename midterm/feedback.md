# Notes on the Midterm

* _Correctness    (out of 40):_ 35
* _Good Practices (out of 10):_ 9
* _Docs / Testing (out of 10):_ 0

_Details on the grading criteria for the midterm can be found on [Canvas](https://canvas.slu.edu/courses/28045/rubrics/23671)._

Overall, nicely done. 

You didn't include any docstrings or test cases as required. I deduced 10 points from the _Docs / Testing_ score.


## Step 1
For the couple of issues noted below, I deducted 2 points from your _Correctness_ score.
* Your approach to this was correct, but there was a typo in `for j in i["allowed_amount"]` where it should have said `"allowed_amounts"` with an `s` on the end.
* Your function `return`ed inside the loop, meaning that it would not process the whole file. As a result, it returned the wrong answer even when I got it running.


## Step 2
* Nice work. Just missing the docstrings and tests.

## Step 3
For the errors below, I deducted 3 points from your _Correctness_ score.
* There's a typo in the line where you try to convert the date information into a datetime object and extract the weekday. It should have said `datetime.date(...)` instead of `datetime.data(...)`.
* You have another typo when you misspell `serivce_code`
* Another typo with `allowed_amont`
* Rather than reproducing all the code from `get_rate()` here, you should have just called your `get_rate()` function. I deducted 1 point from _Good Practices_.

## Step 4
* Your answers here were pretty close, but I think there was an error in rounding somewhere.
* That said, you had the right idea. I'm giving you full _Correctness_ markes for this part.
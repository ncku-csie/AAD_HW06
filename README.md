# AAD_HW06

This repository include **starter code**, **Espresso AndroidTest** and **Travis setting**, which are used for automatically grading in **Android Application Development course in National Cheng Kung University (NCKU)** in 2019 Spring Semester.

Materials:
- **Lesson 6:Testing your UI** in Codelabs for Android Developer Fundamentals (V2). 
<https://developer.android.com/courses/fundamentals-training/toc-v2>

Feel free to fork this repository if you are also working on this codelab and want to testing your answer.
For more instructions, please follow the [homework rules slides](https://github.com/ncku-csie/AAD_HW01/blob/master/Homework%20Rules.pdf). 
If you have further questions, please contact android@imslab.org

These test cases are written by Intelligent Mobile Service laboratory and Cyber Physical System Laboratory in NCKU.

---

Please follow the instructions on the Homework sections in these codelabs.

- [06.1: Espresso for UI testing](https://codelabs.developers.google.com/codelabs/android-training-espresso-for-ui-testing/index.html?#0)
 
## Part 1. Questions (30 pt)
Please submit your answer on moodle.
<https://moodle.ncku.edu.tw/course/view.php?id=104771>

**[Notice]** 
- You only have **one chance** to submit your answer.
- Your score on moodle (out of 100) * 30 % = your points in this part. <br>
For example, you score on moodle is 50, and then you got 50 * 30 % = 15 pt for this homework

| Codelab | Questions |
| --- | ----------- |
| 06.1 | 3 Questions |

## Part 2. Android Test (70 pt)

Please submit your code to the **master** branch in this repository for grading.

| Codelab | Questions | Points |
| --- | ----------- | ---|
| 06.1 | **Record another Espresso test** for the ScorekeeperEspresso app. This test should tap the Night Mode option in the options menu and determine whether the Day Mode option appears in its place. The test should then tap the Day Mode option and determine whether the Night Mode option appears in its place.| 70 pt |

For the test metioned above, you can follow the steps below to record the Espresso test.

1. Assert the textView in the optionsMenu is with the text, `Night Mode`.
2. Click the `Night Mode` textView.
3. Assert the textView in the optionsMenu is with the text, `Day Mode`.
4. Click the `Day Mode` textView.
5. Assert the textView in the optionsMenu is with the text, `Night Mode`.
6. **Save the record with the name, `DayNightTest`.**

**[Notice]** 

- **Please save the record with the name, `DayNightTest`; otherwise, you get no point in this part.**
- Please do not modify the following files:
    - .travis.yml
    - <Project>/app/src/androidTest/*
    - gradle files
- Once any modifications or any cheating behavior are detected, you will got 0 pt for this homework.
- Creating a new branch to develop and testing locally are highly recommended.

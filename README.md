# Mobile_Computing_Practical_8-A-

**Learning Journey: Constructing Guess-the-Celeb App - Part 1**

In a dedicated session lasting approximately 3 hours, I worked on initiating the development of the Guess-the-Celeb App. This involved setting up image assets, utilizing LogCat for debugging, and establishing fragment classes for the app's UI. The following details my experiences with each task:

**Task 0 - Self-Exploration:**

Reviewed Week 9 "Content Slides" on "Issues and Limits Discussion." Summarized Android's Guides about Performance and Power. The guides emphasize optimizing app performance, efficient memory management, and minimizing battery consumption for a seamless user experience.

**Task 1 - Setup Image Assets and Try Out LogCat:**

Created a new project "guessTheCeleb" with an asset folder.
Copied celebrity image files into the "celebs" folder within assets.
Tested code to access assets and display the asset list in LogCat.
Implemented ImageManager class to facilitate access to image assets as Bitmap objects.
Validated ImageManager functionality in MainActivity.

**Task 2 - Start Coding the UI and Associated Boilerplate Code:**

Commented out ImageManager test code in MainActivity.
Created blank fragments: GameFragment, StatusFragment, and QuestionFragment.
Tested GameFragment by replacing the constraint layout in activity_main.xml with a fragment tag.
Set up constraint layout in fragment_game.xml with TextView, Spinner, and Button.
Addressed text size issues for Spinner using styles.xml.
Created fragment_status.xml with a vertical LinearLayoutCompat and two TextViews.
Added a new style "large" for TextViews in fragment_status.xml.
Checked the UI changes by running the app.

**Task 3 - Self-Reflection:**

**Description of the Experience:**

Initiated the construction of the Guess-the-Celeb App, focusing on asset setup, debugging, and fragment UI.

**Feelings and Thoughts about the Experience:**

Excited to see the app structure taking shape. Encountered challenges in styling and layout adjustments.

**Evaluation of the Experience, Both Good and Bad:**

Successfully implemented asset access and began UI development. Adjusting text size for Spinner posed a challenge.

**Analysis to Make Sense of the Situation:**

Understanding asset management and UI setup is crucial. Exploring alternative approaches for Spinner text size.

**Conclusion about What I Learned and What I Could Have Done Differently:**

Gained insights into asset handling and fragment setup. Could explore more styling options and seek efficient solutions for challenges.

**Action Plan for Future Situations or Changes:**

Focus on refining styling and layout adjustments. Explore advanced UI features and efficient coding practices for better app development.

# pandas-challenge
When going through the assignment, I used ChatGPT when I had questions. It suggested using .reset_index() and also provided the code for creating a dataframe for 'match scores by grade.' Specifically the following was pulled from ChatGPT:
    math_scores_by_grade = pd.merge(ninth_grader_math_scores, tenth_grader_math_scores, on="school_name", suffixes=('_9th', '_10th'))
    math_scores_by_grade = pd.merge(math_scores_by_grade, eleventh_grader_math_scores, on="school_name", suffixes=('', '_11th'))
    math_scores_by_grade = pd.merge(math_scores_by_grade, twelfth_grader_math_scores, on="school_name", suffixes=('', '_12th'))

I used this structure again in the reading section.

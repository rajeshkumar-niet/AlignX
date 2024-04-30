# **Test Suite for Equivalence Class Partitioning**

## Input Parameters:

1. **Interests:**
   - User can list up to 3 industries they're curious about.

2. **Skills Snapshot:**
   - User can highlight a couple of skills they feel confident in.

3. **Career Vision:**
   - User can provide their dream job title and describe where they see themselves in 3 years.

4. **Work Environment:**
   - User can describe their ideal workplace in a few words.

5. **Education Background:**
   - User can provide their current field of study or major.
   - User can mention any additional courses/certifications they've completed.

6. **Miscellaneous:**
   - User can provide any additional information they think is relevant.

<br>

## Equivalence Classes:

1. **Interests:**
   - Class 1: User lists 0 industries.
   - Class 2: User lists 1 industry.
   - Class 3: User lists 2 industries.
   - Class 4: User lists 3 industries.

2. **Skills Snapshot:**
   - Class 1: User highlights 0 skills.
   - Class 2: User highlights 1 skill.
   - Class 3: User highlights 2 skills.

3. **Career Vision:**
   - Class 1: User does not provide dream job title or 3-year vision.
   - Class 2: User provides dream job title but no 3-year vision.
   - Class 3: User provides 3-year vision but no dream job title.
   - Class 4: User provides both dream job title and 3-year vision.

4. **Work Environment:**
   - Class 1: User does not describe ideal workplace.
   - Class 2: User provides a brief description of ideal workplace.

5. **Education Background:**
   - Class 1: User does not provide current field of study or major.
   - Class 2: User provides current field of study or major.
   - Class 3: User provides current field of study or major and mentions additional courses/certifications.

6. **Miscellaneous:**
   - Class 1: User does not provide any additional information.
   - Class 2: User provides additional information.

<br>


## Test Cases:

1. **Interests:**
   - Test Case 1: User lists 0 industries.
   - Test Case 2: User lists 1 industry.
   - Test Case 3: User lists 3 industries.

2. **Skills Snapshot:**
   - Test Case 4: User highlights 0 skills.
   - Test Case 5: User highlights 1 skill.
   - Test Case 6: User highlights 2 skills.

3. **Career Vision:**
   - Test Case 7: User does not provide dream job title or 3-year vision.
   - Test Case 8: User provides dream job title but no 3-year vision.
   - Test Case 9: User provides 3-year vision but no dream job title.
   - Test Case 10: User provides both dream job title and 3-year vision.

4. **Work Environment:**
   - Test Case 11: User does not describe ideal workplace.
   - Test Case 12: User provides a brief description of ideal workplace.

5. **Education Background:**
   - Test Case 13: User does not provide current field of study or major.
   - Test Case 14: User provides current field of study or major.
   - Test Case 15: User provides current field of study or major and mentions additional courses/certifications.

6. **Miscellaneous:**
   - Test Case 16: User does not provide any additional information.
   - Test Case 17: User provides additional information.

## Conclusion:

This test suite covers various equivalence classes for each input parameter of the AlignX career guidance questionnaire. By testing representative values from each class, we ensure that the questionnaire handles different inputs appropriately and behaves as expected. Additional test cases can be added as needed to further validate the functionality of the questionnaire.

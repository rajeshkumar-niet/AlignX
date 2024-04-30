### Software Design Document (SDD) for AlignX

#### 1. Introduction
AlignX is a digital platform designed to provide personalized career guidance through interactive career coaching based on personal interests, skills, and educational background.

#### 2. Objectives
- Provide personalized career recommendations tailored to individual profiles.
- Offer interactive roadmaps outlining steps for users to pursue their recommended career paths.
- Provide access to curated study resources to support career exploration and development.
- Incorporate a feedback mechanism for continuous improvement of the platform.

#### 3. Object and Class Diagram
```
+------------------+        +--------------------+
|      User        |        |  Questionnaire     |
+------------------+        +--------------------+
| - userId         |        | - Question ID      |
| - username       |        | - Question Text    |
| - email          |        | - Answer Options   |
| - interests      |        | - User Response    |
| - skills         |        |                    |
| - careerGoals    |        |                    |
|                  |        |                    |
+------------------+        +--------------------+
         |                            |
         |                            |
         |                            |
         |                            |
         |                            |
+------------------+        +---------------------+
| Recommendation   |        |     Roadmap         |
+------------------+        +---------------------+
| - Recommen ID    |        | - Roadmap ID        |
| - Career Path    |        | - Career Path       |
| - ConfidenceScore|        | - Education Steps   |
| - Rationale      |        | - Skill Steps       |
|                  |        | - Opportunities     |
|                  |        |                     |
+------------------+        +---------------------+
          |                          |
          |                          |
          |                          |
          |                          |
          |                          |
          |                          |
+------------------+        +---------------------+
|   Resource       |        |    Feedback         |
+------------------+        +---------------------+
| - Resource ID    |        | - Feedback ID       |
| - Resource Type  |        | - User Responce     |
| - Title          |        | - Description       |
| - Description    |        |                     |
|                  |        |                     |
+------------------+        +---------------------+
```

#### 4. Class Descriptions

1. **User**
   - Attributes:
     - userId: int
     - username: string
     - email: string
     - interests: list of strings
     - skills: list of strings
     - careerGoals: list of strings

2. **Questionnaire**
   - Responsibilities:
     - Start Questionnaire
     - Display Question
     - Analyze Responses

3. **Recommendation**
   - Responsibilities:
     - Generate Recommendation

4. **Roadmap**
   - Responsibilities:
     - View Roadmap

5. **Resource**
   - Responsibilities:
     - Access Resource

6. **Feedback**
   - Responsibilities:
     - Provide Feedback

#### 5. Conclusion
The Object and Class diagram for AlignX provides a visual representation of the main components and their interactions within the system. By leveraging these components, AlignX aims to provide personalized career guidance and support to its users.

**Interaction diagram** for the AlignX system as described in the Software Design Document (SDD).

### Sequence Diagram
```
User --> Questionnaire: Start Questionnaire
Questionnaire --> User: Display Question
User --> Questionnaire: Answer Question
Questionnaire --> Analytics: Analyze Responses
Analytics --> Recommendation: Generate Recommendation
Recommendation --> User: Display Recommendation
User --> Roadmap: View Roadmap
Roadmap --> Resource: Access Resource
User --> Feedback: Provide Feedback
Feedback --> AlignX: Submit Feedback
```

### Collaboration Diagram
```
                  +------------------+
                  |      User        |
                  +------------------+
                         |   |
                         |   |
               +------------------+
               |  Questionnaire   |
               +------------------+
                     |     |
                     |     |
+------------------+ |     | +------------------+
|    Recommendation| |     | |     Roadmap      |
+------------------+ |     | +------------------+
                     |     |          |
                     |     |          |
               +------------------+   |
               |   Analytics       |  |
               +------------------+   |
                           |          |
                           |          |
                    +------------------+
                    |    Feedback      |
                    +------------------+
```

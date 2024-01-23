# Hot Dog Survey Data

Tasks: 

- In this README file, briefly describe the project. 
- Create a separate markdown file as a data dictionary. Look at examples from last terms.

### Data File
See file DS-4002-Survey-Results.csv

### Data Dictionary
| Column| Description| Potential Reponses|                   
|-------|------------|-------------------|
| Timestamp | indicates the month/day/year and hour, minute, and second that the responder completed the survey |month/day/year, hour:minute:second|
| Sandwich| Answers the question: Is a hot dog a sandwich?| "Yes" indicates that the responder believes that a hot dog is a sandwich, "No" indicates that the responder believes that a hot dog is not a sandwich |
| Rationale question| Question about why yes or no| any string containing a valid email address|
|Enrollment question| question intended to get participants information if they are currently enrolled at the university of virginia | yes/no |
| study| indicates field of study|any string containing a field of study |

Note: when participants filled out the survey, there was an optional short-response question titled "Gimme a hot take". This feature was removed due to spicy comments

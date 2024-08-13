# Smart-Survey-Builder-Automated-Question-Classification-and-Quality-Control

## Methodology:
1. Dataset Generation: Used GPT-4.0 to create a diverse dataset of survey questions 
categorized into multiple types (e.g., open-ended, multiple-choice, rating scale).
2. Question Classification: Implemented an attention-based LSTM model to automatically 
categorize questions. Explored other models including MultinomialNB, Logistic Regression, 
Random Forest, SVM, and CNN for comparison.
3. Quality Assurance:
• Grammar Correction: Utilized a T5-based model for text refinement.
• Tone Analysis: Employed a DistilRoBERTa-based model for emotion classification.
• Profanity Detection: Integrated the better_profanity library to identify and censor 
inappropriate language.
• Gibberish Detection: Implemented to filter out nonsensical content.
4. Spam and Phishing Detection: Developed a BERT-based model to filter out unwanted or 
malicious content.
5. Automated Question Generation: Integrated the Mixtral-8x7b-32768 model using the Groq 
API to generate survey questions based on user prompts.

## Key Findings:
1. The attention-based LSTM model showed superior performance in question classification 
compared to traditional machine learning approaches.
2. Integration of multiple NLP techniques (grammar correction, tone analysis, profanity 
detection) significantly improved the quality and appropriateness of survey questions.
3. The BERT-based spam detection model effectively filtered out potentially harmful content.
4. Automated question generation using the Mixtral model provided a flexible and efficient way 
to create diverse survey questions.

## Recommendations:
1. Continue refining the question classification model, potentially exploring more advanced 
architectures or ensemble methods to further improve accuracy.
2. Enhance the quality assurance pipeline by incorporating more sophisticated gibberish 
detection algorithms and expanding the profanity detection capabilities.
2
3. Regularly update and retrain the spam detection model to adapt to evolving spam and 
phishing tactics.
4. Implement user feedback mechanisms to continuously improve the automated question 
generation feature.
5. Develop a user-friendly interface to make the Smart Survey Builder accessible to nontechnical users.
6. Consider integrating additional features such as survey logic design and response analysis 
tools to create a more comprehensive survey management system.
7. Conduct extensive user testing and gather feedback from survey professionals to identify 
areas for improvement and new feature development.
The Smart Survey Builder project demonstrates significant potential in automating and 
enhancing the survey creation process. By leveraging advanced AI and NLP techniques, it offers 
a powerful solution for creating high-quality, appropriate, and spam-free surveys while 
significantly reducing manual effort

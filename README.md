# TextbookQG- Adaptive Automatic Question Generation System
This project addresses the underutilization of textbooks in modern education, despite their comprehensive content that holds a wealth of knowledge essential for exceling in various subjects. Recognizing the challenges posed by traditional textbooks, which often lead to passive learning and low student engagement, this project presents TextbookQG– an innovative Automatic Question Generation (AQG) system designed to enhance textbook interactivity. The system has three primary objectives: to develop an Adaptive AQG system that generates multiple-choice questions targeting key concepts in digital textbooks, to integrate an adaptive learning model that provides a personalized learning experience, and to evaluate the system's effectiveness in generating high-quality questions and adapting to learners' needs. The system's workflow involves extracting and processing textbook PDF content, identifying important content, and using six question generators tailored to different difficulty levels to generate diverse questions. The system also includes an adaptive learning component that adjusts the difficulty of subsequent questions based on a user's previous responses, ensuring that users are consistently challenged at an appropriate level. Overall, the TextbookQG system contributes to educational technology by providing a scalable tool adaptable to different subjects and educational levels, promoting a more interactive and effective learning environment
## TextbookQG System Overview  
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/21217b71-4c69-4e46-b192-85dcbcf663f3)
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/c0defa1d-a9b1-481e-9870-13558585fdcc)
## Individual Components System Architecture
### PDF Extractor
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/6146829d-12ab-48b5-941a-8fec644c0929)

### Keyword Generator
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/8fb3a6c4-2437-4340-962c-1db272242514)

### Sentence Extractor
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/d35366af-a49b-405b-abd1-bf98dfa50ee8)

### MCQ Generation
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/76e089c5-ef51-4fd9-b241-cddb5e6890f4)

### Question Generator Training Pipeline
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/d329e4b9-a2f6-4ef6-8dec-52981e946abf)

### Adaptive Learning System
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/d82097e1-b8fc-4467-99bd-71894bd7c548)

### User Interface Use Case Diagram
![image](https://github.com/xtGitCode/TextbookQG-system/assets/103571608/19d98388-b95a-48ed-873f-e2831d649130)

## Conclusion (Limitations + Future Directions)
The development of the TextbookQG system represents a significant stride towards integrating adaptive question generation technologies with educational textbooks. However, reflecting on the project, several limitations have been identified that could guide future improvements. 
Currently, it relies on manually identifying tables of contents in PDFs, restricting its ability to handle diverse textbook formats. Additionally, the generated questions sometimes lack variety and exhibit inaccuracies in difficulty level classification. The adaptive learning component also updates user ability estimates based solely on the latest response, failing to account for overall performance patterns. 
To overcome these challenges, future developments aim to enhance PDF processing capabilities by adopting techniques like bipartite graph matching for automatic section recognition across formats. Training question generation models on other datasets and expanding to different question types like fill-in-the-blank and true/false are expected to improve question variety and difficulty alignment. Furthermore, incorporating a Bayesian network approach for adaptive learning, which considers multiple factors and probabilistic relationships, is envisioned to provide more nuanced and personalized adaptations based on comprehensive learning patterns. 
These future directions aim not only to address the current limitations of the TextbookQG system but also to expand its capabilities, making it a more versatile and powerful tool in the realm of educational technology. Through continuous development and integration of advanced technologies, the TextbookQG system is poised to significantly enhance the way students interact with and learn from textbooks



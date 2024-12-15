# CS59200-DashGPT
Within this repository, the team was able to create an application that was able to collect the metrics of a car (speed, acceleration & location). In addition, a Video Question and Answer (VQA) was created/designed through the use of the VILA model. This was utilized to provide users personalized responses to specific video clips (of lengths 30-60 seconds) pretaining to the users driving, and methods to possibly improve. Lastly, a VQA was also created/designed in order to provide users personalized responses to images inputted by the user pretaining to the users driving, and methods to possibly improve. 

For the VILA model, the following files were added to run the modified variation for user driving was the following:
-Under the VILA-main\scripts\v1_5\eval\video_chatgpt, a shell script of run_qa_custom.sh was included
-Under the VILA-main\scripts\v1_5\eval\video_chatgpt\GPT_Zero_Shot_QA, a file for CUSTOM_Zero_Shot_QA was included that allowed users to import their own videos, as well as the users specific questions and provide an assumed answer by the user.

# alexa-skill-Hellohvcs
## Description
Amazon Alexa Skill HVCS is a voice-enabled assistant that offers concierge services for the Hudson Valley region. It helps users access personalized services such as recommendations, bookings, and more via Alexa-enabled devices.

## Features
- Provides personalized concierge services.
- Integrates seamlessly with Amazon Alexa devices.
- Supports multiple functionalities, such as:
  - Recommendations for local services.
  - Voice-enabled scheduling and booking.
  - Friendly and intuitive voice interactions.
    
## Installation
1.Navigate to the lambda folder and install required dependencies:
2.Clone the repository:
3.Deploy the lambda_function.py to your AWS Lambda function
4.The interactionModel.json to configure your skill in the Alexa Developer Console.

##Usage
Invoke the skill by saying: "Alexa, open HVCS".
Follow the prompts to access concierge services.
Example commands:
"What are the best restaurants nearby?"
"Can you help me book a taxi?"

##Project Structure
- `lambda/lambda_function.py`: Main Lambda function code.
- `lambda/utils.py`: Utility functions for handling user requests.
- `assets/`: Contains skill icon images and other resources.
- `interactionModel/interactionModel.json`: The interaction model for Alexa.
- `requirements.txt`: Python dependencies.
- `README.md`: Project documentation.
  
## Technologies Used
- **Amazon Alexa Developer Console**: For creating and managing the skill.
- **AWS Lambda**: Backend serverless function for skill logic.
- **Python**: Programming language for the Lambda function.
- **JSON**: For interaction model configuration.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
## Contact
Created by [Navi Reddy](https://github.com/NaviReddy369). Feel free to reach out at gudimillanveen@gmail.com for any questions or suggestions.

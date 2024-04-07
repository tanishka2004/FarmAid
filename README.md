### FarmAid: AI Chat Helper for Indian Farmers

FarmAid is an AI-powered chat helper designed to assist Indian farmers with a range of agricultural challenges. Whether it's crop management, weather updates, market insights, or accessing government schemes, FarmAid aims to provide farmers with a reliable and accessible solution.

### Features

- **Text and Voice Input**: Farmers can interact with FarmAid using both text and voice inputs, ensuring accessibility for users with varying levels of literacy.
  
- **Crop Management**: Get real-time information on crop diseases, pest control, and optimal planting techniques.
  
- **Weather Updates**: Receive accurate weather forecasts and recommendations for crop management based on upcoming weather conditions.
  
- **Market Insights**: Access current market prices and trends to make informed decisions about selling produce.
  
- **Government Schemes**: Stay informed about government agricultural schemes and subsidies that farmers may qualify for.
  
- **Personalized Advice**: Utilizes the Gen AI API to generate personalized agricultural advice tailored to the specific needs and farming practices of each user.

### Technologies Used

- Flask
- React.js
- Dialogflow API (for natural language processing)
- Google Cloud Speech-to-Text API (for voice input)
- Google Cloud Text-to-Speech API (for voice output)
- Gen AI API (for generating personalized agricultural advice)
- HTML/CSS
- JavaScript
- Python
- Git for version control
- Heroku for deployment

### Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/YourUsername/FarmAid.git
   cd FarmAid
   ```

2. Install dependencies:
   ```bash
   # For backend
   cd backend
   pip install -r requirements.txt
   
   # For frontend
   cd frontend
   npm install
   ```

3. Set up API keys:
   - Obtain API keys for Dialogflow, Google Cloud Speech-to-Text, Google Cloud Text-to-Speech, and Gen AI API.
   - Add these keys to the respective environment files (`.env`) in the `backend` directory.

4. Start the backend server:
   ```bash
   # Inside the 'backend' directory
   flask run
   ```

5. Start the frontend server:
   ```bash
   # Inside the 'frontend' directory
   npm start
   ```

6. Open your browser and navigate to `http://localhost:3000` to use FarmAid.

### Contributors

- John Doe
- Jane Smith

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgements

- Special thanks to the Devfolio Hackathon for providing the platform to develop this project.
- We acknowledge the invaluable resources and APIs provided by Google Cloud, Gen AI, and Dialogflow.
  
### Feedback and Support

If you have any feedback, suggestions, or issues with FarmAid, please reach out to us at [farmaid@example.com](mailto:farmaid@example.com). Your input helps us improve this tool for the benefit of Indian farmers.

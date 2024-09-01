# Llama2 Model Selector

## Live Website
Check out the live demo of the application [here]([http://your-live-website-link.com](https://basic-chatbot-wc855dddg3pc2dhdwywq2r.streamlit.app/]).


## Description
The Llama2 Model Selector is a powerful and user-friendly Streamlit application designed to facilitate seamless interaction with advanced Llama2 models for text generation. This application allows users to select between different Llama2 models, specifically the Llama2-7B and Llama2-13B variants, and fine-tune various parameters to optimize the text generation process according to their needs.

With an intuitive interface, users can easily adjust parameters such as temperature, top_p, and max_length to control the creativity and coherence of the generated text. The application also features a chat interface where users can input their prompts and receive responses from the selected model in real-time. Additionally, the chat history can be cleared with a single click, ensuring a fresh start for new interactions.


## Usage
1. Set the `REPLICATE_API_TOKEN` environment variable with your Replicate API token.
2. Run the Streamlit application:
    ```sh
    streamlit run app.py
    ```
3. Open your web browser and go to `http://localhost:8501` to access the application.

## Configuration
- **Model Selection**: Choose between 'Llama2-7B' and 'Llama2-13B' models.
- **Temperature**: Adjust the temperature parameter for text generation (range: 0.01 to 5.0).
- **Top_p**: Adjust the top_p parameter for text generation (range: 0.01 to 1.0).
- **Max Length**: Set the maximum length for generated text (range: 32 to 128).

## Features
- **Model Selection**: Easily switch between different Llama2 models.
- **Parameter Adjustment**: Fine-tune the model parameters using sliders.
- **Chat Interface**: Interact with the model through a chat interface.
- **Clear Chat History**: Clear the chat history with a single click.

## Contributing
1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature/your-feature-name
    ```
3. Make your changes and commit them:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/your-feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the MIT License.

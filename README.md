# Voice-to-Image-Generator
An innovative application that leverages advanced technologies to transform spoken words into stunning visual representations. It is built using Python and an Open Source library Gradio, integrated with the OpenAI API with DALL-E for image generation.

## Features

- Transcribe spoken words from audio input.
- Summarize transcribed text using ChatGPT.
- Generate images using DALL-E based on the ChatGPT summary.


https://github.com/Ishan1440/Voice-to-Image-Generator/assets/113188276/7e0d2c59-a410-4470-95ff-8f300e75ea2e


## How to Use

1. Clone this repository to your local machine.

2. Make sure you have Python installed on your system.

3. Install the required dependencies:

   ```
   pip install gradio openai
   ```
   - For Audio Support, Please install `ffmpeg` in your system to use non-WAV audio file formats and make sure `ffprobe` is in your PATH.

4. Set up your OpenAI API key:

   - Sign up for an OpenAI account and create an API key.
   - Replace `"YourAPIkey"` in the `openai.api_key` line with your actual API key.

5. Run the application:

   ```
   python your_app_name.py
   ```

   Replace `your_app_name.py` with the name of your Python script.

6. The application will launch and allow you to record audio through your microphone.

7. Speak your desired text.

8. The application will transcribe your speech, summarize it using ChatGPT, and generate an image using DALL-E based on the summary.

9. The transcribed text and generated image will be displayed.

## Dependencies

- [Gradio](https://gradio.app/): Gradio is an easy-to-use Python library for creating web interfaces for your machine learning models. It is used here to build the user interface and handle audio input/output.
- [OpenAI](https://beta.openai.com/): OpenAI provides state-of-the-art language and image generation models, including ChatGPT and DALL-E. You need an OpenAI API key to access these models.

## Configuration

Make sure to configure your OpenAI API key in the script to enable access to the ChatGPT and DALL-E models.

```python
openai.api_key = "YourAPIkey"
```

Replace `"YourAPIkey"` with your actual OpenAI API key.

## Contributing

If you'd like to contribute to this project, feel free to fork the repository and submit a pull request with your improvements.

## Author

- [Your Name]

Enjoy using this application to transcribe speech, summarize text, and generate images with ease!

# PitchPerfect

Welcome to the PitchPerfect application! This AI-powered application utilizes stable diffusion and LLMs to generate customizable presentations similar to Tome. With the PitchPerfect, you can create unique and personalized presentations with ease.

#### Note:
The current version of the app uses the `openai` API, but version 2 will incorporate open-source models once we address the following challenges:
1. Utilizing a large model without encountering memory issues on Colab.
2. Identifying a smaller model that can generate satisfactory content.

## Usage

To use the PitchPerfect, you have two options:

### Option 1: GitHub Repository

To utilize the PitchPerfect, follow these steps:

1. Clone the repository from GitHub using this command:
   ```
   git clone https://github.com/manavukani/pitch-perfect.git
   ```

3. Set up a virtual environment:
   ```
   python -m venv env
   env\Scripts\activate
   ```

4. Download wkhtmltopdf
   
   For Linux
   ```
    apt-get update  
    apt-get -y install wkhtmltopdf
   ```
   For other OS checkout: https://wkhtmltopdf.org/downloads.html

   Note: `wkhtmltopdf` may not work well in Windows so try running it in `docker` container.

5. Install the required dependencies using `pip`:
   ```
   pip install -r requirements.txt
   ```

6. Once the dependencies are installed, run the PitchPerfect using the `main.ipynb` file.

## Other Files
`api.py`: Flask app that exposes API endpoints for the PitchPerfect application.

`Dockerfile`: Can be used to deploy the `api.py` file.

## License

The PitchPerfect application is licensed under the [MIT License](LICENSE). By using this application, you agree to comply with the terms and conditions stated in the license.

## Issues & Improvements

If you have any questions, feedback, or suggestions regarding the PitchPerfect application, please create a [GitHub issue](https://github.com/manavukani/pitch-perfect/issues) with the `deck-generator` tag, along with other relevant tags.

We appreciate your interest and support in creating presentations with the PitchPerfect!

Happy presentation generation!

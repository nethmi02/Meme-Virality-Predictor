# Meme-Virality-Predictor

## Running the Application

1. Install required packages:
```bash
pip install -r requirements.txt
```

2. Make sure you have the following files in your directory:
   - `memesChecker.py` (main application file)
   - `memes.json` (data file)

3. Run the Streamlit application:
```bash
streamlit run memesChecker.py
```

4. The application will open in your default web browser at `http://localhost:8501`

## Using the Application

1. Enter your meme title in the text area
2. Use the slider to select posting hour (0-23)
3. Click "Predict" to get:
   - Virality prediction
   - Probability score
   - Improvement suggestions if the meme is predicted to be not viral

## Troubleshooting

If you encounter any errors:
1. Ensure all required packages are installed
2. Check that `memes.json` is in the same directory as `memesChecker.py`
3. Make sure you have proper permissions to read/write files in the directory
4. Check if port 8501 is available (Streamlit's default port)

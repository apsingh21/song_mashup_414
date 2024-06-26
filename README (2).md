# Mashup-Maker

This web application, developed using Streamlit, enables users to generate mashups of YouTube videos effortlessly. Users can input the artist's name, determine the number of clips desired, set the duration for each clip, and specify the output filename. The application seamlessly retrieves videos from YouTube based on the artist's name, proceeds to download and process the clips accordingly, and finally merges them into a unified mashup audio file.


## How to Run

1. Clone the repository:

```
git clone https://github.com/aparna21/Song-Mashup-Creator.git
```

2. Navigate to the project directory:

```
cd Song-Mashup-Creator
```

3. Install the dependencies:

```
pip install -r requirements.txt
```

4. Run the Streamlit application:

```
streamlit run app.py
```

5. Access the application in your web browser by visiting [http://localhost:8501](http://localhost:8501).

## Usage

1. Enter the artist's name, number of clips, duration per clip, and the output filename.
2. Click on the "Create Mashup" button and wait.
3. Once the mashup is created successfully, a "Download Mashup" button will appear. Click on it to download the mashup audio file.

## Example

![image](https://github.com/arnavroh45/Song-Mashup-Creator/assets/58484869/067af8e7-59c7-45bf-8c5e-907bfd464dd3)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

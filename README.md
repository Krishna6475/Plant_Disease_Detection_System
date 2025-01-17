# Plant_Disease_Detection_System_for_Sustainable_Agriculture

This project is a machine learning-based web application designed to identify plant diseases using image classification. The system supports sustainable agriculture by enabling early detection and diagnosis of plant diseases, thus helping to optimize crop health and yield.

## Key Features
- **User-Friendly Interface**: Built with Streamlit, the app provides an intuitive interface for uploading and analyzing plant images.
- **Deep Learning Model**: Utilizes a TensorFlow-based Convolutional Neural Network (CNN) trained on a dataset of plant disease images.
- **Comprehensive Disease Recognition**: Capable of identifying multiple plant diseases across various crops, including apples, tomatoes, and grapes.
- **Real-Time Predictions**: Provides instant results, classifying the input image into one of the pre-defined disease categories.

## Workflow
1. Upload an image of a plant leaf through the app.
2. The model processes the image and predicts the disease class.
3. The result is displayed along with the corresponding disease label.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/Krishna6475/Plant_Disease_Detection_System
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the application:
   ```bash
   streamlit run main.py

## Dataset
The model is trained on the PlantVillage Dataset, which includes images of healthy and diseased plant leaves across various species.

## Future Enhancements
- Extend the model to detect more diseases.
- Integrate with IoT devices for real-time field monitoring.
- Add multilingual support for broader accessibility.

## License
This project is open-source and available under the MIT License.







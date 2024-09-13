# Iris_Flower_Species_Prediction

Here's a sample README for your Iris flower species prediction project on GitHub:

---

# Iris Flower Species Prediction

This project predicts the species of the Iris flower (Setosa, Versicolor, Virginica) using a machine learning model trained on the famous Iris dataset. The prediction is based on four input features: sepal length, sepal width, petal length, and petal width. The project is implemented in Python using the `sklearn` library and SVM (Support Vector Machine) algorithm.

## Features

- **Machine Learning Model**: Built using Support Vector Machine (SVM) from the `scikit-learn` library.
- **Prediction Interface**: A user-friendly web interface created with Gradio allows users to input flower dimensions and get the species prediction along with the flower's image.
- **Error Handling**: Ensures input values are within a valid range (0 to 7) for sepal and petal dimensions, displaying an error message for invalid inputs.

## Dataset

The Iris dataset consists of 150 samples, with 50 samples each for three species of Iris flowers:
- Iris Setosa
- Iris Versicolor
- Iris Virginica

Each sample includes four features:
- **Sepal Length** (cm)
- **Sepal Width** (cm)
- **Petal Length** (cm)
- **Petal Width** (cm)

## Model Training

- **Algorithm**: Support Vector Machine (SVM) is used for training.
- **Training Process**: The model is trained on 80% of the dataset, with the remaining 20% used for testing.
- **Accuracy**: The model achieves high accuracy on the test set, effectively distinguishing between the three Iris species.

## Web Interface

The web interface is built using [Gradio](https://www.gradio.app/), allowing users to:
- Enter sepal and petal dimensions.
- Get the predicted species and view an image of the corresponding Iris flower.

## Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/iris-flower-prediction.git
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch the application:

   ```bash
   python app.py
   ```

4. Access the interface in your browser.

## Screenshots

_Add screenshots of the Gradio interface showing the input fields and predicted results._

## Future Enhancements

- Add more advanced models like Random Forest or Neural Networks.
- Improve the UI with additional features like data visualization.

## License

This project is licensed under the MIT License.

---

Let me know if you'd like to modify anything!

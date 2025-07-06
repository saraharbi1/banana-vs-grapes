# Banana-Grapes Classifier (Teachable Machine)

This project uses a machine learning model trained with [Teachable Machine by Google](https://teachablemachine.withgoogle.com/train/image) to classify images of **Bananas** and **Grapes**.

## Project Files

| File Name               | Description                                                              |
|-------------------------|--------------------------------------------------------------------------|
| `keras_model.h5`        | The trained model exported from Teachable Machine                        |
| `labels.txt`            | Contains the class labels: "Banana" and "Grapes"                         |
| `BananaAndGrapes.ipynb` | Google Colab notebook used to test the model                             |
| `banana test.jpg`       | Sample image used for testing the model                                  |
| `screenshot.png`        | Screenshot showing the model's prediction result                         |

## Model Details

- **Platform Used**: [Teachable Machine](https://teachablemachine.withgoogle.com/train/image)
- **Number of images used for training**:
  - Banana: 5 images
  - Grapes: 5 images

## How to Run the Model on Google Colab

1. Open the `BananaAndGrapes.ipynb` file in Google Colab.
2. Upload the following files:
   - `keras_model.h5`
   - `labels.txt`
   - A test image (e.g., `banana test.jpg`)
3. Run all the code cells:
   - Load the model
   - Preprocess the test image
   - Run the prediction

4. The predicted class and confidence score will appear:
   - Predicted class: Banana
  

## Example

- **Test Image**: ![test banana](https://github.com/user-attachments/assets/0637f7f5-53ad-4c1f-ba4d-937689d3537b)
- **after test in model**![لقطة شاشة 2025-07-06 235540](https://github.com/user-attachments/assets/4ee53816-b32d-496a-9f93-73e814301fd4)

- **output after test in google colab**: ![لقطة شاشة 2025-07-07 000228](https://github.com/user-attachments/assets/f65a1060-518b-4fc1-a233-b63a1f3ba129)




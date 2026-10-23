## Interactive demo
Draw a digit with the mouse inside Colab and the model predicts it instantly.

<img width="792" height="493" alt="Screenshot 2026-10-23 232006" src="https://github.com/user-attachments/assets/340f22e5-a52d-45ec-bbb9-cf8b69ef3e67" />


Before prediction, the drawing is cropped, scaled to fit a 20×20 box and centered
on a 28×28 canvas, exactly like the MNIST images.

## Limitations
- The model only knows digits 0–9, so any other shape is forced into one of them.
- Confidence (softmax) can be very high even when the prediction is wrong.
- Digits drawn very differently from MNIST style may be misclassified.

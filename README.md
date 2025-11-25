# Emotion-Detection-from-Speech
This project is a simple Deep Learning model that detects basic human emotions from speech. It automatically creates a small dummy audio dataset, trains an LSTM model, and predicts emotions such as happy, sad, angry, and neutral. The output also includes a matching emoji so the emotion becomes easy to understand visually.

The program begins by generating synthetic audio files using different frequencies. Each emotion has its own tone, allowing the model to learn patterns even without a real dataset. This makes the project easy for beginners and useful for demonstrations or small academic assignments.

After creating the dataset, the system extracts MFCC features from the audio. MFCCs are commonly used features in speech recognition because they capture important information from the sound. These features are then fed into an LSTM-based neural network, which learns to classify the emotions.

During training, the project also produces graphs for accuracy and loss. These plots help you see how well the model is learning over time. A confusion matrix is also created to show the correct and incorrect predictions.

Finally, the model can predict the emotion of any WAV file in the folder. The prediction includes both the emotion label and the corresponding emoji, making the output simple and user-friendly. This project is ideal for beginners who want to understand speech processing, deep learning, and emotion detection in a very easy and fun way.

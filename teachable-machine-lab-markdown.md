# Lab 5 Notes: Coding with Google Teachable Machine

## Introduction & Getting Started

### What is Teachable Machine?

A no-code tool from Google that lets you create machine learning models using your own images, sounds, or poses. Train your model in the browser, then export it to use in your projects. Ideal for beginners and those who want to experiment with machine learning quickly.

### Key Concepts:

- **Classes:** The categories you want the machine to recognize.
- **Samples:** Examples of each class used for training.
- **Training:** Teaching the model to identify patterns.
- **Testing:** Checking how well the model performs on new examples.
- **Model:** The trained algorithm for making predictions.

### Getting Started:

1. Go to https://teachablemachine.withgoogle.com/.
2. Choose your project type (Image, Audio, or Pose)

   **NOTE:** You WILL be recording your own data. If your camera does not work/you do not want to use your camera, remember you can use data samples from online. Get creative! Attached are some common examples you can get inspired from:
   - Upload photos of dogs and cats to have the machine learn how to identify dogs vs cats
   - Upload photos of different fingers and have the model identify which finger is index, pinky, thumb, etc.
   - Train the model to identify EDM music as oppose to rap
   - Train the model to identify a squat pose from a standing pose
   - Use ChatGPT to get you started with a prompt! 
4. Add classes and collect samples for each class. **Create at least two different classes**

   Classes typically range from two comparitors;
   - human vs vehicle class
   - classical music vs modern pop music class
   - etc.
## Training, Testing, & Exporting Your Model

### Training:

1. Click "Train Model."
2. Observe the training accuracy.

### Testing:

1. Use "Preview" mode with new input.
2. Adjust and retrain if necessary.

### Exporting:

1. Click "Export Model" and choose your format:
    - TensorFlow.js (web applications)
    - SavedModel (TensorFlow tools)
    - Upload to Teachable Machine (sharing)
    - Download as code (integration)

2. Integrate into your project:
    - TensorFlow.js: Use in your browser.
    - SavedModel/Code: Load and run with TensorFlow.
    - Upload: Get a shareable link.
  
### Present Your Model To Your Lab Techs for Full Credit

### Optional Tasks (Integrating Exported Model):

- **Web Integration:** Create a simple webpage that uses your TensorFlow.js model to classify images or sounds in real-time using the user's webcam or microphone. Both CodePen and Glitch (https://glitch.com/) are good options for testing your browser-based app online. https://ramicetty.github.io/blog/browser-based-models-with-tensorflow-js/
- **Mobile App:** If you're familiar with mobile development, try integrating the model into a simple Android or iOS app.
- **Raspberry Pi Project:** Use the model on a Raspberry Pi to build a smart device that reacts to different sounds or images.
- **Game Development:** Incorporate the model into a game where player actions trigger different events based on pose classification or sound recognition.

### Tips and Tricks:

- Include diverse samples and use data augmentation.
- Experiment with different model architectures and settings.

### Additional Resources:

- Teachable Machine documentation: https://teachablemachine.withgoogle.com/
- TensorFlow.js tutorials: https://www.tensorflow.org/js/tutorials


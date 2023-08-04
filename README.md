# eHealth

eHealth has 4 main uses. The first one is a health assistant, which is the app's focus. It provides on-the-go medical information which you can access. The second part is a voice assistant, which was mainly added so that you can entirely rely on eHealth, instead of relying on other sources such as Siri or Google Home. The third is a virtual keyboard, where you can type using a window on your computer, by simply putting your index and middle finger together in front of a webcam. The fourth is a virtual mouse, where you can move your cursor using a window on your computer. You can move your mouse using your pointer finger and click by moving your thumb out. Both the virtual keyboard and the virtual mouse work outside of the application. The health assistant uses an intents.json file to read data and then uses the module NLTK to stem the words inputted; then, the application utilizes a neural network and machine learning algorithms to convert your inputted string to a probability of it being a specific tag which is read in the intents.json file. If the probability is high enough, it returns an answer to your question. The voice assistant is almost the same, except it uses deep speech to understand what you are saying, and then converts it to a string. The virtual mouse and keyboard both use media pipe and OpenCV to scan the webcam for the indexes of your fingers (photo provided in the demo video), and, for the mouse, upscales the camera intake and uses the pointer finger's top index as the center of the cursor. To log in to eHealth, there is a facial recognition system using machine learning that is stored in an Encodings.p file which also stores data such as login attempts in Google Firebase. Overall, eHealth uses AI, machine learning, deep speech, and neural networks to function.

## Acknowledgements

 - [NLTK](https://github.com/nltk/nltk)
 - [TensorFlow](https://github.com/tensorflow/tensorflow)
 - [OpenCV](https://github.com/opencv/opencv)
 - [Face Recognition](https://github.com/ageitgey/face_recognition)

## Authors

- [@rishih](https://www.github.com/Rishi-prog731)


## Contributing

Please adhere to this project's `contribution instructions`.

See `CONTRIBUTING.md` for the contribution instructions.

Please adhere to this project's `code of conduct`.

See `CODE_OF_CONDUCT.md` for the code of conduct.

## Demo

https://www.youtube.com/watch?v=JVKAMiwoprI  


## Utilizes

- Machine Learning
- AI
- Recognition Software
- Deep Learning


## Feedback

If you have any feedback, please reach out to us at rishi.hhp@gmail.com


## License

[MIT](https://choosealicense.com/licenses/mit/)


## Run Locally

Clone the project

```bash
  git clone https://github.com/Rishi-prog731/eHealth.git
```

Go to the project directory

```bash
  cd eHealth
```

Install dependencies

```bash
  pip install opencv
  pip install tensorflow
  pip intall nltk
  pip install pyaudio 
  Look in requirements.txt for additional important pip installations
```

Start files

```bash
  python fileName.py
```

## Slite

https://rishihariharaprasad.slite.page/p/mgBFn1AsE2KQoP/eHealth-Project-Outline

## Open Source

Currently, the code for eHealth isn't public. I am just using this repository as an archive for working TensorFlow models. I will eventually publish eHealth's full program code in this repo.
## Support

For support, email rishi.hhp@gmail.com


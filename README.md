![314F89CD-0B77-4DB7-8157-A5037EFFA651](https://github.com/user-attachments/assets/a4b5d50f-386c-4478-96ff-c460bb62b8da)
# 🐾 CatNalyze

Final project for the Building AI course

## Summary

CatNalyze is an AI idea for analyzing cat photos, videos, or short notes to detect emotions, activities, or possible health issues. It helps cat owners better understand their pets through AI-supported pattern recognition.

## Background

Cat owners take pictures and videos of their pets all the time – sometimes out of joy, sometimes out of concern. But it’s often hard to tell if the cat is just resting or possibly in discomfort.

* Problem 1: Cats hide pain well – early signs of illness often go unnoticed.
* Problem 2: Emotional states like stress, boredom, or fear are difficult to interpret.
* Problem 3: There are hardly any accessible AI tools to help understand cat behavior.

**My motivation**: As a cat owner myself, I’d love a helpful tool that gives feedback – not a diagnosis – but gentle suggestions to increase awareness.

## How is it used?

Cat owners could upload a photo, a short video clip, or even write a brief note describing behavior. The AI would respond with something like:

* “This appears to be normal resting behavior.”
* “Unusual posture – monitor if it persists.”
* “Possible signs of discomfort.”

The app could be mobile or browser-based, with a focus on a simple user experience and a clear disclaimer that it’s not a replacement for veterinary advice.

<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

## Data sources and AI methods

* Data sources: Open datasets of cat images (e.g., Flickr CC, Kaggle pet datasets)
* AI methods:
  * Image recognition using Convolutional Neural Networks (CNNs)
  * Transfer learning with models like MobileNet or ResNet
  * Text classification for short user notes
* Community contributions could help label behavior patterns (e.g., “looks playful”, “seems anxious”).

## Challenges

* This AI cannot diagnose – it must only provide helpful suggestions.
* Emotions in animals are hard to measure objectively.
* Data quality and ethical use: only properly licensed and anonymized content can be used.
* Risk of misinterpretation or users relying too heavily on AI feedback.

## What next?

Future developments could include:

* Video analysis, not just still images
* Behavior tracking over time (e.g. daily routines)
* Expanding to other pets (e.g. dogs, rabbits)
* Partnerships with vets or animal behaviorists
* A fully featured app with a pet behavior journal

I’d need help with data cleaning, model training, and front-end design.

## Acknowledgments

* Inspired by my own cats and the daily questions they raise!
* Image credit: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* Project idea developed as part of the **Building AI** course by Reaktor and the University of Helsinki

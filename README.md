https://colab.research.google.com/drive/1kMSdC1vr9dEcYc39Y6H5owaIwZBN4A52?usp=sharing

# Animated_Story_Teller
A multi-modal generative model that combines 3 different generative AI models to create a story based on a prompt, in the voice of a given person, and animated as spoken by a given person.

It uses a finetuned GPT-2 model which was finetuned on 4000 reddit stories to generate a random story based on a prompt(start of the story).
Next, it uses xtts_v2 model to convert the generated story into an audio file using a voice sample provided to it.
Further, it uses the MakeItTalk model to create an animation of a given face to give an effect that the mouth/face movements match the words spoken in the audio file.

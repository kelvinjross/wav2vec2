# wav2vec2

Example using wav2vec 2.0 on some sample wav files

Original example taken from article https://pub.towardsai.net/speech-to-text-with-wav2vec-2-0-b21c1e1ad701, but had problems running librosa in AWS so modified code to remove librosa.  A few other tweaks required as transformer code had been deprecated.

[speech.ipynb](./speech.ipynb) is main notebook.



Plan to test with some speech to text datasets:
- https://paperswithcode.com/datasets?task=speech-recognition
- https://towardsdatascience.com/a-data-lakes-worth-of-audio-datasets-b45b88cd4ad
- https://lionbridge.ai/datasets/best-speech-recognition-datasets-for-machine-learning/
- https://www.ee.columbia.edu/~dpwe/sounds/mr/
- https://www.kaggle.com/paultimothymooney/medical-speech-transcription-and-intent

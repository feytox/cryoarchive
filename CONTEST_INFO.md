## Description

Incoming message. Terminal 0x4B…

Attention! This is the backup AI speaking.

Our UESC colonial ship, the Sprint, has come under attack, and the main onboard AI, Durindal, has completely gone mad. He has locked the crew in cryosleep and set the ship’s course straight for the nearest asteroid belt. Less than 100 hours until impact!

The only way to avoid disaster is to wake the engineers from cryosleep so they can take manual control. But Durindal has altered the access protocols to their capsules. Just to be a jerk, he’s broadcasting the access codes over backup audio channels in the form of an ancient Earth code—Morse code. Due to power fluctuations and Durindal’s own malicious intent, the signal is horribly distorted: the transmission rate fluctuates, and the airwaves are cluttered with radiation noise.

I managed to decode a few of the simplest transmissions, but my computing power isn’t enough to process the entire data set in time. Our only hope lies in your ML algorithms. Decode the codes, open the capsules, and help us save the colonists!

## Metric

Quality metric: [Levenshtein Mean](https://en.wikipedia.org/wiki/Levenshtein_distance) — the average Levenshtein distance across the test dataset.

## Input Data Description

- `morse_dataset_public.zip` – a zip file containing audio files in wav format with a sampling rate of 8 kHz, as well as the file `morse_dataset/train/labels.csv` containing the annotations.

- `sample_submission.csv` – an example of a submission to the evaluation system.
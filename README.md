# PureLens

**Snap a photo. Know if it's pure.**

PureLens checks whether a food is pure or adulterated from a single photo. Pick the food, take a photo, and get a verdict: **PURE** or **ADULTERATED**, with a confidence score and a one-line reason.

Built for the Meta Global AI Developer Hackathon (Push the Frontier).

## Foods supported
- Milk (water added)
- Haldi / turmeric powder (besan added)
- Laal mirchi / red chilli powder (brick powder added)

The app is built to handle any food. These three are trained and tested.

## How it works
1. **SAM** segments the photo and measures color, unevenness and particle features.
2. **Classifier** trained on my own photos gives the verdict (pure or adulterated).
3. **Muse Spark** explains the result in one line.

The verdict comes from the trained classifier, and Muse Spark only explains it.

## Data
All training photos were taken by me: same plate, light, background and top-down angle. Adulterated samples were made with safe stand-ins at 10%, 20% and 30%.

## Results
Tested on photos the model never saw during training:
- Milk: [X] / 5
- Haldi: [X] / 5
- Mirchi: [X] / 5

## Built during the hackathon
Everything in this repo was built between Oct 26 and Nov 4, 2026.

## Disclaimer
PureLens is a screening aid. It is not a lab test and not health advice.

## Run it
[Add setup steps once the app is built]

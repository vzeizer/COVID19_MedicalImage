# COVID-19 Medical Image Classification Using Transfer Learning

## Project Overview
This project demonstrates the application of advanced deep learning techniques to tackle a critical healthcare challenge: the automated classification of medical images for COVID-19 diagnosis. Using transfer learning approaches with state-of-the-art convolutional neural network architectures (ResNet, VGG16, and VGG19), this solution addresses the real-world constraints of limited data availability and class imbalance in medical imaging datasets.

## Technical Highlights
- **Transfer Learning Implementation**: Leveraged pre-trained models (ResNet, VGG16, VGG19) on ImageNet dataset, adapting them for medical image classification through strategic fine-tuning of specific layers
- **Imbalanced Dataset Handling**: Developed solutions for a significantly skewed dataset (about 1:8 ratio of normal to COVID-19 cases) using sampling and weighting techniques
- **Deep Learning Framework**: Utilized TensorFlow for model implementation, demonstrating proficiency in industry-standard deep learning tools
- **Medical Image Processing**: Applied specialized preprocessing techniques suitable for medical imaging data

## Challenge and Approach
The primary challenge in this project was developing a reliable classification model with a small, imbalanced dataset - a common scenario in medical imaging projects. Instead of training from scratch, which would require vast amounts of data, I implemented a transfer learning strategy that capitalizes on pre-trained models' feature extraction capabilities while fine-tuning specific layers for our medical imaging context.

## Skills Demonstrated
- Deep Learning Architecture Design
- Transfer Learning Implementation
- Medical Image Processing
- Handling Imbalanced Datasets
- TensorFlow/Keras Framework Proficiency
- Model Performance Optimization
- Healthcare AI Applications

## Impact and Applications
This project showcases the practical application of computer vision techniques in healthcare, demonstrating how deep learning can be effectively deployed even with limited data resources. The approach developed here can be extended to other medical imaging classification tasks where data scarcity and class imbalance are common challenges.


![logo](images/1_gender_dist.png)

![logo](images/2_gender_hist.png)

![logo](images/3_COVID_images.png)

![logo](images/4_target_valuecounts.png)

![logo](images/5_train_val.png)

![logo](images/6_confusionmatrix_metrics.png)

![logo](images/7_confusionmatrix.png)


# Contributor Covenant Code of Conduct

## Our Pledge

We as members, contributors, and leaders pledge to make participation in our
community a harassment-free experience for everyone, regardless of age, body
size, visible or invisible disability, ethnicity, sex characteristics, gender
identity and expression, level of experience, education, socio-economic status,
nationality, personal appearance, race, caste, color, religion, or sexual
identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming,
diverse, inclusive, and healthy community.

## Our Standards

Examples of behavior that contributes to a positive environment for our
community include:

* Demonstrating empathy and kindness toward other contributions that are not aligned with this Code of Conduct, and will communicate reasons for moderation decisions when appropriate.

## Scope

This Code of Conduct applies within all community spaces, and also applies when
an individual, or aggression toward or disparagement of classes of individuals.

**Consequence**: A permanent ban from any sort of public interaction within the
community.

## Attribution

This Code of Conduct is adapted from the [Contributor Covenant][homepage],
version 2.1, available at
[https://www.contributor-covenant.org/version/2/1/code_of_conduct.html][v2.1].

Community Impact Guidelines were inspired by
[Mozilla's code of conduct enforcement ladder][Mozilla CoC].

For answers to common questions about this code of conduct, see the FAQ at
[https://www.contributor-covenant.org/faq][FAQ]. Translations are available at
[https://www.contributor-covenant.org/translations][translations].

[homepage]: https://www.contributor-covenant.org
[v2.1]: https://www.contributor-covenant.org/version/2/1/code_of_conduct.html
[Mozilla CoC]: https://github.com/mozilla/diversity
[FAQ]: https://www.contributor-covenant.org/faq
[translations]: https://www.contributor-covenant.org/translations is officially representing the community in public spaces.
Examples of representing our community include using an official e-mail address,
posting via an official social media account, or acting as an appointed
representative at an online or offline event.

## Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be
reported to the community leaders responsible for enforcement at
[INSERT CONTACT METHOD].
All complaints will be reviewed and investigated promptly and fairly.

All community leaders are obligated to respect the privacy and security of the
reporter of any incident.

## Enforcement Guidelines

Community leaders will follow these Community Impact Guidelines in determining
the consequences for any action they deem in violation of this Code of Conduct:

### 1. Correction

**Community Impact**: Use of inappropriate language or other behavior deemed
unprofessional or unwelcome in the community.

**Consequence**: A private, written warning from community leaders, providing
clarity around the nature of the violation and an explanation of why the
behavior was inappropriate. A public apology may be requested.

### 2. Warning

**Community Impact**: A violation through a single incident or series of
actions.

**Consequence**: A warning with consequences for continued behavior. No
interaction with the people involved, including unsolicited interaction with
those enforcing the Code of Conduct, for a specified period of time. This
includes avoiding interactions in community spaces as well as external channels
like social media. Violating these terms may lead to a temporary or permanent
ban.

### 3. Temporary Ban

**Community Impact**: A serious violation of community standards, including
sustained inappropriate behavior.

**Consequence**: A temporary ban from any sort of interaction or public
communication with the community for a specified period of time. No public or
private interaction with the people involved, including unsolicited interaction
with those enforcing the Code of Conduct, is allowed during this period.
Violating these terms may lead to a permanent ban.

### 4. Permanent Ban

**Community Impact**: Demonstrating a pattern of violation of community
standards, including sustained inappropriate behavior, harassment of an
individual people
* Being respectful of differing opinions, viewpoints, and experiences
* Giving and gracefully accepting constructive feedback
* Accepting responsibility and apologizing to those affected by our mistakes,
  and learning from the experience
* Focusing on what is best not just for us as individuals, but for the overall
  community

Examples of unacceptable behavior include:

* The use of sexualized language or imagery, and sexual attention or advances of
  any kind
* Trolling, insulting or derogatory comments, and personal or political attacks
* Public or private harassment
* Publishing others' private information, such as a physical or email address,
  without their explicit permission
* Other conduct which could reasonably be considered inappropriate in a
  professional setting

## Enforcement Responsibilities

Community leaders are responsible for clarifying and enforcing our standards of
acceptable behavior and will take appropriate and fair corrective action in
response to any behavior that they deem inappropriate, threatening, offensive,
or harmful.

Community leaders have the right and responsibility to remove, edit, or reject
comments, commits, code, wiki edits, issues, and other
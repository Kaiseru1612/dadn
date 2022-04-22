# dadn

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)
- [Usage](#usage)
- [Contributing](../CONTRIBUTING.md)

## About <a name = "about"></a>

Grading or marking student the answer sheet is a very common thing of teacher after the student test. However, this one costs a lot of time depend on the number of students that teacher teach and easily to make mistake when manual grading . Understanding these concerns, one of solution has been developed that is Optical Mark Recognition.
This solution is just suitable with multiple choice question test which requires student to highlight the one or more the correct options (A, B, C, D). Besides, in real life, we have a typical kind of test that is short answer. To deal with such kind of test, we propose a AI system which can scan the answer sheet then extracting exactly the handwriting information, content in each answer box correspond with question number of the test based on a defined format answer sheets. After that, the extracted content will be compared string by string with a "True Answers" file, input by user.

## Devices
- Raspberry pi 4
- Android phone
## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

1/ Install droidcam app on your android device with "keyword droidcam" 
                or click this link https://play.google.com/store/apps/details?id=com.dev47apps.droidcam&hl=vi&gl=US .
2/ Download the folder rasp code in this respositories.

### Installing
1/ Update your rapberry pi
  ...
  sudo apt-get update && sudo apt-get upgrade
  ...
3/ open application.py file and change the url to the url on your droidcam app.

## Usage <a name = "usage"></a>

Add notes about how to use the system.

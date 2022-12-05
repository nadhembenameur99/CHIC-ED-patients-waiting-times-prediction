# Patient Wait Times Prediction

Emergency room wait times prediction

## **Goal**

Generate emergency wait times models for CHIC ED

## Problem Statement

Have you ever stepped foot in the emergency room of a hospital in France either for a loved one or perhaps yourself,
only to be met with a grueling long wait until you see any medical professional?

It's frustrating. And there should definitely be a better system, right? Having immersive visit at CHIC Hospital
Emergency Department and being able to experience both sides of the system, I wanted to dig deep at what's really going
on and to actually do something about it.

### Technologies Used

- Python
- Pandas
- Scikit-learn
- Keras
- Anaconda

<!-- - Altair -- plotting
- Folium -- plotting -->

## Project Notes

### Data Gathering ###

Detailed administrative data on date and patient flow was provided by CHIC hospital:

### Data Modeling ###

The ability to accurately and reliably predict waiting times at walk-in hospital facilities can increase both patient
satisfaction and hospital efficiency via a better management of patient flow. This project implements machine learning (
ML) models to predict waiting times in the Emergency Room (ER) of the intercommunal public hospital CHIC in
Castres-Mazamet.

Several ML algorithms were evaluated to find the most accurate and useful prediction to a user. I
chose [Random Forest](https://medium.com/@muneebhashmi10/random-forest-from-scratch-in-python-238d91580841) among other
regression models explored for predicting wait times.

**PATIENT WAIT TIMES PREDICTION** is currently under development. If you notice any bugs, have any questions or
suggestions, I'd love
to hear from you: [nadhem.benameur@enis.tn](nadhem.benameur@enis.tn?subject=Feedback_on_Patient_Wait_times_prediction).


<img src="https://media.makeameme.org/created/me-patiently-waiting-399b1150e6.jpg" width=300>

### Steps towards model generating ###

0) Data exploration: First step where we explore extracted data and generate raw dataset
1) Data cleaning
2) Feature Engineering
3) Dataset preprocessing
4) Model Developpement
5) Model Training and Results

<!-- - Altair -- plotting
- Folium -- plotting -->

### Possible Future Enhancements ###

* Implement web interface to inspect patient flow and waiting times in real time
* Actively scrape hospital data
* Generate best route to hospital using combinatorial optimization and Google API to read your location

## Quick start

> UNZIP the sources or clone the private repository. After getting the code, open a terminal and navigate to the working
> directory, with product source code.

```bash
$ # Get the code
$ git clone https://github.com/nadhembenameur99/CHIC-ED-patients-waiting-times-prediction.git
$ cd CHIC-ED-patients-waiting-times-prediction
$
$ # Virtualenv modules installation (Unix based systems)
$ virtualenv env
$ source env/bin/activate
$
$ # Virtualenv modules installation (Windows based systems)
$ # virtualenv env
$ # .\env\Scripts\activate
$
$ # Install modules
$ pip3 install -r requirements.txt
$ or (if you are using anaconda)
$ conda install -r requirements.txt

```

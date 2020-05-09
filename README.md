# coroNAH
Inspiration
The rampaging outbreak of COVID-19, commonly known as the corona virus

What it does
Our product is our own machine learning model which uses facial recognition and hand gestures to detect a 
person who is coughing severely in a public space through a CCTV footage. The current prototype mainly works 
in airports, as cross-country travel is the main cause of the global spread of the virus. Based on the intensity 
of the persons cough, the facial recognition accesses the individuals travel history through the airport’s database 
and if the person if found to be travelling to highly infested areas he will be dealt with by the airport authorities.

How we built it
We trained our own custom datasets of hand gestures through the open source deep Neural Network, darknet, 
by manually plotting coordinates and training thousands of pictures. Then through facial landmark detection 
we combined our machine learning model and could detect intensive coughing in real time. Once recognized, our 
facial recognition database provided a history of the identified user’s travel history and based on risk levels, 
conducted emergency checkups for extra precaution.

Challenges we ran into
This was our first experience with deep Neural Networks and to build a highly accurate machine learning model 
without any thermal camera, infrared sensors etc. but only using a simple laptop webcam.

Accomplishments that I'm proud of
This is by far the most unique project we’ve worked on and are proud of creating the world’s first ever 
visual cough detection model

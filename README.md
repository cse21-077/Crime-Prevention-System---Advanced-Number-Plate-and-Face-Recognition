# Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition
By  Using already deployed cameras across the city, the system aims to enhance the identification and apprehension of criminals. It is important to note that this project is currently in its early stages, with ongoing development and refinement anticipated

This repository contains an advanced Python script for integrated number plate recognition, identification, and face recognition. The system is designed to detect number plates in images, identify the car details associated with the number plate, and perform face recognition with a focus on recognizing individuals even when wearing glasses.

## Features

1. **Number Plate Recognition:**
   - Utilizes the YOLOv3 deep learning model for accurate license plate detection.
   - Extracts the license plate region and displays it for further processing.
   - Calls a function to identify and verify the number plate against a hypothetical database.

2. **Face Recognition:**
   - Employs the dlib library for face detection and facial landmark prediction.
   - Draws bounding boxes around detected faces and overlays facial landmarks for visualization.
   - Calls a function to identify and verify the face against a hypothetical database.

3. **Database Interaction:**
   - Placeholder functions (`identify_number_plate` and `identify_face`) simulate the process of identifying and verifying information against a database.
 

## Implementation and Importance

In recent times, the surge in citizens sharing videos of personal security incidents, including incidents of robbery by the Police, underscores the urgency for robust crime prevention measures. This Crime Prevention AI system aims to address these concerns by integrating advanced number plate and face recognition technologies.
![653c86f4ae6552d18b48ed14db90277388d6d287](https://github.com/cse21-077/Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition/assets/102771883/0a92d706-1afe-4a35-b0f3-8ae191b4e912)
![8cd1b3b9a577c812aae38c04d5d49d54b8258b59](https://github.com/cse21-077/Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition/assets/102771883/ea7c2b6c-a5fd-4fdf-af6e-381b75248ec9)
![0a4ab7cc2e7c866566352a324a837daf220a4903](https://github.com/cse21-077/Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition/assets/102771883/d3dee09d-6e8e-4185-9a68-899d1aec3949)
![701332d9d5dcd9f57652a945be7bcc233742ddbe](https://github.com/cse21-077/Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition/assets/102771883/1ae423af-fb5a-4d7e-b542-eb3fa54a6574)



### Testing Detection and Recognition

To prioritize user privacy, the initial implementation involves testing detection and recognition on privately created videos. This approach ensures that the system can effectively identify potential threats without compromising the privacy of individuals captured in public spaces. Our commitment to privacy and ethical AI practices guides our decision to perform initial testing on privately generated content.

### Importance of Privacy-Centric Testing

- **User Trust:** By prioritizing privacy in the testing phase, we build trust with users who contribute to the system's development. This ensures that individuals feel confident in the system's capabilities without fear of unwarranted surveillance.

- **Ethical Considerations:** Recognizing the sensitive nature of personal data, the utmost care to develop a system that adheres to ethical standards. Protecting user privacy is a fundamental principle guiding the development process.

### Collaboration with Government

Once the system achieves a high level of security and accuracy, we envision collaborating with governmental authorities being Botswana Police & Its levels to enhance public safety further. This collaboration may involve gaining access to official databases to track and identify individuals associated with criminal activities.

- **Government Collaboration:** Working closely with law enforcement agencies, we aim to contribute to the creation of a secure and efficient crime prevention network. Collaboration with the government ensures that the system is aligned with official security protocols.

- **Database Access:** Access to official databases can significantly augment the system's capabilities. By integrating with governmental resources, we can enhance the accuracy and reliability of identification, contributing to a safer environment for citizens.

### Enhancing Accuracy with Gait Recognition

As part of our commitment to continuous improvement, we are exploring the integration of gait recognition technology. Gait recognition analyzes the unique walking patterns of individuals, adding an additional layer of identification. This enhancement has the potential to further increase accuracy, especially in scenarios where facial recognition may be challenging.

- **Improved Identification:** Gait recognition can contribute to more accurate identification, complementing existing facial recognition capabilities.

- **Challenging Environments:** In situations where facial features may be partially obscured or challenging to capture, gait recognition provides an alternative method for identification.

- **Ongoing Research:** We are actively researching and testing gait recognition algorithms to assess their suitability for integration into the Crime Prevention AI system.

![gait-recognition-identify-mapping-unique-manner](https://github.com/cse21-077/Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition/assets/102771883/00b5537e-a453-4522-a5aa-bb4da32ad0fa)
![Overview-of-the-proposed-gait-recognition-method](https://github.com/cse21-077/Crime-Prevention-System---Advanced-Number-Plate-and-Face-Recognition/assets/102771883/4560022c-ad0f-423a-8e4f-f018ca89872d)


## Prerequisites

- Python 3.x
- OpenCV
- NumPy
- dlib
- YOLOv3 weights and configuration file for license plate detection (not provided in this repository)

## Usage

1. Install the required libraries:

   ```bash
   pip install opencv-python numpy dlib
   
## Setup:

Download YOLOv3 weights and configuration file for license plate detection. Place them in the project directory.
Execution:

python main_script.py pitures/image67.jpg
Replace /image.jpg with the image path for processing.

##Still building this project while still learning this github code is just to doccument the beginning steps, the complete source code wont be Public

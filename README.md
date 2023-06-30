# Vision

Vision is a Multilingual and Multimodal Conversational AI system designed to assist visually impaired individuals. It simplifies daily tasks by managing ToDos, answering complex visual queries, and providing live object detection and scene understanding. Users can interact with Vision by simply double-tapping anywhere on the screen and speaking in natural language.

## Demo and Documentation

- [Demo](https://youtu.be/Ls6mzaTeM64)
- [Documentation and Architecture (PPT)](https://1drv.ms/p/s!AoPml3-hFN8WgtJE8NdjsMAQxRNRlg?e=nLOsRy)
  
## Features

- **Conversational AI Interaction**: Double-tap anywhere on the screen and talk with Vision in natural language for easy interaction.
- **On Device Live Object Detection**: Speak a command, e.g. "Help me find my laptop", and Vision will automatically activate the camera to locate objects.
- **Answering Complex Visual Queries and Interpretation**: Ask complex queries like "Tell me the expiry date of the medicine here, and also describe the activity of any person present." Vision will capture the image, process the scene, and provide detailed information.
- **Adaptive Database Services**: Interact with the database in natural language. For example, "Add a task to buy groceries on Friday with high priority." Vision will manage tasks using natural language interaction, simplifying daily planning.

## Submodules

1. **VisionAPI**: This is the backend of the Vision system, responsible for processing and responding to user queries.
2. **VisionAndroid**: This is the client-side application that users interact with. It communicates with the VisionAPI to provide responses to the user.

## Technology Stack

- TensorFlow Lite
- FastAPI (Python) for REST API
- Torch
- Langchain
- Docker
- Transformers
- Image processing
- LLM (Language Model)
- Prompt engineering techniques


## Getting Started

To get a local copy up and running, follow these simple steps:

1. Visit the main page of the repository.
2. Navigate to each submodule (VisionAPI and VisionAndroid).
3. Switch to their main branches.
4. Clone each submodule individually to your local machine.
5. After cloning, navigate to the project directory of each submodule.
6. Install the required packages as mentioned in the respective README files of the submodules.
7. Run each application as per the instructions provided in their respective README files.

Please ensure you have the necessary environment and tools installed on your machine to run the applications.

## Contact

Your Name - [rohanvermadev@gmail.com](mailto:rohanvermadev@gmail.com)

Project Link: [https://github.com/DevOpRohan/Vision](https://github.com/DevOpRohan/Vision)

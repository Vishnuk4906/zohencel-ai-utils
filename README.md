<div style="text-align: center;">
  <img src="https://raw.githubusercontent.com/Vishnuk4906/zohencel-ai-utils/main/logo.png" alt="Zohencel-AI Logo" style="width: 20%; height: auto;">
</div>

# Zohencel-AI

**Zohencel-AI** is a Python library designed to simplify the development of voice assistants, chatbots, and analytical tools. With built-in modules and functions, `zohencel-ai` provides an easy-to-use interface for building advanced AI solutions without the complexity.

---

## This is where the search ends!

### Key Features
- **Voice Assistant Tools**: Voice assistant in single import.
- **Data Analysis**: Data analytics tool to visualize and query data in natural language.

---

## Installation

To install `zohencel-ai`, use the following pip command:

```bash
pip install zohencel-ai
```
---

## AI Voice Assistant

The `VoiceAssistant` in `Zohencel-AI` provides a customizable, voice-enabled assistant that listens to user input, processes it, and responds with spoken text. Designed to be adaptable, the assistant’s attributes—such as name, tone, purpose, and voice type—can be tailored to fit a wide range of use cases, making it suitable for personalized or business-focused applications.

### Key Customizations
- **Assistant Name**: Set a unique name for the assistant, making interactions feel more personalized and relatable.
- **User Name**: Personalize responses by specifying the user’s name, enhancing engagement.
- **Tone and Duty**: Define the assistant’s tone and duty with an optional description. For example, set it as a "helpful and friendly guide" or an "informative support assistant" to adjust the assistant's personality.
- **Voice Type**: Choose between a ‘male’ or ‘female’ voice to best suit the assistant's character and user preferences.

### Usage Example

Here's how to configure these options when creating and running your assistant:

```python
from zohencel_ai import VoiceAssistant

# Initialize the VoiceAssistant
assistant = VoiceAssistant()

# Run the assistant with custom settings
assistant.run(
    voice='female',                # Voice type: 'female' or 'male'
    assistant_name='Zohencel',     # Assistant's name
    user_name='Alex',              # User's name for personalized responses
    description='I am here as your friendly and reliable AI guide.'  # Assistant's tone and purpose
)
```
all the parameters are optional and you can just run it by calling assistant.run() 


## Author

<div style="text-align: center;">
  <a href="https://www.linkedin.com/in/vishnu-k-8a058425b/" target="_blank">
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e9/Linkedin_icon.svg" alt="LinkedIn" style="width:30px; height:auto;">
  </a>
</div>

---

# UE_Neurosync_Agent

UE_Neurosync_Agent is an Unreal Engine project that integrates the NeuroSync framework, enabling real-time facial animation from audio input. This project leverages advanced machine learning models to synchronize facial expressions with speech, enhancing character realism in virtual environments.

## Features

- **Real-Time Audio-to-Face Animation**: Utilizes the NeuroSync model to generate facial blendshapes from audio features in real-time.
- **MetaHuman Integration**: Compatible with Unreal Engine's MetaHuman characters for high-fidelity facial animations.
- **LiveLink Support**: Streams facial animations directly into Unreal Engine using LiveLink for seamless integration.
- **Customizable Blueprint Interface**: Provides a user-friendly interface for integrating NeuroSync into Unreal Engine projects.

## Requirements

- Unreal Engine 5.1 or later
- [NeuroSync Model](https://huggingface.co/AnimaVR/NeuroSync-0.1a) (128-frame input)
- [LiveLink Plugin](https://www.unrealengine.com/marketplace/en-US/product/livelink) for real-time data streaming
- [Python](https://www.python.org/downloads/) (for model inference and data processing)

## Installation

1. Clone this repository into your Unreal Engine project's `Plugins` directory.
2. Enable the NeuroSync plugin in the Unreal Engine Editor under **Edit > Plugins**.
3. Set up the LiveLink connection:
   - Open the LiveLink panel in Unreal Engine.
   - Add a new LiveLink source and configure it to connect to the NeuroSync model.

## Usage

- **In Unreal Engine**:
  - Add the `NeuroSync` actor to your scene.
  - Configure the actor's properties to match your character's setup.
  - Play the scene to see real-time facial animations driven by audio input.

- **In Python**:
  - Use the provided scripts to preprocess audio data and run inference with the NeuroSync model.
  - Stream the resulting facial blendshape data into Unreal Engine via LiveLink.

## Contributing

Contributions are welcome! Please fork this repository, make your changes, and submit a pull request. Ensure that your code adheres to the project's coding standards and includes appropriate tests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [NeuroSync](https://github.com/JoPmt/NeuroSync) for the audio-to-face animation model.
- [Unreal Engine](https://www.unrealengine.com/) for providing the platform and tools for development.
- [MetaHuman Creator](https://www.unrealengine.com/en-US/metahuman-creator) for high-quality character creation.

## Contact

For questions or support, please open an issue on this repository or contact the project maintainer at [your-email@example.com].


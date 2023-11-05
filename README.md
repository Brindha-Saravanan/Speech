
# Speech to Text with Grammar Correction
🗣️📝 In these exciting projects, we harness the power of OpenVINO™ and Intel OneAPI to take AI to the next level. The first project dives into automatic speech recognition with OpenVINO™, utilizing the QuartzNet 15x5 model. The second project tackles grammatical error correction, transforming pre-trained Hugging Face Transformers models into OpenVINO™ IR format. Both projects exemplify the seamless integration of OpenVINO™ within the Intel OneAPI ecosystem, significantly boosting the efficiency and performance of AI-driven tasks such as speech recognition and text correction. 🚀💡



## OpenVINO™ and Intel OneAPI

🧠🚀 OpenVINO™, a key component of the Intel OneAPI toolkit, empowers developers to optimize deep learning models across various Intel hardware platforms. It provides a unified programming model for CPUs, GPUs, and FPGAs, enhancing performance and efficiency in AI and computer vision tasks.


## Optimum Intel    

🧠🚀 Optimum Intel is the interface between the Transformers and Diffusers libraries and the different tools and libraries provided by Intel to accelerate end-to-end pipelines on Intel architectures.Optimum Intel provides a simple interface to optimize Transformer models and convert them to OpenVINO™ Intermediate  Representation (IR) format to accelerate end-to-end pipelines on Intel® architectures using OpenVINO™ runtime.


## Appendix

### Table of Contents:
#### Speech to Text with OpenVINO™:
- [Imports](#imports)
- [Settings](#settings)
- [Download and Convert Public Model](#download-and-convert-public-model)
    - [Download Model](#download-model)
    - [Convert Model](#convert-model)
- [Audio Processing](#audio-processing)
    - [Define Constants](#define-constants)
    - [Available Audio Formats](#available-audio-formats)
    - [Load Audio File](#load-audio-file)
    - [Visualize Audio File](#visualize-audio-file)
    - [Change Type of Data](#change-type-of-data)
    - [Convert Audio to Mel Spectrum](#convert-audio-to-mel-spectrum)
    - [Run Conversion from Audio to Mel Format](#run-conversion-from-audio-to-mel-format)
    - [Visualize Mel Spectrogram](#visualize-mel-spectrogram)
    - [Adjust Mel Scale to Input](#adjust-mel-scale-to-input)
- [Load the Model](#load-the-model)
    - [Do Inference](#do-inference)
    - [Read Output](#read-output)
    - [Implementation of Decoding](#implementation-of-decoding)
    - [Run Decoding and Print Output](#run-decoding-and-print-output)

#### Grammatical Error Correction with OpenVINO:


- [Grammar Checker](#grammar-checker)
- [Grammar Corrector](#grammar-corrector)
    
- [Final output](#Final-output)




## Analysis
🎙️🤖 This project harnesses OpenVINO and the QuartzNet 15x5 model to perform automatic speech recognition (ASR). The workflow commences with model optimization and covers audio processing, including constants, supported audio formats, and data conversion. After visualizing the audio data, it's converted into Mel Spectrogram representations for effective ASR. Inference with the ASR model generates per-frame probabilities, which are decoded into human-readable text.

📝✅ Following ASR, the project proceeds with grammar correction, enhancing the quality of transcribed text. It uses the FLAN-T5 model for grammatical error correction. This project showcases how OpenVINO empowers ASR tasks and grammar correction, providing efficient and accurate speech recognition while managing complex audio data, inference processes, and linguistic refinements. 🚀💬
## Acknowledgements

The information and guidance in this report were referenced from the [OpenVINO Notebooks Repository](https://github.com/openvinotoolkit/openvino_notebooks/tree/main/notebooks/226-yolov7-optimization). We extend our gratitude to the contributors and authors of the repository for their valuable insights and resources that contributed to this work.

## Run in Your Machine


Clone the project

```bash
  git clone https://github.com/Brindha-Saravanan/Speech2text-grammar-correction-using-openvino.git
```

Open the Jupyter Notebook File

```bash
  Speech2text-grammar-correction-using-openvino.ipynb
```

Import the Audio File and Run all the cells

speech to text
<img src="https://drive.google.com/uc?id=1KvWChs9y41u-i9yOT3s0KwaBRR-T2wI2" alt="Speech to text">



Grammer Correction
<img src="https://drive.google.com/uc?export=view&id=1irtEPx3I8Ys8jqO9rkEAsPmX89PvpHJN" alt="grammer correction">


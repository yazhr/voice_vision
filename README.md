# Voice Vision

Voice Vision is an assistive project focused on accessibility for visually impaired and partially sighted users. It combines voice interaction, object detection, color description, and read-aloud features to provide audio-first support.

## Core capabilities

- Voice assistant interactions through speech input/output.
- Object detection modules using YOLO/MobileNet assets included in this repository.
- Color identification and spoken description utilities.
- Read-aloud scripts for extracted text and nearby content.

## Repository highlights

- `voice_vision.py`, `FINAL_VOICE_ASSISTANT.py`, `speech_assistant.py`: voice assistant flows.
- `object_detection.py`, `OBJECT_DETECt.py`, `new_OBJ.py`, `new_OBJ2.py`: object detection variants.
- `Colour_desc.py`, `Colour2.py`: color analysis and descriptions.
- `READ_ALOUD.py`, `READ_ALOUD2.py`: text-to-speech reading scripts.
- `yolo.cfg`, `yolov3.cfg`, `coco.names`, `mobilenet_iter_73000.caffemodel`, `deploy.prototxt`: model/config files.

## Prerequisites

- Python 3.8+
- Webcam (for live detection scripts)
- Microphone + speakers/headphones

Install commonly used packages:

```bash
pip install opencv-python numpy pyttsx3 SpeechRecognition pillow
```

Depending on the script you run, you may also need:

```bash
pip install pyaudio
```

## Quick start

1. Clone the repository.
2. Open the project folder.
3. Install dependencies listed above.
4. Run one script based on your use case.

Examples:

```bash
python voice_vision.py
python object_detection.py
python READ_ALOUD.py
```

## Notes

- Multiple scripts are experimental/prototype variants of the same features.
- If a model-loading script fails, verify model file paths are correct and files are present.
- If microphone input fails, check OS-level microphone permissions.

## License

No license file is currently included. Add one if you plan to distribute publicly.

# GPT4FreeCAD

A FreeCAD plug in that integrates OpenAI's GPT-4 model to generate Python scripts for creating sketches & 3D models based on user input.

![Workbench Logo](logo.svg)

## Requirements
- Python
- Open AI API key

## Installation

1. Open a terminal or command prompt with administrator privileges.
2. Clone this repository directly into the FreeCAD Mod folder:

`git clone https://github.com/revhappy/GPT4FreeCAD`

into:
`C:\Program Files\FreeCAD 0.20\Mod`

3. Open a command prompt and navigate to the FreeCAD bin folder:

`cd C:\Program Files\FreeCAD 0.20\bin`

4. Install the `requests` library:

`python -m pip install requests`

## Usage

1. Launch FreeCAD.
2. Go to `Macro > Macros...`.
3. Navigate to the folder: `C:\Program Files\FreeCAD 0.20\Mod\GPT4FreeCAD`.
4. Click on `GPTSTART.FCMacro` and click "Execute" to run the macro.

### Adding to the Toolbar

1. In FreeCAD, go to `Tools > Customize...`.
2. Click on the "Macros" tab.
3. Follow the directions to add the macro to your toolbar.

## Tips

Yes, the model can fail and present a blank screen or something random.  
You can turn on Report View, I have it set up to show the python code along with any errors.
In case of failure, merely prompt 'try again' or copy and paste the error into the prompt screen.
These are early days, be patient :p

## License

This project is licensed under the [MIT License](LICENSE).

Copyright (c) 2023 Robb Sharma
## Links

- [GitHub Repository](https://github.com/revhappy/GPT4FreeCAD)

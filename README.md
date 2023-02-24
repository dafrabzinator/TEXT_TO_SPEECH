## gTTS Text-to-Speech Script
This Python script uses the gTTS (Google Text-to-Speech) library to convert the text from a file to speech and save it as an MP3 file. The script can be customized to work with different input files and languages.
### Requirements
This script requires the following dependencies to be installed:
- python3.7 and latest version
- gTTS library
you can install the library using pip:
`pip install gtt`

### Usage
To use this script, follow these steps:

1.Place the text you want to convert to speech in a text file (e.g. "frabswords.txt").

2.Update the file variable in the script to point to your text file.

3.Optionally, update the lang variable in the script to specify the language of the text. The default language is English ('en').

4.Run the script using the following command:
`py -m text_to_speech.py`
5. The script will generate an MP3 file named "voice.mp3" in the same directory as the script.
###Customization
This script can be customized to work with different input files and languages. Here are some examples:
- To use a different input file, update the`frabswords.txt variable in the script to point to your file.
- To use a different language, update the lang variable in the script to the appropriate language code. You can search a list of language codes in the [gTTS documentation.](https://gtts.readthedocs.io/en/latest/)
- To change the output file name, update the speech.save() method in the script method. For example, to save the output as a WAV file, use speech.save(`voice.wav`).
### License
This script is released under the MIT license. See the LICENSE file for more details.
## Author
-[dafrabzinator](linkedin.com/in/oluwabusayomi-s-orosunlegan-6a0144263).
-[twitter](https://twitter.com/dafrabs).
-[email](oluwabusayomidafrabzinator@gmail.com).

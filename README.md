# Assignment-QT
This Repository Contains two folders. 
1.) NOTEPAD-QT:
This folder contains source code files for the text editing app build using QT creator.
**How to run:**:
a) Open the project files in Qt Creator.
b) Compile/ Build the project using "Run" icon present at bottom-left corner.
c) A GUI window will be opened that can be used for text editing.
**Features:**
The GUI application that opens contains following functionalities for text files:
a) It can be used to create a new file, open files and can save them and also save as well.
b) Text can be editted using  cut/copy/paste, undo/redo, bold/italic/underline, superscript and subscript tools.
c) The bold tool can be used to bold as well as unbold the text i.e if the highlighted text is bold, clicking on bold option will unbold it and vice versa.
This same functionality works for italic and underline as well.
d)Superscript and subscript features are also added.
e) There is a menu "About me" and trigerring it will display my resume.
**What has been done:**
Various classes of Qt Creator are used for various functionalities.
a) QString class is used for saving the path of selected file.
b) QFile class is used for opening or closing selected file.
c) QTextStream class is used for writing to/ reading from a text file.
d) QMessageBox class is used for displaying error/ information type messages.
e) QFileDialogue class is used to get the path of file to be opened/ saved through a dialogue box.

2.) OpenOCRCorrect:
(This is a cloned repository from https://github.com/rohitsaluja22/OpenOCRCorrect along with some additional functionalities.
Description: It is a framework for assisting human while correcting the OCR errors in documents, mostly dedicated to Indian Languages. Tested on Sanskrit, Hindi, Marathi and English.
**Features:**
a) Error detection.
b) Generating Suggestions (will replace this to auto-completion in Future Work). Please mail to rohitsaluja22@gmail.com or file an issue for any suggestions related to auto-completion.
**Following information is updated on the fly, after correction of each page:-**
a)A domain specific dictionary which is uploaded on the fly.
b)The domain specific dictionary is also uploaded with OCR words with high confidence as the user starts working on the document.
c)OCR confusions specific to the documents which are uploaded on the fly.
**Additional Functionality:**
In this cloned repository, I have added three tools in toolbar i.e bold, superscript and subscript that can be used to bold or unbold, superscript as well as subscript a text.



 

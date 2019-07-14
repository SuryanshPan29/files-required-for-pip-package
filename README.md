# TextToPPT-Library

TextToPPT is a Python library for converting files generated by exporting WhatsApp chats into a .pptx file. 

## Usage

Make sure you’re in the same directory as texttoppt folder and type this command:

```python
python
from texttoppt.orchestrator import TextToPPTOrchestrator
orc = TextToPPTOrchestrator()
orc.SetStartDate("16/11/19")
orc.SetMessageAuthor("All")
orc.ConvertTextFileToPPT('input.txt','output.pptx')
```

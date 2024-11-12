### Name : Sowmya V
### Reg no : 212222110045
### Date : 
# Exercise 7 - Read and Extract Text from PDF

### Aim:
To extract text from a PDF and save it to a text file.

### Software required:
UiPath Studio-community edition


### Procedure:

1. **Initialize the PDF File Path**:
   - Specify the path of the PDF file you want to extract text from. In the **Extract PDF Text** activity, set the **PDF file** property to the path of your PDF file.
   - This will allow the **Extract PDF Text** activity to locate and read the content of the PDF file.

2. **Extract PDF Text**:
   - Use the **Extract PDF Text** activity to read the text from the PDF file.
   - The extracted text will be saved into a variable, typically named `pdf_text`.

3. **Log the Extracted Text (Optional for Debugging)**:
   - Add a **Log Message** activity to output the content of `pdf_text` to the log, which is helpful for debugging.
   - In the **Message** property, set it to `pdf_text` to log the extracted text.
   - Set **Log Level** to `Info` to display the message in the output panel.

4. **Write the Text to a Text File**:
   - Use a **Write Text File** activity to save the extracted text to a text file.
   - Set the **Text** property to `pdf_text`, which holds the extracted content from the PDF.
   - In the **Write to filename** property, specify the path where you want to save the text file.
   - This will create a new text file at the specified path containing the content of the PDF.

5. **Run the Workflow**:
   - Execute the workflow to test it. UiPath will extract text from the specified PDF, log the text in the Output panel, and then save the text into a file at the specified location.


### Main.xaml:

![image](https://github.com/user-attachments/assets/b8041e4c-56e4-4de0-9c3c-e966ef6265bb)

### Output:

### PDF Text:
![image](https://github.com/user-attachments/assets/fb0a692a-7950-4291-924b-b00408bd81bb)

### Text File:
![image](https://github.com/user-attachments/assets/89c96514-3411-412f-a4ab-8936bc44ebd7)



### Results:
Thus, the text from the PDF file was successfully extracted, logged for verification, and saved to a text file. 



# Automating Flashcard Creation for Anki Using ChatGPT

## Purpose

This guide provides a step-by-step process for converting textbook content into Anki flashcards using ChatGPT, Microsoft Excel, and Anki. The goal is to automate the creation of flashcards for free, bypassing the limitations and costs associated with paid tools. This guide is for undergraduate students looking to streamline their study process by efficiently generating detailed, customizable flashcards directly from their textbooks. This has personally saved me hundreds of hours of valuable study time.

## Prerequisites

1. **ChatGPT**: Preferably the paid subscription version to ensure faster processing and the ability to handle more complex tasks. Most importantly, the ability to upload images.
2. **Microsoft Excel**: For organizing the generated content into a format suitable for Anki.
3. **Anki**: The official version, downloaded as a computer application. (Note: Third-party tools have not been tested with this process).

## Process Overview

### Step 1: Extract Textbook Content as Screenshots
- Begin by taking screenshots of the textbook pages that you want to convert into flashcards. Ensure the text is clear and that each image captures the entire section you need.
- IMPORTANT: ChatGPT cannot yet handle uploading entire PDFs while processing them properly. It is best to do individual page screenshots.

### Step 2: Use ChatGPT to Extract and Format Information
- Upload the screenshots to ChatGPT and use the following advanced prompt to extract the information:

#### Advanced Prompt
```
I am working on converting textbook content into Anki flashcards. I will provide you with screenshots. For each screenshot, extract the relevant information into a basic table format, with questions on the left and answers on the right. For each image, you will make a new table. Remember this. No repeat tables. If any images are required in the answers, place an "X" as a placeholder. If additional information is needed (like definitions or advanced concepts that are not fully covered), include those as well, either in the flashcard or as an additional flash card. The output should be in a format that I can directly copy and paste into Microsoft Excel, with no fancy formatting or indentations. Remember this. Once all the information is extracted, I will manually paste it into Excel, save it as a .CSV file, and import it into Anki as a deck. Remember these instructions. Do not hallucinate.
```

- For each screenshot:
  1. **Upload** the image to ChatGPT.
  2. **Extract** the text content and **format** it into a table.
  3. **Copy and paste** the output into Microsoft Excel.

### Step 3: Organize Content in Microsoft Excel
- Paste the content from ChatGPT into Excel. Ensure that the questions and answers are aligned properly in two columns, with questions on the left and answers on the right.
- Save the Excel file as a `.CSV` file, which is compatible with Anki.

### Step 4: Import the .CSV File into Anki
- Open Anki and select the option to import a file.
- Choose the `.CSV` file you saved.
- Import the content into Anki, make sure to select the right deck. Also, select "Comma" as the field separator.
- Anki will automatically create flashcards based on the data from the `.CSV` file.

### Step 5: Review and Enhance Flashcards in Anki
- Once the flashcards are imported into Anki, go through each card while referencing the original textbook. Add any additional formatting or details that may be necessary for better understanding.
- This step is crucial to ensure that the flashcards are not just accurate but also effective as study tools.
- This is purposely not automated because this part is where you get to learn the content.

### Final Notes
- After importing the flashcards into Anki, always review them in detail to ensure they meet your study needs. Adjust and enhance the flashcards as needed to reinforce your learning and comprehension.

## Conclusion

This guide was created by an undergraduate student to help peers streamline their study process using free tools and resources. With the increasing costs and restrictions associated with paid tools, this method offers a viable alternative that leverages the power of AI, making it accessible to everyone with the necessary prerequisites. Happy studying!

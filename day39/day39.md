# Day 39 – PDF Splitter & Merger

## 📌 Project Overview

Today I built a **PDF Splitter & Merger** web application using HTML, CSS, and JavaScript.

The application allows users to:

* Upload PDF files.
* Split a PDF into individual pages or selected page ranges.
* Merge multiple PDF files into a single PDF.
* Preview processed PDFs.
* Download the generated PDF files locally.

## 🎯 Objectives

* Understand how browser-based PDF processing works.
* Build a practical utility application using JavaScript.
* Implement PDF splitting functionality.
* Implement PDF merging functionality.
* Provide PDF preview and download options.
* Practice creating a complete application from a structured AI prompt.

## 🛠️ Technologies Used

* HTML5
* CSS3
* JavaScript
* PDF processing libraries
* Browser File API
* Claude AI for application generation

## 🧪 Testing

### PDF Splitter
The PDF Splitter was tested with a sample PDF.

**Test performed:**
1. Uploaded a PDF.
2. Selected the required pages/page range.
3. Processed the PDF.
4. Previewed the output.
5. Downloaded the split PDF.
6. Verified that the resulting PDF contained the expected pages.

### PDF Merger
The PDF Merger was tested with multiple PDF files.

**Test performed:**

1. Selected multiple PDF files.
2. Added them to the merger.
3. Verified the selected files.
4. Merged the PDFs.
5. Previewed the generated document.
6. Downloaded the merged PDF.
7. Verified the resulting page order.

## 📸 Screenshots

The `Day39` folder contains screenshots showing:

* PDF Splitter interface
* PDF Merger interface
* Uploaded PDF files
* Split PDF result
* Merged PDF result
* PDF preview
* Downloaded/processed files
---

## 💡 Key Learnings

### 1. Browser-Based PDF Processing

I learned that PDF files can be processed directly in the browser using JavaScript and suitable PDF libraries, without requiring a traditional backend server.

### 2. File API

The browser's File API can be used to read files selected by the user and pass their data to JavaScript for processing.

### 3. PDF Splitting

Splitting a PDF involves reading the source document, selecting specific pages, creating a new PDF, and copying the required pages into the new document.

### 4. PDF Merging

PDF merging involves loading multiple PDF documents and combining their pages into one output document while preserving the required order.

### 5. Client-Side Applications

This project demonstrated that useful file-processing utilities can be built as client-side applications, making them simple to run locally.

### 6. AI-Assisted Development

Claude helped generate the complete application from a structured prompt. I learned the importance of providing clear requirements and answering the AI's interview questions accurately before generating the application.

### 7. Testing Matters

Testing both the splitter and merger separately helped verify that the application worked correctly for different PDF operations.

## 🔍 Challenges Faced

* Understanding PDF page manipulation.
* Handling uploaded files in the browser.
* Ensuring multiple PDFs were merged in the correct order.
* Verifying that generated PDFs could be previewed and downloaded.
* Testing the application with different PDF inputs.

## 📚 What I Improved

Through this project, I improved my understanding of:

* JavaScript file handling
* Client-side PDF processing
* DOM manipulation
* Event handling
* User interface development
* Testing web applications
* AI-assisted coding
* Git and GitHub workflow

## 📈 Day 39 Outcome

By the end of Day 39, I successfully created and tested a functional **PDF Splitter & Merger** application.

The project helped me combine **AI-assisted development, frontend development, file handling, PDF processing, testing, and GitHub documentation** into one practical project.


## 🏁 Conclusion

Day 39 was focused on building a practical PDF utility instead of only learning individual concepts. The completed application can split and merge PDF documents, preview the results, and download the processed files.

This project gave me practical experience with browser-based file processing and strengthened my confidence in building complete web applications with the help of AI.

# Visual-Debugger-for-Visual-C++

### A Visual Diagnostic tool for Debugging and other Applications in Visual Studio

---

#### System Requirements
- Visual Studio 2022
- x86 configuration

---

#### Aim
- The main aim of this project is to reflect the current status of the code while debugging in a kind of diagrammatic way that is easy for the user to visualize.
- Show the contents of variables as well as data structures along with the memory stack.

---

#### Workflow
1. Iterate through the running processes in the operating system. Identify the target process and obtain its handle and perform stackwalk operation on the main thread. Checks machine type etc.
   
   ![Process-Identification](https://github.com/user-attachments/assets/55327250-a4a4-40e4-b657-bd89a3de6a43)
   
2. Relation between components of the C++ DLL
   
   ![PDB-file-Interaction](https://github.com/user-attachments/assets/0bd59dcf-0497-4f77-928a-f38528b1961f)
   
3. Marshalling data from C++ DLL to WPF
   
   ![Marshalling](https://github.com/user-attachments/assets/ba601807-c157-4d19-92a8-05f233619e45)
   
4. Visualize the UI, you can improv on this definitely, we gave up by the end of it
   
   ![image](https://github.com/user-attachments/assets/33b6f4f2-635b-4137-900a-007886bb41d9)

---

#### Improvements Possible
- Read and marshal complex data structures using custom Marshaller and COM Objects.
- Allow visualization of multithreaded applications.
- Visualization of interlinked connections between data structures across different functions and even multiple threads.
- Support visualization of new features from VC++ 11 onwards, such as smart pointers, etc.

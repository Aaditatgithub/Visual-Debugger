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
   
   ![Screenshot 2024-07-12 203545](https://github.com/user-attachments/assets/cdb46618-74bb-4c8a-a742-a65ebe904529)
   
2. Relation between components of the C++ DLL
   
  ![Screenshot 2024-07-12 203721](https://github.com/user-attachments/assets/b84ac997-c3f3-468b-882b-6ba1077d270a)

   
3. Marshalling data from C++ DLL to WPF
   
   ![Screenshot 2024-07-12 203843](https://github.com/user-attachments/assets/a76e487a-59b9-45c0-bfa5-729555871b40)

   
4. Visualize the UI, you can improv on this definitely, we gave up by the end of it
   
   ![Screenshot 2024-07-12 203927](https://github.com/user-attachments/assets/e496f09d-8c57-4acc-88f9-f5e8a48ac83d)


---

#### Improvements Possible
- Read and marshal complex data structures using custom Marshaller and COM Objects.
- Allow visualization of multithreaded applications.
- Visualization of interlinked connections between data structures across different functions and even multiple threads.
- Support visualization of new features from VC++ 11 onwards, such as smart pointers, etc.

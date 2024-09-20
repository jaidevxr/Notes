# Essential Windows Terminal Commands

### Basic Commands

1. **Navigation**
   - **List Files and Directories**
     ```cmd
     dir
     ```
   - **Change Directory**
     ```cmd
     cd directory_name
     ```
   - **Go to Home Directory**
     ```cmd
     cd %HOMEPATH%
     ```
   - **Go to Parent Directory**
     ```cmd
     cd ..
     ```

2. **File Manipulation**
   - **Create a New Directory**
     ```cmd
     mkdir directory_name
     ```
   - **Remove a Directory (empty)**
     ```cmd
     rmdir directory_name
     ```
   - **Remove a Directory (non-empty)**
     ```cmd
     rmdir /s directory_name
     ```
   - **Copy a File or Directory**
     ```cmd
     copy source_path destination_path
     ```
   - **Move or Rename a File or Directory**
     ```cmd
     move source_path destination_path
     ```
   - **Delete a File**
     ```cmd
     del file_name
     ```

3. **Viewing Files**
   - **Open a File in the Default Text Editor**
     ```cmd
     start file_name
     ```
   - **View File Content**
     ```cmd
     type file_name
     ```
   - **View File Content Page by Page**
     ```cmd
     more file_name
     ```

4. **Searching**
   - **Search Within Files**
     ```cmd
     findstr "search_string" file_name
     ```

### Helpful Commands

1. **Command Information**
   - **Get Help for a Command**
     ```cmd
     command_name /?
     ```

2. **Process Management**
   - **List Running Processes**
     ```cmd
     tasklist
     ```
   - **Kill a Process**
     ```cmd
     taskkill /PID process_id
     ```

3. **Networking**
   - **Check Network Connectivity**
     ```cmd
     ping website_or_ip
     ```
   - **Check Open Ports**
     ```cmd
     netstat -ano
     ```

4. **Environment Variables**
   - **List Environment Variables**
     ```cmd
     set
     ```
   - **Set an Environment Variable**
     ```cmd
     set VAR_NAME=value
     ```

5. **Archiving and Compression**
   - **Compress a File (ZIP) using PowerShell**
     ```powershell
     Compress-Archive -Path source_path -DestinationPath destination_path.zip
     ```
   - **Extract a ZIP File using PowerShell**
     ```powershell
     Expand-Archive -Path source_path.zip -DestinationPath destination_path
     ```

### System Information and Control

- **Clear the Screen**
  ```cmd
  cls

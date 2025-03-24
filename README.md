# Memory Manipulator

## Description  
Memory Manipulator is a C# console application that allows manipulation of other processes' memory in a Windows environment. It uses the Windows API (WinAPI) to search memory addresses, filter values, and modify data in the target process's memory.

## Features  
- **View all open windows and their processes**  
- **Search memory addresses within a process** based on a given value  
- **Filter found memory addresses** based on a new value  
- **Modify values of found addresses**  
- **Manually change the value at a specific memory address**  

## Technologies  
- **C#**  
- **.NET Core**  
- **WinAPI** for process memory interaction  
- **Multithreading** for memory search optimization  

## Installation & Execution  

### 1. Download & Build  
You need to have **.NET SDK** installed.  

```sh
# Clone the repository
git clone https://github.com/your-repository/Memory-Manipulator.git
cd Memory_Manipulator

# Build the application
dotnet build
```

### 2. Run the Application  
```sh
dotnet run
```

## How to Use  
1. **Select a process**: The program will display a list of open windows and their process IDs.  
2. **Enter a value to search for**: Input a number you want to find in memory.  
3. **Interact with the found addresses**:  
   - Display addresses  
   - Filter addresses based on a new value  
   - Modify an address value  
   - Manually change a specific memory address value  
4. **Restart or exit** the program.  

## Important Note  
To run the program with full memory manipulation rights, you must **run the application as an administrator**.  

## Security Notice  
Manipulating other processes' memory can lead to unpredictable consequences, including:  
- Crashing the target process  
- Security risks  
- Violating software usage policies  

Users are responsible for how they use this tool.  

## Author  
Aleksandar  

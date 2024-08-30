# C++ Cell Magic for Jupyter Notebooks

This project introduces a straightforward boilerplate code that empowers users to execute C++ code directly within Jupyter notebooks. By utilizing a custom cell magic command, this solution enables seamless integration of C++ programming within an interactive Python environment, enhancing the ability to test, debug, and demonstrate C++ code without needing to leave the notebook interface.

## Features

- **Inline C++ Execution:** This feature allows you to write C++ code directly in a Jupyter notebook cell and execute it with the `%%cpp` magic command. This integration eliminates the need for separate C++ IDEs or external terminal windows, streamlining the development process within a single interface.

- **Automatic Compilation:** The code you write is automatically compiled using the `g++` compiler. Upon execution, the C++ code is compiled into a binary, and this binary is run within the notebook. This feature ensures that you can immediately see the results of your code, making iterative development and testing more efficient.

- **Error Handling:** Any compilation errors encountered during the C++ code compilation are captured and displayed within the notebook. This feature simplifies debugging by providing immediate feedback on syntax errors or other issues, allowing for quick fixes and re-execution without leaving the notebook environment.
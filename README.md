# DebuggerAgent

**Problem Statement**
When you write a program with large number of files, it become increasingly difficult to debug.
Can we use an agent to do debug ?

**Solution**
we have built a watcher agent that traces every line of execution of the program.
After watching the every line of execution, the agent then leverages GPT to analyze the logical error in the code

**Steps to run the program**
An AutoGent Agent helping with debugging python programs
Please follow the following steps
1. pip install -r requirements.txt
2. python debugger.py <insert name of the python file>

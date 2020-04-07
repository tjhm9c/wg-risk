## 1. Description
The lines of code metric is the number of SLOC in a project. This metric allows organizations to understand the size of the code-base, and how much time and effort will be required to maintain it.
## 2. Use Cases
This metric can inform stakeholders about the maintainability of the code. A project with 10,000 SLOC will be harder to maintain that a project with 1,000.
## 3. Formula
num_lines = 0
for file in project:
  for line in file:
    num_lines += 1
## 4. Sample Filter and Visualization
https://github.com/computationalmystic/MU-Software-Engineering/graphs/code-frequency


## 5. Sample Implementation
https://github.com/computationalmystic/MU-Software-Engineering/graphs/code-frequency

## 6. Known Implementations
Look at github.
## 7. Test Cases (Examples)
Input: Some file
Output: Number of lines of code in the file.
## 8. External References (Literature)
https://www.ifpug.org/content/documents/Jones-LinesofCodeMetricV6.pdf

# MATRIX CALCULATOR
### Miniproject 
![Banner](https://github.com/hemanthasapu/256889-miniproject-ltts/blob/main/1_Requirements/Matrix.png)


Build | Code Quality | Unity | [Git Inspector](using github.io option)
------|----------|-------|--------------
[![C/C++ CI](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/c-cpp.yml) | [![Static Cppcheck](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/cppcheck.yml) [![Dynamic Valgrind](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/CodeQuality_Dynamic.yml/badge.svg)](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/CodeQuality_Dynamic.yml) | [![Unity - Unit Testing](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/unity.yml/badge.svg)](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/unity.yml)| [![Git Inspector](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/gitinspector.yml/badge.svg)](https://github.com/hemanthasapu/256889-miniproject-ltts/actions/workflows/gitinspector.yml)


## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

## Contributors List and Summary

SF Id. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
`256889` | Hemanth A | F_01, F_02, F_03, F_04, F_05, F_06, F_07   | None    | None   |7  |7    

| Feature Id | Feature |
| -----------|---------|
|F_01| Options to select matrix operation|
|F_02| Operations on two matrices such as addition, subtraction and multiplication are included|
|F_03| Single matrix operations such as determinant, transpose and inverse of a matrix |
|F_04| Separate function for each operation |
|F_05| A structure has been implemented for storing the matrices|
|F_06| Dynamic memory allocation and deallocation has been implemented for the matrices|
|F_07|  There is no upper limit for the size of the matrix|

## Challenges Faced and How Was It Overcome

| No. | Challenge | Solution
|-----|-----------|--------
|1. | Dynamic memory allocation of 2D arrays created segmentation faults| running the code in GDB helped find the line where the program crashes
|2. | Program crashes | Writing clean code with allocating and deallocating memory at all functions as per requirement|
|3. | Logical errors faced while designing matrix operations| Referred some articles to revise matrix basics and operations on 2D arrays
|4. | Unit testing on dynamic 2D array outputs| Created enumerated variables to be returned by those functions if the specified operation executes successfully

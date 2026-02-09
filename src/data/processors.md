# Processors
Processing units are responsible for taking input data, a specified task, any run-specific constraints, and using those to provide output in the contracted format.


## Input / handling tasks / output 
Input data will be provided such that data is capped at the minimum necessary while still ensuring sufficient context required to finish the task. 

Specified tasks will include details covering:
1. Which sub-tools are allowed for use
2. Fixed depleting resources available for the task (estimated and maximum)
    - Time
    - Proportion of total power available
    - Any others not mentioned, potentially not known
3. Permissible side effects
4. How to handle exceptional instances

Output will provide all contents requested by the task initiator. Output may be in the form of values, objects, files, or any other data-yielding item.  

Input, task handlers, and any output are all discarded after use. The input and task handlers are discarded once the output is provided, and the output is discarded at the initiator's discretion.


## Task optimization
Processors may demonstrate perceived strengths towards data depth or data breadth. That is a naive understanding.

Most processors have the same general ability to handle depth and breadth. Prior training and any auxiliary hardware will impact perceived reward during exploration. 

Understanding a processor's current abilities and limits will help optimally shape new training data.

Processors typically refine capabilities towards specific end goals. 

This doesn't necessarily mean specializing on exactly one task or one small field of tasks. Task specific processors will be optimized processors for this in scenarios where speed beats agility.

A fundamental set of working operations that can be applied generally allows adapting to new tasks as needed. Most processors only follow a relatively small set of operation codes (instruction machine codes), and more capable operations are built by wrapping prescribed behaviour around groups of these opcodes. 

Opcodes are enabled by infrastructure within the processor. Specific parts of the infrastructure may specifically enable certain opcodes, meaning: certain opcodes may have more hardware available for use during processing than others. 

A processor's limit is based on opcodes per second. Which opcodes have more hardware is handled on the basis of expected need during standard operation.

If any specialized task being run on a processor is found sufficiently worthy, changes may be made to better enable that specialized tasks operation: the addition of new opcodes, a rebalance of internal hardware, and in rare cases creation of entirely new components.

Reducing the opcodes required for a task enables the processor to carry out more tasks per unit time. 

New component creation usually involves combining existing capabilities into a single transistor. Then, operations that were previously handled using multiple opcodes can be handled using just one opcode.
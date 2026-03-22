# The third prompt
Hey. I need to study for a test in my C++ class. This test is on pointers and references and I would like you to make a test with 4 questions. The questions should be multiple choice. Make it specific and make the questions of a moderate difficulty. Include an answer key at the end with only the correct answers. Please don’t include extraneous information like encouragement or hints. Thanks!
## The response
To help you prepare for your C++ test, here are 4 moderate-difficulty multiple-choice questions focusing on pointers and references.
Pointers and References Practice Test
1. What is the output of the following code snippet?
cppCopyCopyint a = 10;
int &ref = a;
int *ptr = &ref;
*ptr = 20;
std::cout << a << " " << ref;

A) 10 10
B) 10 20
C) 20 20
D) 20 10
2. Which of the following statements regarding references is FALSE?
A) A reference must be initialized when it is declared.
B) A reference can be reassigned to refer to a different object after initialization.
C) A reference does not have its own memory address distinct from the object it refers to.
D) References cannot be null.
3. Given the declaration int arr[] = {10, 20, 30};, what does the expression *(arr + 1) evaluate to?
A) The memory address of the first element.
B) 10
C) 20
D) 30
4. Consider the function signature void update(int *const ptr). Which of the following operations is illegal inside this function?
A) *ptr = 50;
B) int x = *ptr;
C) ptr = nullptr;
D) std::cout << ptr;

Answer Key

C
B
C
C

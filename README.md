# Simple-Java-Quiz

> [!tips]
> Enjoy the code

## About

This is a simple quiz game created using java you can setn your questions and depending upon user answer the code will collect correct answers and display them at the end.

# Simple Java Quiz :-

## You can create menu interface like this :-

```java
// Question 1
        System.out.println("Question 1: What is the capital of France?");
        System.out.println("A) Berlin");
        System.out.println("B) London");
        System.out.println("C) Paris");
        System.out.println("D) Rome");
        System.out.print("Enter your answer: ");
        String answer1 = scanner.nextLine();
        if (answer1.equalsIgnoreCase("C")) {
            score++;
            System.out.println("Correct!\n");
        } else {
            System.out.println("Incorrect. The correct answer is C) Paris.\n");
        }
```
# Output :-

![image](https://github.com/user-attachments/assets/9ef03094-d440-4c64-97cd-d065fe3873ae)



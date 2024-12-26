# QUIZ
C language Quiz contest 

#include <stdio.h>

int main() {
    int score = 0;
    char answer;

    printf("Welcome to the Quiz!\n");

    // Question 1
    printf("1. Who is the father of C language?\n");
    printf("a) Steve Jobs\n");
    printf("b) James Gosling\n");
    printf("c) Dennis Ritchie\n");
    printf("d) Rasmus Lerdorf\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'c' || answer == 'C') {
        score++;
    }

    // Question 2
    printf("2.  Which of the following is not a valid C variable name?\n");
    printf("a) int number;\n");
    printf("b) Float rate;\n");
    printf("c) int variable_count;\n");
    printf("d) int $main;\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'd' || answer == 'D')
        {
        score++;
        }

    // Question 3
    printf("3. All keywords in C are in ____________\n");
    printf("a) LowerCase letters\n");
    printf("b) UpperCase letters\n");
    printf("c) CamelCase Letter\n");
    printf("d) None of the mentioned\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'a' || answer == 'A') {
        score++;
    }

    // Question 4
    printf("4.  What is short int in C programming?\n");
    printf("a) The basic data type of C\n");
    printf("b) Qualifier\n");
    printf("c) Short is the qualifier and int is the basic data type\n");
    printf("d) All of the mentioned.\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'c' || answer == 'C') {
        score++;
    }

    // Question 5
    printf("5. Which of the following declaration is not supported by C language?\n");
    printf("a) String str;\n");
    printf("b) char *str;\n");
    printf("c) float str;\n");
    printf("d) Both (String str) and (float str = 3e2;)\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'a' || answer == 'A') {
        score++;
    }

    // Question 6
    printf("6. What is an example of iteration in C?\n");
    printf("a) For\n");
    printf("b) While\n");
    printf("c) do-while\n");
    printf("d) all of the mentioned\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'd' || answer == 'D') {
        score++;
    }

    // Question 7
    printf("7. Functions can return enumeration constants in C?\n");
    printf("a) True\n");
    printf("b) False\n");
    printf("c) depends on the compiler\n");
    printf("d) depends on the standard\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'a' || answer == 'A') {
        score++;
    }

    // Question 8
    printf("8. Functions in C Language are always _________\n");
    printf("a) Internal\n");
    printf("b) External\n");
    printf("c) Both internal and External\n");
    printf("d) External and internal are not valid terms for functions\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'b' || answer == 'B') {
        score++;
    }

    // Question 9
    printf("9.  Which of the following are C preprocessors?\n");
    printf("a) #ifdef\n");
    printf("b) #define\n");
    printf("c) #endif\n");
    printf("d) all of the mentioned\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'd' || answer == 'D') {
        score++;
    }

    // Question 10
    printf("10. The C-preprocessors are specified with _________\n");
    printf("a) #\n");
    printf("b) $\n");
    printf("c) ''\n");
    printf("d) &\n");
    printf("Enter your answer (a, b, c, or d): ");
    scanf(" %c", &answer);
    if (answer == 'a' || answer == 'A') {
        score++;
    }

    // Print total score
    printf("Your total score is: %d out of 10\n", score);

    return 0;
}

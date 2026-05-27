# C-Quiz-Game-with-timer-
A console-based Quiz Game developed using C language with timer functionality, score calculation, and MCQ questions covering C programming topics.
#include <stdio.h>
#include <time.h>

int main() {

    int answer;
    int score = 0;
    time_t start, end;
    double time_taken;

    printf("=====================================\n");
    printf("     C PROGRAMMING QUIZ GAME\n");
    printf("=====================================\n");

    // Question 1
    printf("\nQ1. What is the extension of C file?\n");
    printf("1. .java\n2. .c\n3. .py\n4. .html\n");
    printf("You have 10 seconds!\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 2
    printf("\nQ2. Who is the Father of C language?\n");
    printf("1. Dennis Ritchie\n2. James Gosling\n3. Bill Gates\n4. Elon Musk\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 1) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 3
    printf("\nQ3. Which function is used for output?\n");
    printf("1. scanf()\n2. print()\n3. printf()\n4. input()\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 4
    printf("\nQ4. Which datatype is used for integers?\n");
    printf("1. float\n2. int\n3. char\n4. double\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 5
    printf("\nQ5. Which datatype stores decimal numbers?\n");
    printf("1. int\n2. char\n3. float\n4. long\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 6
    printf("\nQ6. Which symbol ends a statement in C?\n");
    printf("1. :\n2. ;\n3. #\n4. ,\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 7
    printf("\nQ7. Which operator is used for addition?\n");
    printf("1. -\n2. +\n3. *\n4. /\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 8
    printf("\nQ8. Which operator checks equality?\n");
    printf("1. =\n2. ==\n3. !=\n4. >=\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 9
    printf("\nQ9. Which loop executes at least once?\n");
    printf("1. for\n2. while\n3. do-while\n4. nested loop\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 10
    printf("\nQ10. Which keyword stops a loop?\n");
    printf("1. stop\n2. break\n3. continue\n4. return\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 11
    printf("\nQ11. Which loop is best when iterations are known?\n");
    printf("1. while\n2. do-while\n3. for\n4. switch\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 12
    printf("\nQ12. Which keyword returns value from function?\n");
    printf("1. stop\n2. break\n3. return\n4. continue\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 13
    printf("\nQ13. Which function is starting point of C program?\n");
    printf("1. start()\n2. main()\n3. run()\n4. init()\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 14
    printf("\nQ14. Which symbol is used for arrays?\n");
    printf("1. ()\n2. {}\n3. []\n4. <>\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 15
    printf("\nQ15. Array index starts from?\n");
    printf("1. 0\n2. 1\n3. -1\n4. 2\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 1) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 16
    printf("\nQ16. Which datatype is used for characters?\n");
    printf("1. int\n2. char\n3. float\n4. long\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 17
    printf("\nQ17. Which function is used to take input?\n");
    printf("1. printf()\n2. scanf()\n3. gets()\n4. putchar()\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 18
    printf("\nQ18. Which symbol is used for pointers?\n");
    printf("1. &\n2. *\n3. %%\n4. #\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 19
    printf("\nQ19. Which operator gives address of variable?\n");
    printf("1. *\n2. &\n3. %%\n4. @\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 20
    printf("\nQ20. Correct syntax for if statement?\n");
    printf("1. if x>0\n2. if(x>0)\n3. if{x>0}\n4. if[x>0]\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 21
    printf("\nQ21. Which header file is used for input/output?\n");
    printf("1. math.h\n2. string.h\n3. stdio.h\n4. conio.h\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 22
    printf("\nQ22. Which comment is single-line comment?\n");
    printf("1. ##\n2. %%\n3. //\n4. &&\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 23
    printf("\nQ23. Which keyword defines constant?\n");
    printf("1. fixed\n2. define\n3. const\n4. value\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 24
    printf("\nQ24. Which loop is entry-controlled?\n");
    printf("1. do-while\n2. while\n3. goto\n4. switch\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 2) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    // Question 25
    printf("\nQ25. Which keyword skips current iteration?\n");
    printf("1. break\n2. stop\n3. continue\n4. skip\n");

    time(&start);
    scanf("%d", &answer);
    time(&end);

    time_taken = difftime(end, start);

    if(time_taken > 10)
        printf("Time Over!\n");
    else if(answer == 3) {
        printf("Correct!\n");
        score++;
    }
    else
        printf("Wrong!\n");

    printf("\n=====================================\n");
    printf("FINAL SCORE = %d/25\n", score);
    printf("=====================================\n");

    return 0;
}
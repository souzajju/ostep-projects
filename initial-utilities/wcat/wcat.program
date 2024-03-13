#include <stdio.h>
#include <stdlib.h> 
#define BUFFER_SIZE (10)

int main (int argc, char*argv[])
{
    //FILE * fp = fopen (const char *restrict filename, const char *restrict mode);
    FILE * fp = fopen (argv[1], "r");
    if (fp == NULL)
    {
        printf("wcat: cannot open file\n");
        exit(1);
    }
    char buffer [BUFFER_SIZE];
        while (fgets(buffer, BUFFER_SIZE, fp) != NULL)
        printf("%s\n", buffer);
    
    fclose (fp);
    return 0;
}

#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
   //문자를 입력받는다
   string s = get_string("Input: ");
   
   //Output 출력
   printf("Output:\n");
    
   //입력받은 문자열(s)의 길이(strlen)만큼 반복한다
   for (int i = 0, n = strlen(s); i < n; i++)
   {
       //입력받은 문자(c)를 하나씩 출력
       //s[i], 입력받은 문자열(s)의 [i]번째 값을 한 글자(c)씩 출력
       printf("%c\n", s[i]);
   }
}

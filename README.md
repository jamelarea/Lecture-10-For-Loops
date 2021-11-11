# Lecture-10-For-Loops

SLIDE 5, For Loop Example

    #include <iostream>
    using namespace std;

    int main()
    {
        for (int x = 0; x < 10; x++) {
            cout << "X is " << x << "\n";
        }
    }
    
SLIDE 6, Countdown
    
    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int x = 10; x >= 0; x--)
        {
            cout << x << endl;
            if (x == 0) //when you read 0
                cout << "We have lift off!" << endl; //it will show this character output
        }
        return 0;
    }

SLIDE 7, Nested Loops

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int i = 0; i < 5; i++) { //execute the outer loop 5 times
            for (int j = 0; j < 5; j++) { //execute the inner loop 5 x 5 times
                cout << "*"; //print 5 stars
            }
            cout << endl; //print to a new console line
        }
        return 0;
    }
    
SLIDE 8, Nested Loops
    
    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int i = 1; i <= 5; i++) {
            for (int j = i; j <= 5; j++) { //execute the inner loop 5 times
                cout << "*"; //print reducing lines of stars
            }
            cout << endl; //print to a new console line
            //descending stars from 5 to 1
        }
        return 0;
    }
    
EXERCISE BREAK

SLIDE 10, Some counting

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int a = 0; a <= 50; a++) { //counts up from 0 to 50 in increments of 1
            cout << a << endl;
        }
        for (int b = 50; b >= 0; b--) { //counts down from 50 to 0 in decrements of 1
            cout << b << endl;
        }
        for (int c = 30; c <= 50; c++) { //counts up from 30 to 50 in increments of 1
            cout << c << endl;
        }
        for (int d = 50; d >= 10; d -= 2) { //counts down from 50 to 10 in decrements of 2
            cout << d << endl;
        }
        for (int e = 100; e <= 200; e += 5) { //counts up from 100 to 200 in increments of 5
            cout << e << endl;
        }
        return 0;
    }
    
SLIDE 11, Odd or Even

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int num = 20; num <= 24; num++) {
            if (num % 2 == 0) //if the number is divisible by 2
            {
                cout << num << " - Even" << endl; //character output for even
            }
            else //not divisible by 2
            {
                cout << num << " - Odd" << endl; //character output for odd
            }
        }
        return 0;
    }

SLIDE 12, Iterate through a word

    #include <iostream>
    #include <string>
    using namespace std;
    
    int main()
    {
        string myWord = "ARSH";

        cout << myWord.at(0) << endl;
        cout << myWord.at(1) << endl;
        cout << myWord.at(2) << endl;
        cout << myWord.at(3) << endl;
    }
    
SLIDE 13, Seven Stars, Seven Lines

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int i = 0; i < 7; i++) {
            for (int j = 0; j < 7; j++) {
                cout << "*";
            }
            cout << endl;
        }
        return 0;
    }
    
The For Loop Exercises

SLIDE 2, Descending Stars, Seven Lines

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int i = 1; i <= 7; i++) {
            for (int j = i; j <= 7; j++) { //execute the inner loop 7 times
                cout << "*"; //print lines of stars
            }
            cout << endl; //print to a new console line
            //stars from 7 to 1
        }
        return 0;
    }
    
SLIDE 3, Rising Stars, Five Lines

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) { //execute the inner loop 5 times
                cout << "*"; //print line of stars
            }
            cout << endl; //print to a new console line
            //stars from 1 to 5
        }
        return 0;
    }
    
SLIDE 4, Rising and Falling Stars

    #include <iostream>
    using namespace std;
    
    int main()
    {
        for (int i = 1; i <= 5; i++) {
            for (int j = 1; j <= i; j++) { //execute the inner loop 5 times
                cout << "*"; //print line of stars
            }
            cout << endl; //print to a new console line
            //stars from 1 to 5
        }
        return 0;
    }
    
SLIDE 5, Cubes

    #include <iostream>
    using namespace std;
    
    int main()
    {
        int i, num, cub; //variables

        cout << "Enter the number of integer = ";
        cin >> num;

        for (i = 1; i <= num; i++)
        {
            cub = i * i * i; //formula for cube
            cout << "Number is: " << i << " and the cube of " << i << " is: " << cub << endl;
        }
    }
    
SLIDE 6, Find the 9s

    #include <iostream>
    #include <string>
    using namespace std;
    
    int main()
    {
        int sum = 0;

        for (int num = 100; num <= 200; num++) {
            if (num % 9 == 0) {
                cout << num << endl;
                sum = sum + num;
            }
        }
        cout << "\nSum = " << sum << endl;
        return 0;
    }
    

    

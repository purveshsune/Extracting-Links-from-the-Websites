# Extracting-Links-From-Websites-Using-BeautifulSoup

•	Sample problem: Start at http://py4e-data.dr-chuck.net/known_by_Fikret.html

Find the link at position 3 (the first name is 1). Follow that link. Repeat this process 4 times. The answer is the last name that you retrieve.

Sequence of names: Fikret Montgomery Mhairade Butchi Anayah

Last name in sequence: Anayah

•	Actual problem: Start at: http://py4e-data.dr-chuck.net/known_by_Soukina.html

Find the link at position 18 (the first name is 1). Follow that link. Repeat this process 7 times. The answer is the last name that you retrieve.

Hint: The first character of the name of the last page that you will load is: B
Strategy

The web pages tweak the height between the links and hide the page after a few seconds to make it difficult for you to do the assignment without writing a Python program. But frankly with a little effort and patience you can overcome these attempts to make it a little harder to complete the assignment without writing a Python program. But that is not the point. The point is to write a clever Python program to solve the program.

Sample execution
Here is a sample execution of a solution:

$ python3 solution.py

Enter URL: http://py4e-data.dr-chuck.net/known_by_Fikret.html

Enter count: 4

Enter position: 3

Retrieving: http://py4e-data.dr-chuck.net/known_by_Fikret.html

Retrieving: http://py4e-data.dr-chuck.net/known_by_Montgomery.html

Retrieving: http://py4e-data.dr-chuck.net/known_by_Mhairade.html

Retrieving: http://py4e-data.dr-chuck.net/known_by_Butchi.html

Retrieving: http://py4e-data.dr-chuck.net/known_by_Anayah.html

The answer to the assignment for this execution is "Anayah".

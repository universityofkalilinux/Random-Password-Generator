This Python program generates a list of potential passwords based on specified keywords, numbers, and special characters. The primary purpose is to create a diverse set of password combinations that can be used for testing security measures or for educational purposes related to password strength.

Key Features:
Keywords: The program uses two predefined keywords, "universitykalilinux" and "universityofkalilinux". These keywords are transformed into both lowercase and uppercase forms to increase the variety of generated passwords.

Numbers: A list of numeric strings (`'123'`, `'2025'`, `'456'`, and `'789'`) is included to append or prepend to the keywords, enhancing the complexity of the passwords.

Special Characters: The program incorporates a selection of special characters (`'!'`, `'@'`, `'#'`, `'$'`, `'%'`, `'^'`, `'&'`, and `'*'`) to further diversify the password combinations.

Combination Logic: The program employs nested loops to create various combinations of the keywords, numbers, and special characters. It generates:
   - Keyword followed by number
   - Number followed by keyword
   - Keyword followed by special character
   - Special character followed by keyword
   - Keyword followed by number followed by special character
   - Special character followed by number followed by keyword

Unique Passwords: A set is used to store the generated passwords, ensuring that all entries are unique and eliminating any duplicates.

Output: The generated passwords are written to a text file named `password_list.txt`, with each password on a new line.
User Notification: After successfully generating and saving the password list, the program prints a confirmation message to the console.

Usage:
This program can be useful for security professionals, educators, or anyone interested in understanding password generation techniques and the importance of using varied character types in creating strong passwords.


How to Use it:
git clone https://github.com/universityofkalilinux/WebAdminFinder.git
sudo python randompasswordgenerator.py

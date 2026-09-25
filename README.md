# CS50P-python-My-_Final_Project-


# PASSWORD VALIDATION CHECKER #

#### Video Demo: https://youtu.be/vLTjLGAdxEI

#### Description: In a new world that we're living in, full of easy/simple passwords made just to guarantee remembering them, we need to make people aware of the danger that faces their data by helping them and making it easier to know whether a password is SECURE enough or needs to REGENERATE a strong one.

And simply, that is my project's goal:

__In the project.py file__

1. Asking the user to input the password they want to check in a hidden way (pwinput.pwinput(...)) and their name as an extra step to guarantee the validation of the password.

2. Checking the password via (check_password_strength).

3. Returning back to them the entropy of their password, a security "%" score the password collected, and notes on what is missing for it to be better and more secure.

4. Asking the user whether they want the program to generate a new, stronger password or not, by offering two options (y/n).

__In the test_project file__

We will be testing three functions:

1. test_entropy(): the first assertion is that a mixed-type password is better than a one-type password, e.g. ("rrrrrrrr" < "aB3!AcB3!").

   The second assertion tests the mathematical formula (len(password) * math.log2(pool_size)).

   The third one asserts that an empty password equals 0 entropy.

2. test_password_strength(): will be testing some important options that a password must include, e.g. (password length validation, contains name?, contains digits and symbols?).

3. The last test is test_password_with_requested_len(): the simplest test, which only checks whether the length matches the requested password length.

__In the requirements.txt file__

You will find all the requirements for this project and any pip-installable libraries that the project needs.

IMPORTANT NOTE!: I believe this project would be even stronger with further development, and I admit it needs more details to make it completely dependable for this goal... but as CS50 reminds us, "Be proud of it!" and luckily, I am because i learnd alot from it — and I promise to keep working on it... Thanks, CS50 staff and dear professor.
    

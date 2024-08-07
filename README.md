# Library-membership-issuance-system

Please open the XML using UPPAAL.

This project was made for the assignment component of the course Logic in Computer Science, CS F214.

The model was made for the following problem statement: 

    You are required to model a library membership issuance system in UPPAAL based on the following specifications.

    Every time the user wants to issue a book or buy a membership, s/he should sign in to the system using their email ID.

    For each sign-in, the system should authenticate the details. In case the authentication fails, users have to check their credentials and sign in again.

    On signing-in, the user has two options:

    > Buy a membership card

    > View membership details/history

    The membership card is of 2 types: Gold and Platinum, with different rates. Users can only purchase one type of membership at a time (in one transaction).

    If the membership card is bought, the payment should be made before exiting the system. There is only one mode of payment i.e. via Credit/Debit card.

    Users should log out of the system after every transaction.

    You have to additionally model the payment system from the bank’s point of view. The transaction will only be approved by the bank if there is sufficient balance in the account.

    Additionally, verify any 2 safety and liveness properties each on this template using UPPAAL. Clearly state those properties in your submission.

Refer UPPAAL_readme_model.pdf for understanding the model.

Credits - Madhav Gupta (2022A7PS0078P), Subham Pan (2022A7PS0141P), Ritvik Singh (2022A7PS0045P)
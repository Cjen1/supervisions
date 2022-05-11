# Higher level attacks

- SQL injection
  - What is it?
  - What are safe-strings?
  - Outline input sanitisation
  - Outline the general approach to SQL injection

- Passwords
  - Outline why passwords are a generally terrible approach (XKCD is relevant here)
  - Why is storing passwords in plaintext a bad idea?
  - What can go wrong with storing passwords in a hashed form
  - Why does salting fix this?
  - Outline why password reuse is so common
  - Outline why password reuse is a terrible idea
  - What is a rainbow table?
  - Outline the benefits of a password manager?
  - What is a replay attack?
    - (optional) how could you mitigate a replay attack?

- Cross site request forgery and Cross-Site Scripting
  - What is CSRF
  - What is XSS
  - How can we use XSS to gift ourselfs steam keys using the reviews on steam (Assume they haven't sanitised their reviews)
  - Outline input-as-output

- Human factors
  - Outline Prospect Theory and apply it to the Ticks in the CST course
  - Discuss the following aspects of scams:
    - Distraction
    - Social Compliance
    - Herd mentality
    - Dishonesty
    - Deception
    - Need and greed
    - Time
  - (very optional but recommended) read "The art of deception" by kevin mitnick 

- Malware
  - What is malware
  - What is the purpose of the following
    - Spyware
    - Adware
    - Ransomware
  - Choose one (or more) of the following, outline the purpose, attack vector and impact
    - Stuxnet worm
    - Wannacry
    - NotPetya
  - What is a 0-day?
  - Write a program which prints itself

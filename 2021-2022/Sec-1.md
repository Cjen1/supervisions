# Low level exploits

- Abstractions
  - Why are they useful?
  - What can happen if they break?
  - Why is it necessary to understand the underlying system for any abstraction to build high performance, safe and secure systems?

- Give examples of a trusted entity
- What is the principle of least privilege

- Physical security
  - What is the purpose of locks?
  - Discuss destructive and non-destructive methods of breaking into a locked door
  - (very optional) Learn how to pick locks (I'll try to bring in a practise lock for the supervision)

- Access control
  - How does POSIX security work?
    - Access control bits
    - chmod
    - umaks
    - What do the various access control bits mean for:
      - files 
      - directories?
    - What are the setuid/setgid bits?
    - Which permissions do you get?

- What is privilege escalation
  - Why is it a problem?
  - Outline the problem with unsanitized strings
  - What is the general approach to finding these kind of attacks?
    - Why is this similar to debugging?

- What is a buffer overflow?
  - How can we use this to launch an attack?
  - Why is this mitigated in every reasonable language? (ie not c or c++)
  - What does the call stack look like?
  - How does ASLR work and how can it make buffer overflow more difficult.
  - Outline function calling conventions
  - What is a foreign function call and why might it be a source of bugs and exploits?
  - What is return oriented programming and how would we achieve such an attack (this is the more general form of return-to-libc)?
  - Outline how sleds are used in ROP
  - Outline the layout and contents of a programs memory when it is initially loaded and discuss how this could be used to attack the code
  - (optional) outline the rowhammer attack and discuss how it is similar to a buffer overflow attack
  - (optional) hows the CHERI project fix some of these problems?

- TCP
  - Outline the purpose of scapy and wireshark
  - What is the problem with plaintext communication links? (eg old wifi routers, or HTTP traffic)
  - Outline the Man-in-the-middle attack


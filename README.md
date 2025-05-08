# Fiber-based-Injection
A full working POC of Fiber-based Injection 

Must add a custom encryption scheme, either xor or AES. This will only fail to pass static detection if it can see the payload.

I have a new idea for storing shellcode in an obfuscated way and that is to store each char into a struct and add each char together to build the total shellcode. I would like to see an EDR guess a signature from a single char ;). But this is for a future write-up

This is ready to run and have a payload added

Uses 2 fibers within the thread to throw EDRs off by building and loading the shellcode in 2 differnt fibers withing a remote thread

For the full zine entry visit: 

https://sleepyg8.github.io/FiberInjection.html



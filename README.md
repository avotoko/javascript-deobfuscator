# jsdfe: JavaScript Deobfuscator Full of Excuses
- The purpose of this program is to make obfuscated scripts easier to read and help you understand their roughly behavior, not to try to reproduce the original code or output executable code.
- This program is built on nodejs and babel.
- I developed this program for my own use. It often terminates with an uncaught error and sometimes goes into an infinite loop and freezes and executes some code of the target script in VM without considering security. VM is implemented as iframe[sandbox=""] and its document has Content-Security-Policy:default-src 'self'; script-src 'unsafe-eval'. You can test the security/vulnerability of VM by placing any code in the input box and clicking [Run code in vm(iframe)]. See the results in the Developer Tools. 
- The progress is output to the console of the developer tools.
- Please make sure you understand the above before executing.
- Try it here: https://avotoko.github.io/javascript-deobfuscator/

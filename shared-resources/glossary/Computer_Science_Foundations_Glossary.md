# Computer Science Foundations — Shared Glossary

**Audience:** First-year students with no assumed programming experience  
**Applies to:** C++20, Python, Java, and Visual Basic introductory textbooks  
**Status:** Working master glossary, version 0.1 (October 2026)

This glossary supports the shared, language-independent introductory chapter. Definitions are written for beginners; individual language textbooks may add specialized terms later. Terms from the Chapter 1 production plan are retained and expanded with foundational concepts planned for the chapter. The glossary is a teaching resource, not a substitute for formal standards.

## A

**Algorithm**  
A finite set of clear steps for completing a task or solving a problem. An algorithm can be described in ordinary language, a flowchart, pseudocode, or program code.

**ASCII (American Standard Code for Information Interchange)**  
A character-encoding standard that assigns numeric values from 0 through 127 to letters, digits, punctuation, and control characters. Tables showing values 128–255 use some additional encoding and are not standard 7-bit ASCII.

## B

**Binary**  
A base-2 positional number system that uses only the digits 0 and 1. For example, `1010₂` represents decimal 10.

**Bit**  
A binary digit whose value is 0 or 1. A physical switch can model a bit, but a bit is a unit of information, not the switch itself.

**Byte**  
A unit of digital data. In modern general-purpose computing it is usually eight bits, although some programming environments define a byte differently. See **Octet**.

## C

**Character**  
A letter, digit, punctuation mark, symbol, or other unit of text. A character is not necessarily stored as one byte.

**Character encoding**  
A set of rules for representing text as stored or transmitted data. ASCII and UTF-8 are examples, although they cover different ranges and use different rules.

**Code point**  
A numeric value assigned to a character or other text element in a character set such as Unicode. For example, the letter `A` has Unicode code point `U+0041`.

**Compiler**  
A program that translates source code into another form, often machine code or an intermediate representation, so it can be executed later or by another program.

**Computer**  
An electronic system that processes information by following instructions. Computers take many forms, including laptops, phones, embedded controllers, and servers.

**Control character**  
A character code used for control functions rather than a normally printed symbol. ASCII examples include line feed (`LF`) and escape (`ESC`).

## D

**Data**  
Information represented in a form a computer can store, process, or transmit, such as numbers, text, pictures, and sound.

**Debugging**  
Finding and correcting the causes of errors or unexpected behavior in a program or algorithm.

**Decimal**  
The base-10 positional number system using digits 0 through 9.

**Directory (folder)**  
A container used by a file system to organize files and other directories.

## E

**Executable program**  
A program in a form that a computing environment can run. Not every language produces a standalone executable file.

## F

**File**  
A named collection of data stored by a computer, such as a document, picture, or source-code file.

**File extension**  
The suffix of a filename, often used to suggest its format or associated application, such as `.txt` or `.png`. An extension alone does not guarantee the file's actual contents.

**File system**  
The method an operating system or device uses to name, organize, store, and retrieve files.

**Flowchart**  
A diagram that represents steps and decisions in a process using shapes and connecting arrows.

## H

**Hardware**  
The physical parts of a computing system, such as its processor, memory, keyboard, and storage device.

**Hexadecimal**  
A base-16 positional number system using digits 0–9 and letters A–F. For example, `10₁₆` represents decimal 16. Each hexadecimal digit corresponds to four binary digits.

## I

**Input**  
Data or signals received by a computer or process, such as keyboard entry, sensor readings, or a file being read.

**Interpreter**  
A program that executes instructions from a source or intermediate representation. Real language implementations may combine interpretation and compilation.

## L

**Logic error**  
An error in a program's reasoning or algorithm that produces an incorrect result even when the program runs.

## M

**Machine code**  
Instructions encoded in a form a particular processor can execute directly.

**Memory (RAM)**  
Working storage used by a computer while programs and data are in use. Its contents are generally lost when power is removed.

## O

**Octal**  
A base-8 positional number system using digits 0 through 7. It is different from an **octet**.

**Octet**  
A group of exactly eight bits, regardless of the byte size used by a particular programming environment.

**Operating system**  
Software that manages computer resources and provides services for applications and users.

**Output**  
Data or signals produced by a computer or process, such as text on a screen, sound from a speaker, or a saved file.

## P

**Pixel**  
A picture element or sample in a raster image. Pixels describe image data; physical display subpixels are a related but different concept.

**Positional number system**  
A system in which a digit's value depends on its position and the base. In decimal, the digits of 159 represent hundreds, tens, and ones.

**Processing**  
Operations performed on data according to instructions, such as calculating, comparing, sorting, or transforming it.

**Program**  
A collection of instructions intended for a computer to execute.

**Programming language**  
A formal language used to express instructions and algorithms for computers.

**Pseudocode**  
A human-readable description of an algorithm that resembles programming instructions without requiring the exact syntax of a particular language.

## R

**Register**  
A small storage location used inside a processor or digital circuit. The classroom switch simulator models groups of bits as registers; its on-screen switches are a teaching representation.

**RGB (red, green, blue)**  
A way of representing color with red, green, and blue components. Many common digital images use eight bits per component, but other bit depths and color representations exist.

**Runtime error**  
A problem that occurs while a program is executing, such as attempting an invalid operation or accessing an unavailable resource.

## S

**Sequence**  
The execution of steps in a particular order.

**Software**  
Programs and related data that direct a computer's behavior.

**Source code**  
Human-readable instructions written in a programming language.

**Storage**  
A way to retain data for later use, such as a solid-state drive or other persistent medium. Unlike RAM, persistent storage normally keeps data when power is off.

**Syntax**  
The rules governing how instructions must be written in a particular programming language.

**Syntax error**  
An error in the written structure of code that violates a language's rules and may prevent translation or execution.

## T

**Testing**  
Running or examining a program or algorithm with chosen inputs and expected outcomes to identify problems and assess whether it behaves as intended.

## U

**Unicode**  
A standard for representing text across many languages and writing systems. It assigns code points to characters and other text elements; UTF-8 is one way to encode Unicode text as bytes.

**Unary (tally representation)**  
A way to represent a quantity by repeating a mark, such as `||||` for four. This is a useful classroom contrast with positional number systems; conventions for representing zero vary.

**UTF-8**  
A variable-length encoding of Unicode code points using one to four bytes. For example, `A` is encoded as hexadecimal byte `41`, while `é` (U+00E9) is encoded as `C3 A9`.

## V

**Version control**  
A method for recording and managing changes to files over time. Git is a version-control system; hosting a repository online is a separate service and is not automatically a complete backup strategy.

## Additional instructional notes

- **Number bases:** `10₂ = 2₁₀`, `10₁₀ = 10₁₀`, and `10₁₆ = 16₁₀`. The same written digits can represent different values depending on the base.
- **Bits and switches:** A switch is an analogy for two states. Actual computers may represent bits using electrical, magnetic, or other physical states.
- **Text:** Do not equate a character, Unicode code point, glyph, and byte. They are related concepts, but not interchangeable.
- **Errors:** Syntax, runtime, and logic errors are useful beginner categories, though real failures may overlap.
- **Flow of a lesson:** Explanation → Demonstration → Practical Application, with Predict → Test → Explain activities where helpful.

## Maintenance and contribution notes

This is the **shared foundation glossary**, not the final complete glossary for every language. Add new terms as chapters are edited, and record technical reviews before treating definitions as final. Suggested metadata for a future CSV or LMS export: `term_id`, `term`, `definition`, `first_lesson_id`, `language_notes`, `review_status`.

For the companion GitHub repository, place this file at `shared-resources/glossary/Computer_Science_Foundations_Glossary.md` and link to it from the repository's main `README.md`. This is a proposed path, not an existing repository link.



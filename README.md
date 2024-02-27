# [go back to overview](https://github.com/c4arl0s#main-projects)

# [Regular Expression - Content](https://github.com/c4arl0s/RegularExpressions#go-back-to-overview)

1. [x] [1. Regular Expression Tutorial - Content](https://github.com/c4arl0s/RegularExpressions#1-regular-expression-tutorial)
    * [x] [What Regular Expressions Are Exactly - Terminology](https://github.com/c4arl0s/RegularExpressions#-what-regular-expressions-are-exactly---terminology)
    * [x] [Different Regular Expression Engines](https://github.com/c4arl0s/RegularExpressions#-different-regular-expression-engines)
    * [x] [Give Regexes a First Try](https://github.com/c4arl0s/RegularExpressions#-give-regexes-a-first-try)
2. [x] [2. Literal Characters](https://github.com/c4arl0s/RegularExpressions#2-literal-characters)
    * [x] [Special Characters](https://github.com/c4arl0s/RegularExpressions#-special-characters)
    * [x] [Special Characters and Programming Languages](https://github.com/c4arl0s/RegularExpressions#-special-characters-and-programming-languages)
    * [x] [Non-Printable Characters](https://github.com/c4arl0s/RegularExpressions#-non-printable-characters)
3. [x] [3. First Look at How a Regex Engine Works Internally](https://github.com/c4arl0s/RegularExpressions#3-first-look-at-how-a-regex-engine-works-internally)
    * [The Regex-Directed Engine Always Returns the Leftmost Match](https://github.com/c4arl0s/RegularExpressions#-the-regex-directed-engine-always-returns-the-leftmost-match)
4. [x] [4. Character Classes or Character Sets](https://github.com/c4arl0s/RegularExpressions#4-character-classes-or-character-sets)
    * [x] [Useful Applications](https://github.com/c4arl0s/RegularExpressions#-useful-applications)
    * [x] [Negated Character Classes](https://github.com/c4arl0s/RegularExpressions#-negated-character-classes)
    * [x] [Metacharacters Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#-metacharacters-inside-character-classes)
    * [x] [Shorthand Character Classes](https://github.com/c4arl0s/RegularExpressions#17-lookahead-and-lookbehind-zero-width-assertions)
    * [x] [Negated Shorthand Character Classes](https://github.com/c4arl0s/RegularExpressions#-negated-shorthand-character-classes)
    * [x] [Repeating Character Classes](https://github.com/c4arl0s/RegularExpressions#-repeating-character-classes)
    * [x] [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine)
5. [x] [5. The Dot Matches (Almost) Any Character](https://github.com/c4arl0s/RegularExpressions#5-the-dot-matches-almost-any-character-)
    * [x] [Use The Dot Sparingly](https://github.com/c4arl0s/RegularExpressions#-use-the-dot-sparingly)
    * [x] [Use Negated Character Sets Instead of the Dot](https://github.com/c4arl0s/RegularExpressions#-use-negated-character-sets-instead-of-the-dot)
6. [x] [6. Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#6-start-of-string-and-end-of-string-anchors)
    * [x] [Useful Applications](https://github.com/c4arl0s/RegularExpressions#-useful-applications-for-6)
    * [x] [Using ^ and $ as Start of Line and End of Line Anchors](https://github.com/c4arl0s/RegularExpressions#-using--and--as-start-of-line-and-end-of-line-anchors)
    * [x] [Permanent Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#-permanent-start-of-string-and-end-of-string-anchors)
    * [x] [Zero-Length Matches](https://github.com/c4arl0s/RegularExpressions#-zero-length-matches)
    * [x] [Strings Ending with a Line Break](https://github.com/c4arl0s/RegularExpressions#-strings-ending-with-a-line-break)
    * [x] [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-1)
    * [x] [Another Inside Look](https://github.com/c4arl0s/RegularExpressions#-another-inside-look)
    * [x] [Caution for Programmers](https://github.com/c4arl0s/RegularExpressions#-caution-for-programmers)
7. [x] [7. Word Boundaries](https://github.com/c4arl0s/RegularExpressions#7-word-boundaries)
    * [x] [Negated Word Boundary](https://github.com/c4arl0s/RegularExpressions#-negated-word-boundary)
    * [x] [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-2)
    * [x] [Tcl Word Boundaries](https://github.com/c4arl0s/RegularExpressions#-tcl-word-boundaries)
8. [x] [8. Alternation with The Vertical Bar or Pipe Symbol](https://github.com/c4arl0s/RegularExpressions#8-alternation-with-the-vertical-bar-or-pipe-symbol)
    * [x] [Remember That The Regex Engine Is Eager](https://github.com/c4arl0s/RegularExpressions#-remember-that-the-regex-engine-is-eager)
9. [x] [9. Optional Items](https://github.com/c4arl0s/RegularExpressions#9-optional-items)
    * [x] [Important Regex Concept: Greediness](https://github.com/c4arl0s/RegularExpressions#-important-regex-concept-greediness)
    * [ ] [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-3)
<!---10. [ ] [10. Repetition with Star and Plus](https://github.com/c4arl0s/RegularExpressions#10-repetition-with-star-and-plus)
    * [ ] [Limiting Repetition](https://github.com/c4arl0s/RegularExpressions#-limiting-repetition)
    * [ ] [Watch Out for The Greediness!](https://github.com/c4arl0s/RegularExpressions#-watch-out-for-the-greediness)
    * [ ] [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-4)
    * [ ] [Laziness Instead of Greediness](https://github.com/c4arl0s/RegularExpressions#-laziness-instead-of-greediness)
    * [ ] [An Alternative to Laziness](https://github.com/c4arl0s/RegularExpressions#-an-alternative-to-laziness)
    * [ ] [Repeating \Q...\E Escape Sequences](https://github.com/c4arl0s/RegularExpressions#-repeating-qe-escape-sequences)
11. [ ] [11. Use Round Brackets for Grouping](https://github.com/c4arl0s/RegularExpressions#11-use-round-brackets-for-grouping)
    * [ ] [Round Brackets Create a Backreference](https://github.com/c4arl0s/RegularExpressions#-round-brackets-create-a-backreference)
    * [ ] [How to Use Backreferences](https://github.com/c4arl0s/RegularExpressions#-how-to-use-backreferences)
    * [ ] [The Entire Regex Match As Backreference Zero](https://github.com/c4arl0s/RegularExpressions#-the-entire-regex-match-as-backreference-zero)
    * [ ] [Using Backreferences in The Regular Expression](https://github.com/c4arl0s/RegularExpressions#-using-backreferences-in-the-regular-expression)
    * [ ] [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-5)
    * [ ] [Repetition and Backreferences](https://github.com/c4arl0s/RegularExpressions#-repetition-and-backreferences)
    * [ ] [Useful Example: Checking for Doubled Words](https://github.com/c4arl0s/RegularExpressions#-useful-example-checking-for-doubled-words)
    * [ ] [Parentheses and Backreferences Cannot Be Used Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#-parentheses-and-backreferences-cannot-be-used-inside-character-classes)
12. [ ] [12. Named Capturing Groups](https://github.com/c4arl0s/RegularExpressions#12-named-capturing-groups)
    * [ ] [Named Capture with Python, PCRE and PHP](https://github.com/c4arl0s/RegularExpressions#-named-capture-with-python-pcre-and-php)
    * [ ] [Named Capture with .NET’s System.Text.RegularExpressions](https://github.com/c4arl0s/RegularExpressions#-named-capture-with-nets-systemtextregularexpressions)
    * [ ] [Names and Numbers for Capturing Groups](https://github.com/c4arl0s/RegularExpressions#-names-and-numbers-for-capturing-groups)
    * [ ] [Other Regex Flavors](https://github.com/c4arl0s/RegularExpressions#-other-regex-flavors)
13. [ ] [13. Unicode Regular Expressions](https://github.com/c4arl0s/RegularExpressions#13-unicode-regular-expressions)
    * [ ] [Characters, Code Points and Graphemes or How Unicode Makes a Mess of Things](https://github.com/c4arl0s/RegularExpressions#-characters-code-points-and-graphemes-or-how-unicode-makes-a-mess-of-things)
    * [ ] [How to Match a Single Unicode Grapheme](https://github.com/c4arl0s/RegularExpressions#-how-to-match-a-single-unicode-grapheme)
    * [ ] [Matching a Specific Code Point](https://github.com/c4arl0s/RegularExpressions#-matching-a-specific-code-point)
    * [ ] [Unicode Character Properties](https://github.com/c4arl0s/RegularExpressions#-unicode-character-properties)
    * [ ] [Unicode Scripts](https://github.com/c4arl0s/RegularExpressions#-unicode-scripts)
    * [ ] [Unicode Blocks](https://github.com/c4arl0s/RegularExpressions#-unicode-blocks)
    * [ ] [Alternative Unicode Regex Syntax](https://github.com/c4arl0s/RegularExpressions#-alternative-unicode-regex-syntax)
    * [ ] [Do You Need To Worry About Different Encodings?](https://github.com/c4arl0s/RegularExpressions#-do-you-need-to-worry-about-different-encodings)
14. [ ] [14. Regex Matching Modes](https://github.com/c4arl0s/RegularExpressions#14-regex-matching-modes)
    * [ ] [Specifying Modes Inside The Regular Expression](https://github.com/c4arl0s/RegularExpressions#-specifying-modes-inside-the-regular-expression)
    * [ ] [Turning Modes On and Off for Only Part of The Regular Expression](https://github.com/c4arl0s/RegularExpressions#-turning-modes-on-and-off-for-only-part-of-the-regular-expression)
    * [ ] [Modifier Spans](https://github.com/c4arl0s/RegularExpressions#-modifier-spans)
15. [ ] [15. Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#15-possessive-quantifiers)
    * [ ] [How Possessive Quantifiers Work](https://github.com/c4arl0s/RegularExpressions#-how-possessive-quantifiers-work)
    * [ ] [When Possessive Quantifiers Matter](https://github.com/c4arl0s/RegularExpressions#-when-possessive-quantifiers-matter)
    * [ ] [Possessive Quantifiers Can Change The Match Result](https://github.com/c4arl0s/RegularExpressions#-possessive-quantifiers-can-change-the-match-result)
    * [ ] [Using Atomic Grouping Instead of Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#-using-atomic-grouping-instead-of-possessive-quantifiers)
16. [ ] [16. Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#16-atomic-grouping)
    * [ ] [Regex Optimization Using Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#-regex-optimization-using-atomic-grouping)
17. [ ] [17. Lookahead and Lookbehind Zero-Width Assertions](https://github.com/c4arl0s/RegularExpressions#17-lookahead-and-lookbehind-zero-width-assertions)
    * [ ] [Positive and Negative Lookahead](https://github.com/c4arl0s/RegularExpressions#-positive-and-negative-lookahead)
    * [ ] [Regex Engine Internals](https://github.com/c4arl0s/RegularExpressions#-regex-engine-internals)
    * [ ] [Positive and Negative Lookbehind](https://github.com/c4arl0s/RegularExpressions#-positive-and-negative-lookbehind)
    * [ ] [More Regex Engine Internals](https://github.com/c4arl0s/RegularExpressions#-more-regex-engine-internals)
    * [ ] [Important Notes About Lookbehind](https://github.com/c4arl0s/RegularExpressions#-important-notes-about-lookbehind)
    * [ ] [Lookaround Is Atomic](https://github.com/c4arl0s/RegularExpressions#-lookaround-is-atomic)
18. [ ] [18. Testing The Same Part of a String for More Than One Requirement](https://github.com/c4arl0s/RegularExpressions#18-testing-the-same-part-of-a-string-for-more-than-one-requirement)
    * [ ] [Lookaround to The Rescue](https://github.com/c4arl0s/RegularExpressions#-lookaround-to-the-rescue)
    * [ ] [Optimizing Our Solution](https://github.com/c4arl0s/RegularExpressions#-optimizing-our-solution)
    * [ ] [A More Complex Problem](https://github.com/c4arl0s/RegularExpressions#-a-more-complex-problem)
19. [ ] [19. Continuing at The End of The Previous Match](https://github.com/c4arl0s/RegularExpressions#19-continuing-at-the-end-of-the-previous-match)
    * [ ] [End of The Previous Match vs. Start of The Match Attempt](https://github.com/c4arl0s/RegularExpressions#-end-of-the-previous-match-vs-start-of-the-match-attempt)
    * [ ] [\G Magic with Perl](https://github.com/c4arl0s/RegularExpressions#-g-magic-with-perl)
    * [ ] [\G in Other Programming Languages](https://github.com/c4arl0s/RegularExpressions#-g-in-other-programming-languages)
20. [ ] [20. If-Then-Else Conditionals in Regular Expressions](https://github.com/c4arl0s/RegularExpressions#20-if-then-else-conditionals-in-regular-expressions)
    * [ ] [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-6)
    * [ ] [Regex Flavors](https://github.com/c4arl0s/RegularExpressions#-regex-flavors)
    * [ ] [Example: Extract Email Headers](https://github.com/c4arl0s/RegularExpressions#-example-extract-email-headers)
21. [ ] [21. XML Schema Character Classes ](https://github.com/c4arl0s/RegularExpressions#21-xml-schema-character-classes-)
    * [ ] [Character Class Subtraction](https://github.com/c4arl0s/RegularExpressions#-character-class-subtraction)
    * [ ] [Nested Character Class Subtraction](https://github.com/c4arl0s/RegularExpressions#-nested-character-class-subtraction)
    * [ ] [Notational Compatibility with Other Regex Flavors](https://github.com/c4arl0s/RegularExpressions#-notational-compatibility-with-other-regex-flavors)
22. [ ] [22. POSIX Bracket Expressions](https://github.com/c4arl0s/RegularExpressions#22-posix-bracket-expressions)
    * [ ] [Character Classes](https://github.com/c4arl0s/RegularExpressions#-character-classes)
    * [ ] [Collating Sequences](https://github.com/c4arl0s/RegularExpressions#-collating-sequences)
    * [ ] [Character Equivalents](https://github.com/c4arl0s/RegularExpressions#-character-equivalents)
23. [ ] [23. Adding Comments to Regular Expressions](https://github.com/c4arl0s/RegularExpressions#23-adding-comments-to-regular-expressions)
24. [ ] [24. Free-Spacing Regular Expressions](https://github.com/c4arl0s/RegularExpressions#24-free-spacing-regular-expressions)
    * [ ] [Comments in Free-Spacing Mode](https://github.com/c4arl0s/RegularExpressions#-comments-in-free-spacing-mode)

Examples

1. [Sample Regular Expression](https://github.com/c4arl0s/RegularExpressions#1-sample-regular-expression)
2. [Matching Floating Point Numbers with a Regular Expression](https://github.com/c4arl0s/RegularExpressions#2-matching-floating-point-numbers-with-a-regular-expression)
3. [How to Find or Validate an Email Address](https://github.com/c4arl0s/RegularExpressions#3-how-to-find-or-validate-an-email-address)
4. [Matching a Valid Date](https://github.com/c4arl0s/RegularExpressions#4-matching-a-valid-date)
5. [Matching Whole Lines of Text](https://github.com/c4arl0s/RegularExpressions#5-matching-whole-lines-of-text)
6. [Deleting Duplicate Lines From a File ](https://github.com/c4arl0s/RegularExpressions#6-deleting-duplicate-lines-from-a-file-)
8. [Find Two Words Near Each Other](https://github.com/c4arl0s/RegularExpressions#8-find-two-words-near-each-other)
9. [Runaway Regular Expressions: Catastrophic Backtracking](https://github.com/c4arl0s/RegularExpressions#9-runaway-regular-expressions-catastrophic-backtracking)
10. [Repeating a Capturing Group vs. Capturing a Repeated Group](https://github.com/c4arl0s/RegularExpressions#10-repeating-a-capturing-group-vs-capturing-a-repeated-group)

# Tools and Languages

1. Specialized Tools and Utilities for Working with Regular Expressions.
2. Using Regular Expressions with Delphi for .NET and Win32.
3. EditPad Pro: Convenient Text Editor with Full Regular Expression Support.
4. What Is grep?.
5. Using Regular Expressions in Java.
6. Java Demo Application using Regular Expressions.
7. Using Regular Expressions with JavaScript and ECMAScript.
8. JavaScript RegExp Example: Regular Expression Tester.
9. MySQL Regular Expressions with The REGEXP Operator.
10. Using Regular Expressions with The Microsoft .NET Framework.
11. C# Demo Application.
12. Oracle Database 10g Regular Expressions.
13. The PCRE Open Source Regex Library.
14. Perl’s Rich Support for Regular Expressions.
15. PHP Provides Three Sets of Regular Expression Functions.
16. POSIX Basic Regular Expressions.
17. PostgreSQL Has Three Regular Expression Flavors.
18. PowerGREP: Taking grep Beyond The Command Line.
19. Python’s re Module.
20. How to Use Regular Expressions in REALbasic.
21. RegexBuddy: Your Perfect Companion for Working with Regular Expressions.
22. Using Regular Expressions with Ruby.
23. Tcl Has Three Regular Expression Flavors.
24. VBScript’s Regular Expression Support.
25. VBScript RegExp Example: Regular Expression Tester.
26. How to Use Regular Expressions in Visual Basic.
27. XML Schema Regular Expressions.
-->

# Reference

1. Basic Syntax Reference.
    * Characters
    * Character Classes or Character Sets [abc]
    * Dot
    * Anchors
    * Word Boundaries
    * Alternation
    * Quantifiers
2. Advanced Syntax Reference.
    * Grouping and Backreferences
    * Modifiers
    * Atomic Grouping and Possessive Quantifiers
    * Lookaround
    * Continuing from The Previous Match
    * Conditionals
    * Comments
    * 
3. Unicode Syntax Reference.
    * Unicode Characters
    * Unicode Properties, Scripts and Blocks
4. Syntax Reference for Specific Regex Flavors.
    * .NET Syntax for Named Capture and Backreferences
    * Python Syntax for Named Capture and Backreferences
    * XML Character Classes
    * POSIX Bracket Expressions
5. Regular Expression Flavor Comparison.
    * Characters
    * Character Classes or Character Sets
    * Dot
    * Anchors
    * Word Boundaries
    * Alternation
    * Quantifiers
    * Grouping and Backreferences
    * Modifiers
    * Atomic Grouping and Possessive Quantifiers
    * Lookaround
    * Continuing from The Previous Match
    * Conditionals
    * Comments
    * Unicode Characters
    * Unicode Properties, Scripts and Blocks
    * .NET Syntax for Named Capture and Backreferences
    * Python Syntax for Named Capture and Backreferences
    * XML Character Classes
    * POSIX Bracket Expressions
6. Replacement Text Reference.
    * Syntax Using Backslashes
    * Syntax Using Dollar Signs
    * Tokens Without a Backslash or Dollar
    * General Replacement Text Behavior
    * Highest-Numbered Capturing Group

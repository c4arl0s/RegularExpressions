# [go back to overview](https://github.com/c4arl0s#main-projects)

# [Regular Expression - Content](https://github.com/c4arl0s/RegularExpressions#go-back-to-overview)

1. [Regular Expression Tutorial - Content](https://github.com/c4arl0s/RegularExpressions#1-regular-expression-tutorial)
    * [What Regular Expressions Are Exactly - Terminology](https://github.com/c4arl0s/RegularExpressions#-what-regular-expressions-are-exactly---terminology)
    * [Different Regular Expression Engines](https://github.com/c4arl0s/RegularExpressions#-different-regular-expression-engines)
    * [Give Regexes a First Try](https://github.com/c4arl0s/RegularExpressions#-give-regexes-a-first-try)
2. [Literal Characters](https://github.com/c4arl0s/RegularExpressions#2-literal-characters)
    * [Special Characters](https://github.com/c4arl0s/RegularExpressions#-special-characters)
    * [Special Characters and Programming Languages](https://github.com/c4arl0s/RegularExpressions#-special-characters-and-programming-languages)
    * [Non-Printable Characters](https://github.com/c4arl0s/RegularExpressions#-non-printable-characters)
3. [First Look at How a Regex Engine Works Internally](https://github.com/c4arl0s/RegularExpressions#3-first-look-at-how-a-regex-engine-works-internally)
    * [The Regex-Directed Engine Always Returns the Leftmost Match](https://github.com/c4arl0s/RegularExpressions#-the-regex-directed-engine-always-returns-the-leftmost-match)
4. [Character Classes or Character Sets](https://github.com/c4arl0s/RegularExpressions#4-character-classes-or-character-sets)
    * [Useful Applications](https://github.com/c4arl0s/RegularExpressions#-useful-applications)
    * [Negated Character Classes](https://github.com/c4arl0s/RegularExpressions#-negated-character-classes)
    * [Metacharacters Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#-metacharacters-inside-character-classes)
    * [Shorthand Character Classes](https://github.com/c4arl0s/RegularExpressions#17-lookahead-and-lookbehind-zero-width-assertions)
    * [Negated Shorthand Character Classes](https://github.com/c4arl0s/RegularExpressions#-negated-shorthand-character-classes)
    * [Repeating Character Classes](https://github.com/c4arl0s/RegularExpressions#-repeating-character-classes)
    * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine)
5. [The Dot Matches (Almost) Any Character](https://github.com/c4arl0s/RegularExpressions#5-the-dot-matches-almost-any-character-)
    * [Use The Dot Sparingly](https://github.com/c4arl0s/RegularExpressions#-use-the-dot-sparingly)
    * [Use Negated Character Sets Instead of the Dot](https://github.com/c4arl0s/RegularExpressions#-use-negated-character-sets-instead-of-the-dot)
6. [Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#6-start-of-string-and-end-of-string-anchors)
    * [Useful Applications](https://github.com/c4arl0s/RegularExpressions#-useful-applications-1)
    * [Using ^ and $ as Start of Line and End of Line Anchors](https://github.com/c4arl0s/RegularExpressions#-using--and--as-start-of-line-and-end-of-line-anchors)
    * [Permanent Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#-permanent-start-of-string-and-end-of-string-anchors)
    * [Zero-Length Matches](https://github.com/c4arl0s/RegularExpressions#-zero-length-matches)
    * [Strings Ending with a Line Break](https://github.com/c4arl0s/RegularExpressions#-strings-ending-with-a-line-break)
    * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-1)
    * [Another Inside Look](https://github.com/c4arl0s/RegularExpressions#-another-inside-look)
    * [Caution for Programmers](https://github.com/c4arl0s/RegularExpressions#-caution-for-programmers)
7. [Word Boundaries](https://github.com/c4arl0s/RegularExpressions#7-word-boundaries)
    * [Negated Word Boundary](https://github.com/c4arl0s/RegularExpressions#-negated-word-boundary)
    * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-2)
    * [Tcl Word Boundaries](https://github.com/c4arl0s/RegularExpressions#-tcl-word-boundaries)
8. [Alternation with The Vertical Bar or Pipe Symbol](https://github.com/c4arl0s/RegularExpressions#8-alternation-with-the-vertical-bar-or-pipe-symbol)
    * [Remember That The Regex Engine Is Eager](https://github.com/c4arl0s/RegularExpressions#-remember-that-the-regex-engine-is-eager)
9. [Optional Items](https://github.com/c4arl0s/RegularExpressions#9-optional-items)
    * [Important Regex Concept: Greediness](https://github.com/c4arl0s/RegularExpressions#-important-regex-concept-greediness)
    * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-3)
10. [Repetition with Star and Plus](https://github.com/c4arl0s/RegularExpressions#10-repetition-with-star-and-plus)
    * [Limiting Repetition](https://github.com/c4arl0s/RegularExpressions#-limiting-repetition)
    * [Watch Out for The Greediness!](https://github.com/c4arl0s/RegularExpressions#-watch-out-for-the-greediness)
    * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-4)
    * [Laziness Instead of Greediness](https://github.com/c4arl0s/RegularExpressions#-laziness-instead-of-greediness)
    * [An Alternative to Laziness](https://github.com/c4arl0s/RegularExpressions#-an-alternative-to-laziness)
    * [Repeating \Q...\E Escape Sequences](https://github.com/c4arl0s/RegularExpressions#-repeating-qe-escape-sequences)
11. [Use Round Brackets for Grouping](https://github.com/c4arl0s/RegularExpressions#11-use-round-brackets-for-grouping)
    * [Round Brackets Create a Backreference](https://github.com/c4arl0s/RegularExpressions#-round-brackets-create-a-backreference)
    * [How to Use Backreferences](https://github.com/c4arl0s/RegularExpressions#-how-to-use-backreferences)
    * [The Entire Regex Match As Backreference Zero](https://github.com/c4arl0s/RegularExpressions#-the-entire-regex-match-as-backreference-zero)
    * [Using Backreferences in The Regular Expression](https://github.com/c4arl0s/RegularExpressions#-using-backreferences-in-the-regular-expression)
    * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-5)
    * [Repetition and Backreferences](https://github.com/c4arl0s/RegularExpressions#-repetition-and-backreferences)
    * [Useful Example: Checking for Doubled Words](https://github.com/c4arl0s/RegularExpressions#-useful-example-checking-for-doubled-words)
    * [Parentheses and Backreferences Cannot Be Used Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#-parentheses-and-backreferences-cannot-be-used-inside-character-classes)
12. [Named Capturing Groups](https://github.com/c4arl0s/RegularExpressions#12-named-capturing-groups)
    * [Named Capture with Python, PCRE and PHP](https://github.com/c4arl0s/RegularExpressions#-named-capture-with-python-pcre-and-php)
    * [Named Capture with .NET’s System.Text.RegularExpressions](https://github.com/c4arl0s/RegularExpressions#-named-capture-with-nets-systemtextregularexpressions)
    * [Names and Numbers for Capturing Groups](https://github.com/c4arl0s/RegularExpressions#-names-and-numbers-for-capturing-groups)
    * [Other Regex Flavors](https://github.com/c4arl0s/RegularExpressions#-other-regex-flavors)
13. [Unicode Regular Expressions](https://github.com/c4arl0s/RegularExpressions#13-unicode-regular-expressions)
    * [Characters, Code Points and Graphemes or How Unicode Makes a Mess of Things](https://github.com/c4arl0s/RegularExpressions#-characters-code-points-and-graphemes-or-how-unicode-makes-a-mess-of-things)
    * [How to Match a Single Unicode Grapheme](https://github.com/c4arl0s/RegularExpressions#-how-to-match-a-single-unicode-grapheme)
    * [Matching a Specific Code Point](https://github.com/c4arl0s/RegularExpressions#-matching-a-specific-code-point)
    * [Unicode Character Properties](https://github.com/c4arl0s/RegularExpressions#-unicode-character-properties)
    * [Unicode Scripts](https://github.com/c4arl0s/RegularExpressions#-unicode-scripts)
    * [Unicode Blocks](https://github.com/c4arl0s/RegularExpressions#-unicode-blocks)
    * [Alternative Unicode Regex Syntax](https://github.com/c4arl0s/RegularExpressions#-alternative-unicode-regex-syntax)
    * [Do You Need To Worry About Different Encodings?](https://github.com/c4arl0s/RegularExpressions#-do-you-need-to-worry-about-different-encodings)
14. [Regex Matching Modes](https://github.com/c4arl0s/RegularExpressions#14-regex-matching-modes)
    * [Specifying Modes Inside The Regular Expression](https://github.com/c4arl0s/RegularExpressions#-specifying-modes-inside-the-regular-expression)
    * [Turning Modes On and Off for Only Part of The Regular Expression](https://github.com/c4arl0s/RegularExpressions#-turning-modes-on-and-off-for-only-part-of-the-regular-expression)
    * [Modifier Spans](https://github.com/c4arl0s/RegularExpressions#-modifier-spans)
15. [Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#15-possessive-quantifiers)
    * [How Possessive Quantifiers Work](https://github.com/c4arl0s/RegularExpressions#-how-possessive-quantifiers-work)
    * [When Possessive Quantifiers Matter](https://github.com/c4arl0s/RegularExpressions#-when-possessive-quantifiers-matter)
    * [Possessive Quantifiers Can Change The Match Result](https://github.com/c4arl0s/RegularExpressions#-possessive-quantifiers-can-change-the-match-result)
    * [Using Atomic Grouping Instead of Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#-using-atomic-grouping-instead-of-possessive-quantifiers)
16. [Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#16-atomic-grouping)
    * [Regex Optimization Using Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#-regex-optimization-using-atomic-grouping)
17. [Lookahead and Lookbehind Zero-Width Assertions](https://github.com/c4arl0s/RegularExpressions#17-lookahead-and-lookbehind-zero-width-assertions)
    * [Positive and Negative Lookahead](https://github.com/c4arl0s/RegularExpressions#-positive-and-negative-lookahead)
    * [Regex Engine Internals](https://github.com/c4arl0s/RegularExpressions#-regex-engine-internals)
    * [Positive and Negative Lookbehind](https://github.com/c4arl0s/RegularExpressions#-positive-and-negative-lookbehind)
    * [More Regex Engine Internals](https://github.com/c4arl0s/RegularExpressions#-more-regex-engine-internals)
    * [Important Notes About Lookbehind](https://github.com/c4arl0s/RegularExpressions#-important-notes-about-lookbehind)
    * [Lookaround Is Atomic](https://github.com/c4arl0s/RegularExpressions#-lookaround-is-atomic)
18. [Testing The Same Part of a String for More Than One Requirement](https://github.com/c4arl0s/RegularExpressions#18-testing-the-same-part-of-a-string-for-more-than-one-requirement)
    * [Lookaround to The Rescue](https://github.com/c4arl0s/RegularExpressions#-lookaround-to-the-rescue)
    * [Optimizing Our Solution](https://github.com/c4arl0s/RegularExpressions#-optimizing-our-solution)
    * [A More Complex Problem](https://github.com/c4arl0s/RegularExpressions#-a-more-complex-problem)
19. [Continuing at The End of The Previous Match](https://github.com/c4arl0s/RegularExpressions#19-continuing-at-the-end-of-the-previous-match)
    * [End of The Previous Match vs. Start of The Match Attempt](https://github.com/c4arl0s/RegularExpressions#-end-of-the-previous-match-vs-start-of-the-match-attempt)
    * [\G Magic with Perl](https://github.com/c4arl0s/RegularExpressions#-g-magic-with-perl)
    * [\G in Other Programming Languages](https://github.com/c4arl0s/RegularExpressions#-g-in-other-programming-languages)
20. [If-Then-Else Conditionals in Regular Expressions](https://github.com/c4arl0s/RegularExpressions#20-if-then-else-conditionals-in-regular-expressions)
    * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine-6)
    * [Regex Flavors](https://github.com/c4arl0s/RegularExpressions#-regex-flavors)
    * [Example: Extract Email Headers](https://github.com/c4arl0s/RegularExpressions#-example-extract-email-headers)
21. [XML Schema Character Classes ](https://github.com/c4arl0s/RegularExpressions#21-xml-schema-character-classes-)
    * [Character Class Subtraction](https://github.com/c4arl0s/RegularExpressions#-character-class-subtraction)
    * [Nested Character Class Subtraction](https://github.com/c4arl0s/RegularExpressions#-nested-character-class-subtraction)
    * [Notational Compatibility with Other Regex Flavors](https://github.com/c4arl0s/RegularExpressions#-notational-compatibility-with-other-regex-flavors)
22. [POSIX Bracket Expressions](https://github.com/c4arl0s/RegularExpressions#22-posix-bracket-expressions)
    * [Character Classes](https://github.com/c4arl0s/RegularExpressions#-character-classes)
    * [Collating Sequences](https://github.com/c4arl0s/RegularExpressions#-collating-sequences)
    * [Character Equivalents](https://github.com/c4arl0s/RegularExpressions#-character-equivalents)
23. [Adding Comments to Regular Expressions](https://github.com/c4arl0s/RegularExpressions#23-adding-comments-to-regular-expressions)
24. [Free-Spacing Regular Expressions](https://github.com/c4arl0s/RegularExpressions#24-free-spacing-regular-expressions)
    * [Comments in Free-Spacing Mode](https://github.com/c4arl0s/RegularExpressions#-comments-in-free-spacing-mode)

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
    * 

# [Regular Expression](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

# 1. [Regular Expression Tutorial](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

In this tutorial, I will teach you all you need to know to be able to craft powerful time-saving regular expressions. I will start with the most basic concepts, so that you can follow this tutorial even if you know nothing at all about regular expressions yet.
But I will not stop there. I will also explain how a regular expression engine works on the inside, and alert you at the consequences. This will help you to understand quickly why a particular regex does not do what you initially expected. It will save you lots of guesswork and head scratching when you need to write more complex regexes.

#  * [What Regular Expressions Are Exactly - Terminology](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
**Basically, a regular expression is a pattern describing a certain amount of text**. Their name comes from the mathematical theory on which they are based. But we will not dig into that. Since most people including myself are lazy to type, you will usually find the name abbreviated to regex or regexp. I prefer regex, because it is easy to pronounce the plural “regexes”. **In this book, regular expressions are printed between guillemots: «regex»**. They clearly separate the pattern from the surrounding text and punctuation.

This first example is actually a perfectly valid regex. It is the most basic pattern, simply matching the literal text „regex”. **A "match" is the piece of text, or sequence of bytes or characters that pattern was found to correspond to by the regex processing software**. Matches are indicated by double quotation marks, with the left one at the base of the line.

**`\b[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,4}\b` is a more complex pattern**. It describes a series of letters, digits, dots, underscores, percentage signs and hyphens, followed by an at sign, followed by another series of letters, digits and hyphens, finally followed by a single dot and between two and four letters. In other words: this pattern describes an email address.

**With the above regular expression pattern, you can search through a text file to find email addresses, or verify if a given string looks like an email address**. In this tutorial, I will use the term “string” to indicate the text that I am applying the regular expression to. I will indicate strings using regular double quotes. The term “string” or “character string” is used by programmers to indicate a sequence of characters. **In practice, you can use regular expressions with whatever data you can access using the application or programming language you are working with**.

#  * [Different Regular Expression Engines](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**A regular expression “engine” is a piece of software that can process regular expressions, trying to match the pattern to the given string**. Usually, the engine is part of a larger application and you do not access the engine directly. Rather, the application will invoke it for you when needed, making sure the right regular expression is applied to the right file or data.

As usual in the software world, different regular expression engines are not fully compatible with each other. It is not possible to describe every kind of engine and regular expression syntax (or “flavor”) in this tutorial. I will focus on the regex flavor used by Perl 5, for the simple reason that this regex flavor is the most popular one, and deservedly so. Many more recent regex engines are very similar, but not identical, to the one of Perl 5. Examples are the open source PCRE engine (used in many tools and languages like PHP), the .NET regular expression library, and the regular expression package included with version 1.4 and later of the Java JDK. I will point out to you whenever differences in regex flavors are important, and which features are specific to the Perl-derivatives mentioned above.

#  * [Give Regexes a First Try](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

You can easily try the following yourself in a text editor that supports regular expressions, such as EditPad Pro. If you do not have such an editor, you can download the free evaluation version of EditPad Pro to try this out. EditPad Pro’s regex engine is fully functional in the demo version. As a quick test, copy and paste the text of this page into EditPad Pro. Then select Search|Show Search Panel from the menu. In the search pane that appears near the bottom, type in «regex» in the box labeled “Search Text”. Mark the “Regular expression” checkbox, and click the Find First button. This is the leftmost button on the search panel. See how EditPad Pro’s regex engine finds the first match. Click the Find Next button, which sits next to the Find First button, to find further matches. When there are no further matches, the Find Next button’s icon will flash briefly.

Now try to search using the regex «reg(ular expressions?|ex(p|es)?)» . This regex will find all names, singular and plural, I have used on this page to say “regex”. If we only had plain text search, we would have needed 5 searches. With regexes, we need just one search. Regexes save you time when using a tool like EditPad Pro. Select Count Matches in the Search menu to see how many times this regular expression can match the file you have open in EditPad Pro.

**If you are a programmer, your software will run faster since even a simple regex engine applying the above regex once will outperform a state of the art plain text search algorithm searching through the data five times**. Regular expressions also reduce development time. With a regex engine, it takes only one line (e.g. in Perl, PHP, Java or .NET) or a couple of lines (e.g. in C using PCRE) of code to, say, check if the user’s input looks like a valid email address.

In this case we are going to use grep tool, from unix command line.

```console
Mon Jul 27 ~/iOS/30Properties_ObjectiveC 
$ cat README.md | grep "view"
In the last chapter, you created a class called **Appliance** that had two properties: **productName** and **voltage**. Let's review how those properties work.
```

It retrieves all lines where the sting "view" appears.


# 2. [Literal Characters](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**The most basic regular expression consists of a single literal character, e.g.: «a**». 

It will match the first occurrence of that character in the string. If the string is “Jack is a boy”, it will match the „a” after the “J”.

Let's start experimenting our course by using this txt file.

```txt
A prominent leaker has cast doubt on rumors that a 2020 iMac update will take place this week, instead suggesting that the product refresh is more likely to take place in August, though without any major redesigns.

Over the weekend, a tweet from a relatively unknown leaker started circulating, putting forward the claim that Apple was preparing to launch a new iMac "this week." The tweet from @Soybeys also went further, suggesting the launch itself could happen earlier in the period, on the Monday.

A second tweet from another leaker, @Jioriku, added to the iMac rumors by writing "The iMac redesign is not coming for this 10th-generation Intel refresh. They are saving it for their own silicon," referencing Apple Silicon.

Late on Sunday, prominent leak reporter Jon Prosser dismissed the claimed launch this week with a single word attached to a screenshot of a headline reporting on the supposed launch: "Nope." In a second tweet, Prosser goes on to suggest it will be later, advising "If you want the new iMac, keep an eye out for August." 

While there is some dispute over timing, there does seem to be a general belief that some form of product launch is on the way. On July 19, fellow prominent leaker @L0vetodream suggested "some products are ready to ship," without saying exactly what, while a mid-June DigiTimes report claimed new iMac and iPad models were destined for release in the second half of 2020.

Despite being negative about the first of the two tweets, Prosser does seem to have backed up the second, ending one of his tweets with "No redesign." This seems to be fairly logical to deduce, as it would be expected for Apple to withhold any major design changes for a major update, such as the introduction of Apple Silicon.

Icons found in an alleged iOS 14 build in June offered the suggestion Apple was redesigning the iMac to include a design that is reminiscent of an iPad Pro, complete with thinner bezels.
```

Let's retrieve only the last line of occurence in the console

```console
Mon Jul 27 ~/iOS/RegularExpressions 
$ cat article.txt | grep "a" | tail -1
Icons found in an alleged iOS 14 build in June offered the suggestion Apple was redesigning the iMac to include a design that is reminiscent of an iPad Pro, complete with thinner bezels.
```

The fact that this “a” is in the middle of the word does not matter to the regex engine. If it matters to you, you will need to tell that to the regex engine by using word boundaries. We will get to that later.

This regex can match the second „a” too. It will only do so when you tell the regex engine to start searching through the string after the first match. In a text editor, you can do so by using its “Find Next” or “Search Forward” function. In a programming language, there is usually a separate function that you can call to continue searching through the string after the previous match.

Similarly, the regex «cat» will match „cat” in “About cats and dogs”. This regular expression consists of a series of three literal characters. This is like saying to the regex engine: find a «c», immediately followed by an «a», immediately followed by a «t».

In this case we are going to use the string "build"

```console
$ cat article.txt | grep "a" | tail -1 | grep "build"
Icons found in an alleged iOS 14 build in June offered the suggestion Apple was redesigning the iMac to include a design that is reminiscent of an iPad Pro, complete with thinner bezels.
```

Note that regex engines are case sensitive by default. «build» does not match “Build”, unless you tell the regex engine to ignore differences in case.

#  * [Special Characters](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Because we want to do more than simply search for literal pieces of text, we need to reserve certain characters for special use. **In the regex flavors discussed in this tutorial, there are 11 characters with special meaningsi**: 

1. the opening square bracket «`[`», 
2. the backslash «\», 
3. the caret «^», 
4. the dollar sign «$», 
5. the period or dot «.», 
6. the vertical bar or pipe symbol «|», 
7. the question mark «?», 
8. the asterisk or star «`*`», 
9. the plus sign «+», 
10. the opening round bracket «(» 
11. and the closing round bracket «)».

**These special characters are often called “metacharacters”**.

If you want to use any of these characters as a literal in a regex, you need to escape them with a backslash. If you want to match „1+1=2”, the correct regex is «1\+1=2». Otherwise, the plus sign will have a special meaning. Note that «1+1=2», with the backslash omitted, is a valid regex. So you will not get an error message. But it will not match “1+1=2”. It would match „111=2” in “123+111=234”, due to the special meaning of the plus character. If you forget to escape a special character where its use is not allowed, such as in «+1», then you will get an error message. In the case of the grep tool, this does not happen, use a tool like vim to see it.

Doing this in vim, it is also successful. 

```console
/1+1 = 2
```

**Most regular expression flavors treat the brace «{» as a literal character, unless it is part of a repetition operator like «{1,3}»**. So you generally do not need to escape it with a backslash, though you can do so if you want. An exception to this rule is the java.util.regex package: it requires all literal braces to be escaped.

**All other characters should not be escaped with a backslash**. That is because the backslash is also a special character. The backslash in combination with a literal character can create a regex token with a special meaning. 

> E.g. «\d» will match a single digit from 0 to 9.

**Escaping a single metacharacter with a backslash works in all regular expression flavors**. Many flavors also support the \Q...\E escape sequence. All the characters between the \Q and the \E are interpreted as literal characters. 

> E.g. «`\Q*\d+*\E`» matches the literal text „`*\d+*`”. 

The \E may be omitted at the end of the regex, so «`\Q*\d+*`» is the same as «`\Q*\d+*\E`». This syntax is supported by the JGsoft engine, Perl and PCRE, both inside and outside character classes. Java supports it outside character classes only, and quantifies it as one token.

#  * [Special Characters and Programming Languages](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**If you are a programmer, you may be surprised that characters like the single quote and double quote are not special characters**. That is correct. When using a regular expression or grep tool like PowerGREP or the search function of a text editor like EditPad Pro, you should not escape or repeat the quote characters like you do in a programming language.

In your source code, you have to keep in mind which characters get special treatment inside strings by your programming language. That is because those characters will be processed by the compiler, before the regex library sees the string. So the regex «1\+1=2» must be written as "1\\+1=2" in C++ code. The C++ compiler will turn the escaped backslash in the source code into a single backslash in the string that is passed on to the regex library. To match „c:\temp”, you need to use the regex «c:\\temp». As a string in C++ source code, this regex becomes "c:\\\\temp". Four backslashes to match a single one indeed.

See the tools and languages section in this book for more information on how to use regular expressions in various programming languages.

#  * [Non-Printable Characters](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**You can use special character sequences to put non-printable characters in your regular expression**. Use «\t» to match a tab character (ASCII 0x09), «\r» for carriage return (0x0D) and «\n» for line feed (0x0A). More exotic non-printables are «\a» (bell, 0x07), «\e» (escape, 0x1B), «\f» (form feed, 0x0C) and «\v» (vertical tab, 0x0B). Remember that Windows text files use “\r\n” to terminate lines, while UNIX text files use “\n”.
You can include any character in your regular expression if you know its hexadecimal ASCII or ANSI code for the character set that you are working with. In the Latin-1 character set, the copyright symbol is character 0xA9. So to search for the copyright symbol, you can use «\xA9». Another way to search for a tab is to use «\x09». Note that the leading zero is required.
Most regex flavors also support the tokens «\cA» through «\cZ» to insert ASCII control characters. The letter after the backslash is always a lowercase c. The second letter is an uppercase letter A through Z, to indicate Control+A through Control+Z. These are equivalent to «\x01» through «\x1A» (26 decimal). E.g. «\cM» matches a carriage return, just like «\r» and «\x0D». In XML Schema regular expressions, «\c» is a shorthand character class that matches any character allowed in an XML name.
If your regular expression engine supports Unicode, use «\uFFFF» rather than «\xFF» to insert a Unicode character. The euro currency sign occupies code point 0x20AC. If you cannot type it on your keyboard, you can insert it into a regular expression with «\u20AC».

# 3. [First Look at How a Regex Engine Works Internally](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Knowing how the regex engineworks will enable you to craft better regexes more easily. It will help you understand quickly why a particular regex does not do what you initially expected. This will save you lots of guesswork and head scratching when you need to write more complex regexes.

There are two kinds of regular expression engines: 

1. text-directed engines,
2. regex-directed engines. 

Jeffrey Friedl calls them DFA and NFA engines, respectively. 

All the regex flavors treated in this tutorial are based on regex-directed engines. This is because certain very useful features, such as lazy quantifiers and backreferences, can only be implemented in regex-directed engines. No surprise that this kind of engine is more popular.

Notable tools that use text-directed engines are awk, egrep, flex, lex, MySQL and Procmail. **For awk and egrep, there are a few versions of these tools that use a regex-directed engine**.

You can easily find out whether the regex flavor you intend to use has a text-directed or regex-directed engine. If backreferences and/or lazy quantifiers are available, you can be certain the engine is regex-directed. You can do the test by applying the regex «regex|regex not» to the string “regex not”. If the resulting match is only „regex”, the engine is regex-directed. If the result is „regex not”, then it is text-directed. The reason behind this is that the regex-directed engine is “eager”.

In this tutorial, after introducing a new regex token, I will explain step by step how the regex engine actually processes that token. This inside look may seem a bit long-winded at certain times. But understanding how the regex engine works will enable you to use its full power and help you avoid common mistakes.

#  * [The Regex-Directed Engine Always Returns the Leftmost Match](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**This is a very important point to understand: a regex-directed engine will always return the leftmost match, even if a “better” match could be found later**. When applying a regex to a string, the engine will start at the first character of the string. It will try all possible permutations of the regular expression at the first character. Only if all possibilities have been tried and found to fail, will the engine continue with the second character in the text. Again, it will try all possible permutations of the regex, in exactly the same order. **The result is that the regex-directed engine will return the leftmost match**.

When applying «cat» to “He captured a catfish for his cat.”, the engine will try to match the first token in the regex «c» to the first character in the match “H”. This fails. There are no other possible permutations of this regex, because it merely consists of a sequence of literal characters. So the regex engine tries to match the «c» with the “e”. This fails too, as does matching the «c» with the space. Arriving at the 4th character in the match, «c» matches „c”. The engine will then try to match the second token «a» to the 5th character, „a”. This succeeds too. But then, «t» fails to match “p”. At that point, the engine knows the regex cannot be matched starting at the 4th character in the match. So it will continue with the 5th: “a”. Again, «c» fails to match here and the engine carries on. At the 15th character in the match, «c» again matches „c”. The engine then proceeds to attempt to match the remainder of the regex at character 15 and finds that «a» matches „a” and «t» matches „t”.
The entire regular expression could be matched starting at character 15. The engine is "eager" to report a match. It will therefore report the first three letters of catfish as a valid match. The engine never proceeds beyond this point to see if there are any “better” matches. The first match is considered good enough.


In this first example of the engine’s internals, our regex engine simply appears to work like a regular text search routine. A text-directed engine would have returned the same result too. However, it is important that you can follow the steps the engine takes in your mind. In following examples, the way the engine works will have a profound impact on the matches it will find. Some of the results may be surprising. But they are always logical and predetermined, once you know how the engine works.

# 4. [Character Classes or Character Sets](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)


**With a "character class", also called “character set”, you can tell the regex engine to match only one out of several characters**. 

Simply place the characters you want to match between square brackets `[]`. If you want to match an `a` or an `e`, use «[ae]». You could use this in «gr[ae]y» to match either „gray” or „grey”. Very useful if you do not know whether the document you are searching through is written in American or British English. A character class matches only a single character. «gr[ae]y» will not match “graay”, “graey” or any such thing. The order of the characters inside a character class does not matter. The results are identical.

> So, [ao], this will find `a` or `o`.

**You can use a hyphen inside a character class to specify a range of characters**. «[0-9]» matches a single digit between 0 and 9. You can use more than one range. «[0-9a-fA-F]» matches a single hexadecimal digit, case insensitively. You can combine ranges and single characters. «[0-9a-fxA-FX]» matches a hexadecimal digit or the letter X. Again, the order of the characters and the ranges does not matter.

> [0-9], it will match a single digit between 0 and 9.

```console
$ cat article.txt | grep "[0-9]"
A prominent leaker has cast doubt on rumors that a 2020 iMac update will take place this week, instead suggesting that the product refresh is more likely to take place in August, though without any major redesigns.
A second tweet from another leaker, @Jioriku, added to the iMac rumors by writing "The iMac redesign is not coming for this 10th-generation Intel refresh. They are saving it for their own silicon," referencing Apple Silicon.
While there is some dispute over timing, there does seem to be a general belief that some form of product launch is on the way. On July 19, fellow prominent leaker @L0vetodream suggested "some products are ready to ship," without saying exactly what, while a mid-June DigiTimes report claimed new iMac and iPad models were destined for release in the second half of 2020.
Icons found in an alleged iOS 14 build in June offered the suggestion Apple was redesigning the iMac to include a design that is reminiscent of an iPad Pro, complete with thinner bezels.
1+1 = 2
2
02/12/03 
021203
02512703
```

Another example:

```console
$ cat article.txt | grep "b[aeio]t" | tail -1
Anchors are a different breed. They do not match any character at all. Instead, they match a position before, after or between characters. They can be used to “anchor” the regex match at a certain position. The caret «^» matches the position before the first character in the string. Applying «^a» to “abc” matches „a”. «^b» will not match “abc” at all, because the «b» cannot be matched right after the start of the string, matched by «^». See below for the inside view of the regex engine.
```

Founded words, in the tail line:

- between 

#  * [Useful Applications](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

1. Find a word, even if it is misspelled, such as «sep[ae]r[ae]te» or «li[cs]en[cs]e». 
2. Find an identifier in a programming language with «`[A-Za-z_][A-Za-z_0-9]*`».
3. Find a C-style hexadecimal number with «0[xX][A-Fa-f0-9]+».

#  * [Negated Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**Typing a caret after the opening square bracket will negate the character class**. The result is that the character class will match any character that is not in the character class. Unlike the dot, negated character classes also match (invisible) line break characters.
It is important to remember that a negated character class still must match a character. «q[^u]» does not mean: “a q not followed by a u”. It means: “a q followed by a character that is not a u”. It will not match the q in the string “Iraq”. It will match the q and the space after the q in “Iraq is a country”. Indeed: the space will be part of the overall match, because it is the “character that is not a u” that is matched by the negated character class in the above regexp. If you want the regex to match the q, and only the q, in both strings, you need to use negative lookahead: «q(?!u)». But we will get to that later.


#  * [Metacharacters Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Note that the only special characters or metacharacters inside a character class are the closing bracket (]), the backslash (\), the caret (^) and the hyphen (-). The usual metacharacters are normal characters inside a character class, and do not need to be escaped by a backslash. To search for a star or plus, use «`[+*]`». Your regex will work fine if you escape the regular metacharacters inside a character class, but doing so significantly reduces readability.

To include a backslash as a character without any special meaning inside a character class, you have to escape it with another backslash. «[\\x]» matches a backslash or an x. The closing bracket (]), the caret (^) and the hyphen (-) can be included by escaping them with a backslash, or by placing them in a position where they do not take on their special meaning. I recommend the latter method, since it improves readability. To include a caret, place it anywhere except right after the opening bracket. «[x^]» matches an x or a caret. You can put the closing bracket right after the opening bracket, or the negating caret. «[]x]» matches a closing bracket or an x. «[^]x]» matches any character that is not a closing bracket or an x. The hyphen can be included right after the opening bracket, or right before the closing bracket, or right after the negating caret. Both «[-x]» and «[x-]» match an x or a hyphen.

```console
$ cat article.txt | grep "[+*-]" | tail -4
1+1 = 2
```

You can use all non-printable characters in character classes just like you can use them outside of character classes. E.g. «[$\u20AC]» matches a dollar or euro sign, assuming your regex flavor supports Unicode.

The JGsoft engine, Perl and PCRE also support the \Q...\E sequence inside character classes to escape a string of characters. E.g. «[\Q[-]\E]» matches „[”, „-” or „]”.

POSIX regular expressions treat the backslash as a literal character inside character classes. This means you can’t use backslashes to escape the closing bracket (]), the caret (^) and the hyphen (-). To use these characters, position them as explained above in this section. This also means that special tokens like shorthands are not available in POSIX regular expressions. See the tutorial topic on POSIX bracket expressions for more information.

#     * [Shorthand Characters Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Negated Shorthand Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Repeating Character classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)      
#     * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine)
# 5. [The Dot Matches (Almost) Any Character](https://github.com/c4arl0s/RegularExpressions#5-the-dot-matches-almost-any-character-)
#     * [Use The Dot Sparingly]()
#     * [Use Negated Character Sets Instead of the Dot](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 6. [Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#6-start-of-string-and-end-of-string-anchors)
#     * [Useful Applications](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Using ^ and $ as Start of Line and End of Line Anchors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Permanent Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Zero-Length Matches](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Strings Ending with a Line Break](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Another Inside Look](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Caution for Programmers](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 7. [Word Boundaries](https://github.com/c4arl0s/RegularExpressions#7-word-boundaries)
#     * [Negated Word Boundary](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Tcl Word Boundaries](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 8. [Alternation with The Vertical Bar or Pipe Symbol](https://github.com/c4arl0s/RegularExpressions#8-alternation-with-the-vertical-bar-or-pipe-symbol)
#     * [Remember That The Regex Engine Is Eager](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 9. [Optional Items](https://github.com/c4arl0s/RegularExpressions#9-optional-items)
#     * [Important Regex Concept: Greediness](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 10. [Repetition with Star and Plus](https://github.com/c4arl0s/RegularExpressions#10-repetition-with-star-and-plus)
#     * [Limiting Repetition](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Watch Out for The Greediness!](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Laziness Instead of Greediness](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [An Alternative to Laziness](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Repeating \Q...\E Escape Sequences](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 11. [Use Round Brackets for Grouping](https://github.com/c4arl0s/RegularExpressions#11-use-round-brackets-for-grouping)
#     * [Round Brackets Create a Backreference](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [How to Use Backreferences](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [The Entire Regex Match As Backreference Zero](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Using Backreferences in The Regular Expression](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Repetition and Backreferences](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Useful Example: Checking for Doubled Words](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Parentheses and Backreferences Cannot Be Used Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 12. [Named Capturing Groups](https://github.com/c4arl0s/RegularExpressions#12-named-capturing-groups)
#     * [Named Capture with Python, PCRE and PHP](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Named Capture with .NET’s System.Text.RegularExpressions](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Names and Numbers for Capturing Groups](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Other Regex Flavors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 13. [Unicode Regular Expressions](https://github.com/c4arl0s/RegularExpressions#13-unicode-regular-expressions)
#     * [Characters, Code Points and Graphemes or How Unicode Makes a Mess of Things](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [How to Match a Single Unicode Grapheme](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Matching a Specific Code Point](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Unicode Character Properties](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Unicode Scripts](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Unicode Blocks](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Alternative Unicode Regex Syntax](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Do You Need To Worry About Different Encodings?](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 14. [Regex Matching Modes](https://github.com/c4arl0s/RegularExpressions#14-regex-matching-modes)
#     * [Specifying Modes Inside The Regular Expression](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Turning Modes On and Off for Only Part of The Regular Expression](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Modifier Spans](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 15. [Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#15-possessive-quantifiers)
#     * [How Possessive Quantifiers Work](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [When Possessive Quantifiers Matter](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Possessive Quantifiers Can Change The Match Result](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Using Atomic Grouping Instead of Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 16. [Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#16-atomic-grouping)
#     * [Regex Optimization Using Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 17. [Lookahead and Lookbehind Zero-Width Assertions](https://github.com/c4arl0s/RegularExpressions#17-lookahead-and-lookbehind-zero-width-assertions)
#     * [Positive and Negative Lookahead](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Regex Engine Internals](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Positive and Negative Lookbehind](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [More Regex Engine Internals](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Important Notes About Lookbehind](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Lookaround Is Atomic](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 18. [Testing The Same Part of a String for More Than One Requirement](https://github.com/c4arl0s/RegularExpressions#18-testing-the-same-part-of-a-string-for-more-than-one-requirement)
#     * [Lookaround to The Rescue](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Optimizing Our Solution](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [A More Complex Problem](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 19. [Continuing at The End of The Previous Match](https://github.com/c4arl0s/RegularExpressions#19-continuing-at-the-end-of-the-previous-match)
#     * [End of The Previous Match vs. Start of The Match Attempt](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [\G Magic with Perl](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [\G in Other Programming Languages](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 20. [If-Then-Else Conditionals in Regular Expressions](https://github.com/c4arl0s/RegularExpressions#20-if-then-else-conditionals-in-regular-expressions)
#     * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Regex Flavors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Example: Extract Email Headers](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 21. [XML Schema Character Classes ](https://github.com/c4arl0s/RegularExpressions#21-xml-schema-character-classes-)
#     * [Character Class Subtraction](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Nested Character Class Subtraction](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Notational Compatibility with Other Regex Flavors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 22. [POSIX Bracket Expressions](https://github.com/c4arl0s/RegularExpressions#22-posix-bracket-expressions)
#     * [Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Collating Sequences](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
#     * [Character Equivalents](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 23. [Adding Comments to Regular Expressions](https://github.com/c4arl0s/RegularExpressions#23-adding-comments-to-regular-expressions)
# 24. [Free-Spacing Regular Expressions](https://github.com/c4arl0s/RegularExpressions#24-free-spacing-regular-expressions)
#     * [Comments in Free-Spacing Mode](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

# Examples
 
# 1. [Sample Regular Expression](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 2. [Matching Floating Point Numbers with a Regular Expression](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 3. [How to Find or Validate an Email Address](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 4. [Matching a Valid Date](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 5. [Matching Whole Lines of Text](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 6. [Deleting Duplicate Lines From a File ](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 8. [Find Two Words Near Each Other](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 9. [Runaway Regular Expressions: Catastrophic Backtracking](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)
# 10. [Repeating a Capturing Group vs. Capturing a Repeated Group](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)


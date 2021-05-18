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
    * [Useful Applications](https://github.com/c4arl0s/RegularExpressions#-useful-applications-for-6)
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
**Basically, a regular expression is a pattern describing a certain amount of text**. Their name comes from the mathematical theory on which they are based. But we will not dig into that. Since most people including myself are lazy to type, you will usually find the name abbreviated to regex or regexp. I prefer regex, because it is easy to pronounce the plural “regexes”. **In this book, regular expressions are printed between guillemots: `regex`**. They clearly separate the pattern from the surrounding text and punctuation.

This first example is actually a perfectly valid regex. It is the most basic pattern, simply matching the literal text „regex”. **A "match" is the piece of text, or sequence of bytes or characters that pattern was found to correspond to by the regex processing software**. Matches are indicated by double quotation marks, with the left one at the base of the line.

**`\b[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,4}\b` is a more complex pattern**. It describes a series of letters, digits, dots, underscores, percentage signs and hyphens, followed by an at sign, followed by another series of letters, digits and hyphens, finally followed by a single dot and between two and four letters. In other words: this pattern describes an email address.

**With the above regular expression pattern, you can search through a text file to find email addresses, or verify if a given string looks like an email address**. In this tutorial, I will use the term “string” to indicate the text that I am applying the regular expression to. I will indicate strings using regular double quotes. The term “string” or “character string” is used by programmers to indicate a sequence of characters. **In practice, you can use regular expressions with whatever data you can access using the application or programming language you are working with**.

#  * [Different Regular Expression Engines](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**A regular expression “engine” is a piece of software that can process regular expressions, trying to match the pattern to the given string**. Usually, the engine is part of a larger application and you do not access the engine directly. Rather, the application will invoke it for you when needed, making sure the right regular expression is applied to the right file or data.

As usual in the software world, different regular expression engines are not fully compatible with each other. It is not possible to describe every kind of engine and regular expression syntax (or “flavor”) in this tutorial. I will focus on the regex flavor used by Perl 5, for the simple reason that this regex flavor is the most popular one, and deservedly so. Many more recent regex engines are very similar, but not identical, to the one of Perl 5. Examples are the open source PCRE engine (used in many tools and languages like PHP), the .NET regular expression library, and the regular expression package included with version 1.4 and later of the Java JDK. I will point out to you whenever differences in regex flavors are important, and which features are specific to the Perl-derivatives mentioned above.

#  * [Give Regexes a First Try](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

You can easily try the following yourself in a text editor that supports regular expressions, such as EditPad Pro. If you do not have such an editor, you can download the free evaluation version of EditPad Pro to try this out. EditPad Pro’s regex engine is fully functional in the demo version. As a quick test, copy and paste the text of this page into EditPad Pro. Then select Search|Show Search Panel from the menu. In the search pane that appears near the bottom, type in `regex` in the box labeled “Search Text”. Mark the “Regular expression” checkbox, and click the Find First button. This is the leftmost button on the search panel. See how EditPad Pro’s regex engine finds the first match. Click the Find Next button, which sits next to the Find First button, to find further matches. When there are no further matches, the Find Next button’s icon will flash briefly.

Now try to search using the regex `reg(ular expressions?|ex(p|es)?)` . This regex will find all names, singular and plural, I have used on this page to say “regex”. If we only had plain text search, we would have needed 5 searches. With regexes, we need just one search. Regexes save you time when using a tool like EditPad Pro. Select Count Matches in the Search menu to see how many times this regular expression can match the file you have open in EditPad Pro.

**If you are a programmer, your software will run faster since even a simple regex engine applying the above regex once will outperform a state of the art plain text search algorithm searching through the data five times**. Regular expressions also reduce development time. With a regex engine, it takes only one line (e.g. in Perl, PHP, Java or .NET) or a couple of lines (e.g. in C using PCRE) of code to, say, check if the user’s input looks like a valid email address.

In this case we are going to use grep tool, from unix command line.

```console
Mon Jul 27 ~/iOS/30Properties_ObjectiveC 
$ cat README.md | grep "view"
In the last chapter, you created a class called **Appliance** that had two properties: **productName** and **voltage**. Let's review how those properties work.
```

It retrieves all lines where the sting "view" appears.


# 2. [Literal Characters](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**The most basic regular expression consists of a single literal character, e.g.: `a`**. 

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

Similarly, the regex `cat` will match „cat” in “About cats and dogs”. This regular expression consists of a series of three literal characters. This is like saying to the regex engine: find a c, immediately followed by an a, immediately followed by a t.

In this case we are going to use the string "build"

```console
$ cat article.txt | grep "a" | tail -1 | grep "build"
Icons found in an alleged iOS 14 build in June offered the suggestion Apple was redesigning the iMac to include a design that is reminiscent of an iPad Pro, complete with thinner bezels.
```

Note that regex engines are case sensitive by default. `build` does not match “Build”, unless you tell the regex engine to ignore differences in case.

#  * [Special Characters](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Because we want to do more than simply search for literal pieces of text, we need to reserve certain characters for special use. **In the regex flavors discussed in this tutorial, there are 11 characters with special meaningsi**: 

1. the opening square bracket `[`, 
2. the backslash `\`, 
3. the caret `^`, 
4. the dollar sign `$`, 
5. the period or dot `.`, 
6. the vertical bar or pipe symbol `|`, 
7. the question mark `?`, 
8. the asterisk or star `*`, 
9. the plus sign `+`, 
10. the opening round bracket `(` 
11. and the closing round bracket `)`.

**These special characters are often called “metacharacters”**.

If you want to use any of these characters as a literal in a regex, you need to escape them with a backslash. If you want to match „1+1=2”, the correct regex is `1\+1=2`. Otherwise, the plus sign will have a special meaning. Note that 1+1=2, with the backslash omitted, is a valid regex. So you will not get an error message. But it will not match “1+1=2”. It would match „111=2” in “123+111=234”, due to the special meaning of the plus character. If you forget to escape a special character where its use is not allowed, such as in +1, then you will get an error message. In the case of the grep tool, this does not happen, use a tool like vim to see it.

Doing this in vim, it is also successful. 

```console
/1+1 = 2
```

**Most regular expression flavors treat the brace `{` as a literal character, unless it is part of a repetition operator like {1,3}**. So you generally do not need to escape it with a backslash, though you can do so if you want. An exception to this rule is the java.util.regex package: it requires all literal braces to be escaped.

**All other characters should not be escaped with a backslash**. That is because the backslash is also a special character. The backslash in combination with a literal character can create a regex token with a special meaning. 

> E.g. `\d` will match a single digit from 0 to 9.

**Escaping a single metacharacter with a backslash works in all regular expression flavors**. Many flavors also support the \Q...\E escape sequence. All the characters between the \Q and the \E are interpreted as literal characters. 

> E.g. ``\Q*\d+*\E`` matches the literal text „`*\d+*`”. 

The \E may be omitted at the end of the regex, so ``\Q*\d+*`` is the same as `\Q*\d+*\E`. This syntax is supported by the JGsoft engine, Perl and PCRE, both inside and outside character classes. Java supports it outside character classes only, and quantifies it as one token.

#  * [Special Characters and Programming Languages](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**If you are a programmer, you may be surprised that characters like the single quote and double quote are not special characters**. That is correct. When using a regular expression or grep tool like PowerGREP or the search function of a text editor like EditPad Pro, you should not escape or repeat the quote characters like you do in a programming language.

In your source code, you have to keep in mind which characters get special treatment inside strings by your programming language. That is because those characters will be processed by the compiler, before the regex library sees the string. So the regex `1\+1=2` must be written as "1\\+1=2" in C++ code. The C++ compiler will turn the escaped backslash in the source code into a single backslash in the string that is passed on to the regex library. To match „c:\temp”, you need to use the regex c:\\temp. As a string in C++ source code, this regex becomes "c:\\\\temp". Four backslashes to match a single one indeed.

See the tools and languages section in this book for more information on how to use regular expressions in various programming languages.

#  * [Non-Printable Characters](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**You can use special character sequences to put non-printable characters in your regular expression**. 

1. Use `\t` to match a tab character (ASCII 0x09), 
2. \r for carriage return (0x0D) 
3. and \n for line feed (0x0A). 

More exotic non-printables are: 

1. \a (bell, 0x07), 
2. \e (escape, 0x1B), 
3. \f (form feed, 0x0C) 
4. and \v (vertical tab, 0x0B). 

> Remember that Windows text files use “\r\n” to terminate lines, while UNIX text files use “\n”.

You can include any character in your regular expression if you know its hexadecimal ASCII or ANSI code for the character set that you are working with. In the Latin-1 character set, the copyright symbol is character 0xA9. So to search for the copyright symbol, you can use `\xA9`. Another way to search for a tab is to use \x09. Note that the leading zero is required.

Most regex flavors also support the tokens `\cA` through \cZ to insert ASCII control characters. The letter after the backslash is always a lowercase c. The second letter is an uppercase letter A through Z, to indicate Control+A through Control+Z. These are equivalent to \x01 through \x1A (26 decimal). E.g. \cM matches a carriage return, just like \r and \x0D. In XML Schema regular expressions, \c is a shorthand character class that matches any character allowed in an XML name.

If your regular expression engine supports Unicode, use `\uFFFF` rather than \xFF to insert a Unicode character. The euro currency sign occupies code point 0x20AC. If you cannot type it on your keyboard, you can insert it into a regular expression with \u20AC.

# 3. [First Look at How a Regex Engine Works Internally](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Knowing how the regex engineworks will enable you to craft better regexes more easily. It will help you understand quickly why a particular regex does not do what you initially expected. This will save you lots of guesswork and head scratching when you need to write more complex regexes.

There are two kinds of regular expression engines: 

1. text-directed engines,
2. regex-directed engines. 

Jeffrey Friedl calls them DFA and NFA engines, respectively. 

All the regex flavors treated in this tutorial are based on regex-directed engines. This is because certain very useful features, such as lazy quantifiers and backreferences, can only be implemented in regex-directed engines. No surprise that this kind of engine is more popular.

Notable tools that use text-directed engines are awk, egrep, flex, lex, MySQL and Procmail. **For awk and egrep, there are a few versions of these tools that use a regex-directed engine**.

You can easily find out whether the regex flavor you intend to use has a text-directed or regex-directed engine. If backreferences and/or lazy quantifiers are available, you can be certain the engine is regex-directed. You can do the test by applying the regex `regex|regex not` to the string “regex not”. If the resulting match is only „regex”, the engine is regex-directed. If the result is „regex not”, then it is text-directed. The reason behind this is that the regex-directed engine is “eager”.

In this tutorial, after introducing a new regex token, I will explain step by step how the regex engine actually processes that token. This inside look may seem a bit long-winded at certain times. But understanding how the regex engine works will enable you to use its full power and help you avoid common mistakes.

#  * [The Regex-Directed Engine Always Returns the Leftmost Match](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**This is a very important point to understand: a regex-directed engine will always return the leftmost match, even if a “better” match could be found later**. When applying a regex to a string, the engine will start at the first character of the string. It will try all possible permutations of the regular expression at the first character. Only if all possibilities have been tried and found to fail, will the engine continue with the second character in the text. Again, it will try all possible permutations of the regex, in exactly the same order. **The result is that the regex-directed engine will return the leftmost match**.

When applying `cat` to “He captured a catfish for his cat.”, the engine will try to match the first token in the regex c to the first character in the match “H”. This fails. There are no other possible permutations of this regex, because it merely consists of a sequence of literal characters. So the regex engine tries to match the c with the “e”. This fails too, as does matching the c with the space. Arriving at the 4th character in the match, c matches „c”. The engine will then try to match the second token a to the 5th character, „a”. This succeeds too. But then, t fails to match “p”. At that point, the engine knows the regex cannot be matched starting at the 4th character in the match. So it will continue with the 5th: “a”. Again, c fails to match here and the engine carries on. At the 15th character in the match, c again matches „c”. The engine then proceeds to attempt to match the remainder of the regex at character 15 and finds that a matches „a” and t matches „t”.
The entire regular expression could be matched starting at character 15. The engine is "eager" to report a match. It will therefore report the first three letters of catfish as a valid match. The engine never proceeds beyond this point to see if there are any “better” matches. The first match is considered good enough.


In this first example of the engine’s internals, our regex engine simply appears to work like a regular text search routine. A text-directed engine would have returned the same result too. However, it is important that you can follow the steps the engine takes in your mind. In following examples, the way the engine works will have a profound impact on the matches it will find. Some of the results may be surprising. But they are always logical and predetermined, once you know how the engine works.

# 4. [Character Classes or Character Sets](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)


**With a "character class", also called “character set”, you can tell the regex engine to match only one out of several characters**. 

Simply place the characters you want to match between square brackets `[]`. If you want to match an `a` or an `e`, use `[ae]`. You could use this in gr[ae]y to match either „gray” or „grey”. Very useful if you do not know whether the document you are searching through is written in American or British English. A character class matches only a single character. gr[ae]y will not match “graay”, “graey” or any such thing. The order of the characters inside a character class does not matter. The results are identical.

> So, [ao], this will find `a` or `o`.

**You can use a hyphen inside a character class to specify a range of characters**. `[0-9]` matches a single digit between 0 and 9. You can use more than one range. [0-9a-fA-F] matches a single hexadecimal digit, case insensitively. You can combine ranges and single characters. [0-9a-fxA-FX] matches a hexadecimal digit or the letter X. Again, the order of the characters and the ranges does not matter.

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
Anchors are a different breed. They do not match any character at all. Instead, they match a position before, after or between characters. They can be used to “anchor” the regex match at a certain position. The caret `^` matches the position before the first character in the string. Applying ^a to “abc” matches „a”. ^b will not match “abc” at all, because the b cannot be matched right after the start of the string, matched by ^. See below for the inside view of the regex engine.
```

Founded words, in the tail line:

- between 

#  * [Useful Applications](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

1. Find a word, even if it is misspelled, such as `sep[ae]r[ae]te` or li[cs]en[cs]e. 
2. Find an identifier in a programming language with ``[A-Za-z_][A-Za-z_0-9]*``.
3. Find a C-style hexadecimal number with `0[xX][A-Fa-f0-9]+`.

#  * [Negated Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

**Typing a caret after the opening square bracket will negate the character class**. The result is that the character class will match any character that is not in the character class. Unlike the dot, negated character classes also match (invisible) line break characters.
It is important to remember that a negated character class still must match a character. `q[^u]` does not mean: “a q not followed by a u”. It means: “a q followed by a character that is not a u”. It will not match the q in the string “Iraq”. It will match the q and the space after the q in “Iraq is a country”. Indeed: the space will be part of the overall match, because it is the “character that is not a u” that is matched by the negated character class in the above regexp. If you want the regex to match the q, and only the q, in both strings, you need to use negative lookahead: q(?!u). But we will get to that later.


#  * [Metacharacters Inside Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Note that the only special characters or metacharacters inside a character class are the closing bracket (]), the backslash (\), the caret (^) and the hyphen (-). The usual metacharacters are normal characters inside a character class, and do not need to be escaped by a backslash. To search for a star or plus, use ``[+*]``. Your regex will work fine if you escape the regular metacharacters inside a character class, but doing so significantly reduces readability.

To include a backslash as a character without any special meaning inside a character class, you have to escape it with another backslash. `[\\x]` matches a backslash or an x. The closing bracket (]), the caret (^) and the hyphen (-) can be included by escaping them with a backslash, or by placing them in a position where they do not take on their special meaning. I recommend the latter method, since it improves readability. To include a caret, place it anywhere except right after the opening bracket. [x^] matches an x or a caret. You can put the closing bracket right after the opening bracket, or the negating caret. []x] matches a closing bracket or an x. [^]x] matches any character that is not a closing bracket or an x. The hyphen can be included right after the opening bracket, or right before the closing bracket, or right after the negating caret. Both [-x] and [x-] match an x or a hyphen.

```console
$ cat article.txt | grep "[+*-]" | tail -4
1+1 = 2
```

You can use all non-printable characters in character classes just like you can use them outside of character classes. E.g. `[$\u20AC]` matches a dollar or euro sign, assuming your regex flavor supports Unicode.

The JGsoft engine, Perl and PCRE also support the \Q...\E sequence inside character classes to escape a string of characters. E.g. `[\Q[-]\E]` matches „[”, „-” or „]”.

POSIX regular expressions treat the backslash as a literal character inside character classes. This means you can’t use backslashes to escape the closing bracket (]), the caret (^) and the hyphen (-). To use these characters, position them as explained above in this section. This also means that special tokens like shorthands are not available in POSIX regular expressions. See the tutorial topic on POSIX bracket expressions for more information.

#     * [Shorthand Characters Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Since certain character classes are used often, a series of shorthand character classes are available. `\d` is short for [0- 9].

`\w` stands for “word character”. Exactly which characters it matches differs between regex flavors. In all flavors, it will include [A-Za- z]. In most, the underscore and digits are also included. In some flavors, word characters from other languages may also match. The best way to find out is to do a couple of tests with the regex flavor you are using. In the screen shot, you can see the characters matched by \w in RegexBuddy using various scripts.

To test an example, I create sentence.txt, the output console instruction is:

![Screen Shot 2021-04-01 at 8 33 05](https://user-images.githubusercontent.com/24994818/113309933-e77e6e00-92c4-11eb-8358-be7819a0e7da.png)

`\s` stands for “whitespace character”. Again, which characters this actually includes, depends on the regex flavor. In all flavors discussed in this tutorial, it includes [ \t]. That is: \s will match a space or a tab. In most flavors, it also includes a carriage return or a line feed as in [ \t\r\n]. Some flavors include additional, rarely used non-printable characters such as vertical tab and form feed.

Using sentence.txt:

![Screen Shot 2021-04-01 at 8 36 52](https://user-images.githubusercontent.com/24994818/113310396-6d021e00-92c5-11eb-9f3a-b840364f4545.png)

Shorthand character classes can be used both inside and outside the square brackets. `\s\d` matches a whitespace character followed by a digit. [\s\d] matches a single character that is either whitespace or a digit. 

![Screen Shot 2021-04-01 at 8 40 08](https://user-images.githubusercontent.com/24994818/113310831-e1d55800-92c5-11eb-8ebd-2bc29028ee8c.png)

When applied to “1 + 2 = 3”, the former regex will match „ 2” (space two), while the latter matches „1” (one). `[\da-fA-F]` matches a hexadecimal digit, and is equivalent to [0-9a-fA-F].

#     * [Negated Shorthand Character Classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

The above three shorthands also have negated versions. `\D` is the same as `[^\d]`, `\W` is short for `[^\w]` and `\S` is the equivalent of `[^\s]`.

Be careful when using the negated shorthands inside square brackets. `[\D\S]` is not the same as [^\d\s]. The latter will match any character that is not a digit or whitespace. So it will match „x”, but not “8”. The former, however, will match any character that is either not a digit, or is not whitespace. Because a digit is not whitespace, and whitespace is not a digit, `[\D\S]` will match any character, digit, whitespace or otherwise.

Take a look what is the console output for the file attached to this priject

![Screen Shot 2021-04-07 at 0 27 05](https://user-images.githubusercontent.com/24994818/113814966-15860700-9738-11eb-8f4b-6ddcae306e46.png)

The output points only symbols like , and ?, and . 

#     * [Repeating Character classes](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)      

If you repeat a character class by using the `?`, `*` or `+` operators, you will repeat the entire character class, and not just the character that it matched. The regex `[0-9]+` can match „837” as well as „222”.
If you want to repeat the matched character, rather than the class, you will need to use backreferences. `([0- 9])\1+` will match „222” but not “837”. When applied to the string “833337”, it will match „3333” in the middle of this string. If you do not want that, you need to use lookahead and lookbehind.
But I digress. I did not yet explain how character classes work inside the regex engine. Let us take a look at that first.

If you are doing it in VIM: you have to use `[0-9]\+` to repeat a character. Take a look below:

![Screen Shot 2021-04-13 at 19 30 54](https://user-images.githubusercontent.com/24994818/114637407-e1a66680-9c8e-11eb-8a4d-25c58409a20e.png)

#     * [Looking Inside The Regex Engine](https://github.com/c4arl0s/RegularExpressions#-looking-inside-the-regex-engine)

As I already said: the order of the characters inside a character class does not matter. `gr[ae]y` will match „grey” in “Is his hair grey or gray?”, because that is the leftmost match. We already saw how the engine applies a regex consisting only of literal characters. Below, I will explain how it applies a regex that has more than one permutation. That is: `gr[ae]y` can match both „gray” and „grey”.

Nothing noteworthy happens for the first twelve characters in the string. The engine will fail to match `g` at every step, and continue with the next character in the string. When the engine arrives at the 13th character, „g” is matched. The engine will then try to match the remainder of the regex with the text. The next token in the regex is the literal r, which matches the next character in the text. So the third token, `[ae]` is attempted at the next character in the text (“e”). The character class gives the engine two options: match a or match e. It will first attempt to match a, and fail.

But because we are using a regex-directed engine, it must continue trying to match all the other permutations of the regex pattern before deciding that the regex cannot be matched with the text starting at character 13.

So it will continue with the other option, and find that `e` matches „e”. The last regex token is y, which can be matched with the following character as well. The engine has found a complete match with the text starting at character 13. It will return „grey” as the match result, and look no further. Again, the leftmost match was returned, even though we put the a first in the character class, and „gray” could have been matched in the string. But the engine simply did not get that far, because another equally valid match was found to the left of it.

# 5. [The Dot Matches (Almost) Any Character](https://github.com/c4arl0s/RegularExpressions#5-the-dot-matches-almost-any-character-)

In regular expressions, the dot or period is one of the most commonly used metacharacters. Unfortunately, it is also the most commonly misused metacharacter.

The dot matches a single character, without caring what that character is. The only exception are newlinecharacters. In all regex flavors discussed in this tutorial, the dot will not match a newline character by default. So by default, the dot is short for the negated character class `[^\n]` (UNIX regex flavors) or `[^\r\n]` (Windows regex flavors).

This exception exists mostly because of historic reasons. The first tools that used regular expressions were line-based. They would read a file line by line, and apply the regular expression separately to each line. The effect is that with these tools, the string could never contain newlines, so the dot could never match them.

Modern tools and languages can apply regular expressions to very large strings or even entire files. All regex flavors discussed here have an option to make the dot match all characters, including newlines. In RegexBuddy, EditPad Pro or PowerGREP, you simply tick the checkbox labeled “dot matches newline”.

In Perl, the mode where the dot also matches newlines is called "single-line mode". This is a bit unfortunate, because it is easy to mix up this term with “multi-line mode”. Multi-line mode only affects anchors, and single-line mode only affects the dot. You can activate single-line mode by adding an s after the regex code, like this: m/^regex$/s;.

Other languages and regex libraries have adopted Perl’s terminology. When using the regex classes of the .NET framework, you activate this mode by specifying RegexOptions.Singleline, such as in Regex.Match("string", "regex", RegexOptions.Singleline).

In all programming languages and regex libraries I know, activating single-line mode has no effect other than making the dot match newlines. So if you expose this option to your users, please give it a clearer label like was done in RegexBuddy, EditPad Pro and PowerGREP.

JavaScript and VBScript do not have an option to make the dot match line break characters. In those languages, you can use a character class such as `[\s\S]` to match any character. This character matches a character that is either a whitespace character (including line break characters), or a character that is not a whitespace character. Since all characters are either whitespace or non-whitespace, this character class matches any character.

#     * [Use The Dot Sparingly](https://github.com/c4arl0s/RegularExpressions#5-the-dot-matches-almost-any-character-)

The dot is a very powerful regex metacharacter. It allows you to be lazy. Put in a dot, and everything will match just fine when you test the regex on valid data. The problem is that the regex will also match in cases where it should not match. If you are new to regular expressions, some of these cases may not be so obvious at first.

I will illustrate this with a simple example. Let’s say we want to match a date in mm/dd/yy format, but we want to leave the user the choice of date separators. The quick solution is `\d\d.\d\d.\d\d`.  Seems fine at first. It will match a date like „02/12/03” just fine. Trouble is: „02512703” is also considered a valid date by this regular expression. In this match, the first dot matched „5”, and the second matched „7”. Obviously not what we intended.

`\d\d[- /.]\d\d[- /.]\d\d` is a better solution. This regex allows a dash, space, dot and forward slash as date separators. **Remember that the dot is not a metacharacter inside a character class, so we do not need to escape it with a backslash**.

This regex is still far from perfect. It matches „99/99/99” as a valid date. `[0-1]\d[- /.][0-3]\d[- /.]\d\d` is a step ahead, though it will still match „19/39/99”. 


```console
[0-1]\d[- /.][0-3]\d[- /.]\d\d
```

If you want to match 2021 year, add two more digits.

```console
[0-1]\d[- /.][0-3]\d[- /.]\d\d\d\d
```

How perfect you want your regex to be depends on what you want to do with it. If you are validating user input, it has to be perfect. If you are parsing data files from a known source that generates its files in the same way every time, our last attempt is probably more than sufficient to parse the data without errors. You can find a better regex to match dates in the example section.

#     * [Use Negated Character Sets Instead of the Dot](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

I will explain this in depth when I present you the repeat operators star and plus, but the warning is important enough to mention it here as well. I will illustrate with an example.

Suppose you want to match a double-quoted string. Sounds easy. We can have any number of any character between the double quotes, so `".*"` seems to do the trick just fine. The dot matches any character, and the star allows the dot to be repeated any number of times, including zero. If you test this regex on “Put a "string" between double quotes”, it will match „"string"” just fine. Now go ahead and test it on “Houston, we have a problem with "string one" and "string two". Please respond.”

Ouch. The regex matches „"string one" and "string two"”. Definitely not what we intended. The reason for this is that the star is greedy.

In the date-matching example, we improved our regex by replacing the dot with a character class. Here, we will do the same. Our original definition of a double-quoted string was faulty. We do not want any number of any character between the quotes. We want any number of characters that are not double quotes or newlines between the quotes. So the proper regex is `"[^"\r\n]*"`.

This is important to find patterns like „method(:)” or „method(parameter:)”:

```txt
method(_:) and this is another method2(parameter:).
```

# 6. [Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#6-start-of-string-and-end-of-string-anchors)

Thus far, I have explained literal characters and character classes. In both cases, putting one in a regex will cause the regex engine to try to match a single character.

Anchors are a different breed. They do not match any character at all. Instead, they match a position before, after or between characters. They can be used to “anchor” the regex match at a certain position. The caret `^` matches the position before the first character in the string. Applying `^a` to “abc” matches „a”. `^b` will not match “abc” at all, because the `b` cannot be matched right after the start of the string, matched by `^`. See below for the inside view of the regex engine.

Similarly, `$` matches right after the last character in the string. `c$` matches „c” in “abc”, while `a$` does not match at all.

#     * [Useful Applications for 6](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

When using regular expressions in a programming language to validate user input, using anchors is very important. If you use the code if ($input =~ m/\d+/) in a Perl script to see if the user entered an integer number, it will accept the input even if the user entered “qsdf4ghjk”, because `\d+` matches the 4. The correct regex to use is `^\d+$`. Because “start of string” must be matched before the match of `\d+`, and “end of string” must be matched right after it, the entire string must consist of digits for `^\d+$` to be able to match.

If you apply it to VIM:

```console
/\d\+
```

It matches 4

The correct regex is:

```console
/^\d\+$
```

Then, it will not match “qsdf4ghjk”, It only matches “2222”, “12323”, “23”, etc.

It is easy for the user to accidentally type in a space. When Perl reads from a line from a text file, the line break will also be stored in the variable. So before validating input, it is good practice to trim leading and trailing whitespace. `^\s+` matches leading whitespace and `\s+$` matches trailing whitespace. 

In VIM:

```console
/^\s\+
```

```console
/^\s\+$
```

In Perl, you could use $input =~ s/^\s+|\s+$//g. Handy use of alternation and /g allows us to do this in a single line of code.

#     * [Using ^ and $ as Start of Line and End of Line Anchors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

If you have a string consisting of multiple lines, like “first line\nsecond line” (where \n indicates a line break), it is often desirable to work with lines, rather than the entire string. Therefore, all the regex engines discussed in this tutorial have the option to expand the meaning of both anchors. `^` can then match at the start of the string (before the “f” in the above string), as well as after each line break (between “\n” and “s”). Likewise, `$` will still match at the end of the string (after the last “e”), and also before every line break (between “e” and “\n”).

In text editors like EditPad Pro or GNU Emacs, and regex tools like PowerGREP, the caret and dollar always match at the start and end of each line. This makes sense because those applications are designed to work with entire files, rather than short strings.

In all programming languages and libraries discussed in this book , except Ruby, you have to explicitly activate this extended functionality. It is traditionally called "multi-line mode". In Perl, you do this by adding an m after the regex code, like this: m/^regex$/m;. In .NET, the anchors match before and after newlines when you specify RegexOptions.Multiline, such as in Regex.Match("string", "regex", RegexOptions.Multiline).

#     * [Permanent Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

`\A` only ever matches at the start of the string. Likewise, `\Z` only ever matches at the end of the string. These two tokens never match at line breaks. This is true in all regex flavors discussed in this tutorial, even when you turn on “multiline mode”. In EditPad Pro and PowerGREP, where the caret and dollar always match at the start and end of lines, `\A` and `\Z` only match at the start and the end of the entire file.

#     * [Zero-Length Matches](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

We saw that the anchors match at a position, rather than matching a character. This means that when a regex only consists of one or more anchors, it can result in a zero-length match. Depending on the situation, this can be very useful or undesirable. Using `^\d*$` to test if the user entered a number.

> notice the use of the star instead of the plus would cause the script to accept an empty string as a valid input. See below.

In VIM:

```console
/^\d*$
```

![Screen Shot 2021-05-16 at 6 37 56](https://user-images.githubusercontent.com/24994818/118395691-531c6080-b611-11eb-9840-df7e9e36447a.png)

Take a look how Zero-length matches.

However, matching only a position can be very useful. In email, for example, it is common to prepend a “greater than” symbol and a space to each line of the quoted message. In VB.NET, we can easily do this with Dim Quoted as String = Regex.Replace(Original, "^", "> ", RegexOptions.Multiline). We are using multi-line mode, so the regex `^` matches at the start of the quoted message, and after each newline. The Regex.Replace method will remove the regex match from the string, and insert the replacement string (greater than symbol and a space). Since the match does not include any characters, nothing is deleted. However, the match does include a starting position, and the replacement string is inserted there, just like we want it.

#     * [Strings Ending with a Line Break](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Even though `\Z` and `$` only match at the end of the string (when the option for the caret and dollar to match at embedded line breaks is off), there is one exception. If the string ends with a line break, then `\Z` and `$` will match at the position before that line break, rather than at the very end of the string. This “enhancement” was introduced by Perl, and is copied by many regex flavors, including Java, .NET and PCRE. In Perl, when reading a line from a file, the resulting string will end with a line break. Reading a line from a file with the text “joe” results in the string “joe\n”. When applied to this string, both `^[a-z]+$` and `\A[a-z]+\Z` will match „joe”.

Applying this In VIM, you will find this at this moment:

```c
/^[a-z]\+$
```

![Screen Shot 2021-05-16 at 6 53 41](https://user-images.githubusercontent.com/24994818/118396164-d2ab2f00-b613-11eb-984b-0e7759e67e2b.png)

If you only want a match at the absolute very end of the string, use `\z` (lower case z instead of upper case Z). `\A[a-z]+\z` does not match “joe\n”. `\z` matches after the line break, which is not matched by the character class.

#     * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Let’s see what happens when we try to match `^4$` to “749\n486\n4”. Which is:

```console
749
486
4
```

> Where \n represents a newline character, in multi-line mode. 

As usual, the regex engine starts at the first character: “7”. The first token in the regular expression is `^`. Since this token is a zero-width token, the engine does not try to match it with the character, but rather with the position before the character that the regex engine has reached so far. `^` indeed matches the position before “7”. The engine then advances to the next regex token: `4`. Since the previous token was zero-width, the regex engine does not advance to the next character in the string. It remains at “7”. `4` is a literal character, which does not match “7”. There are no other permutations of the regex, so the engine starts again with the first regex token, at the next character: “4”. This time, `^` cannot match at the position before the 4. This position is preceded by a character, and that character is not a newline. The engine continues at “9”, and fails again. The next attempt, at “\n”, also fails. Again, the position before “\n” is preceded by a character, “9”, and that character is not a newline.

Then, the regex engine arrives at the second “4” in the string. The `^` can match at the position before the “4”, because it is preceded by a newline character. Again, the regex engine advances to the next regex token, `4`, but does not advance the character position in the string. `4` matches „4”, and the engine advances both the regex token and the string character. Now the engine attempts to match `$` at the position before (indeed: before) the “8”. The dollar cannot match here, because this position is followed by a character, and that character is not a newline.

Yet again, the engine must try to match the first token again. Previously, it was successfully matched at the second “4”, so the engine continues at the next character, “8”, where the caret does not match. Same at the six and the newline. 

Finally, the regex engine tries to match the first token at the third “4” in the string. With success. After that, the engine successfully matches `4` with „4”. The current regex token is advanced to `$`, and the current character is advanced to the very last position in the string: the void after the string. No regex token that needs a character to match can match here. Not even a negated character class. However, we are trying to match a dollar sign, and the mighty dollar is a strange beast. It is zero-width, so it will try to match the position before the current character. It does not matter that this “character” is the void after the string. In fact, the dollar will check the current character. It must be either a newline, or the void after the string, for `$` to match the position before the current character. Since that is the case after the example, the dollar matches successfully. Since `$` was the last token in the regex, the engine has found a successful match: the last „4” in the string.

![Screen Shot 2021-05-16 at 22 32 16](https://user-images.githubusercontent.com/24994818/118429155-a5539500-b696-11eb-9b94-0c835703ceaf.png)

#     * [Another Inside Look](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Earlier I mentioned that `^\d*$` would successfully match an empty string. Let’s see why. There is only one “character” position in an empty string: the void after the string. The first token in the regex is `^`. It matches the position before the void after the string, because it is preceded by the void before the string. The next token is `\d*`. As we will see later, one of the star’s effects is that it makes the `\d`, in this case, optional. The engine will try to match `\d` with the void after the string. That fails, but the star turns the failure of the `\d` into a zero-width success. The engine will proceed with the next regex token, without advancing the position in the string. So the engine arrives at `$`, and the void after the string. We already saw that those match. At this point, the entire regex has matched the empty string, and the engine reports success.

![Screen Shot 2021-05-16 at 22 37 07](https://user-images.githubusercontent.com/24994818/118429413-43475f80-b697-11eb-9762-83530dd154c2.png)

#     * [Caution for Programmers](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

A regular expression such as `$` all by itself can indeed match after the string. If you would query the engine for the character position, it would return the length of the string if string indices are zero-based, or the length+1 if string indices are one-based in your programming language. If you would query the engine for the length of the match, it would return zero.

What you have to watch out for is that String[Regex.MatchPosition] may cause an access violation or segmentation fault, because MatchPosition can point to the void after the string. This can also happen with `^` and `^$` if the last character in the string is a newline.

# 7. [Word Boundaries](https://github.com/c4arl0s/RegularExpressions#7-word-boundaries)

The metacharacter `\b` is an anchor like the caret and the dollar sign. It matches at a position that is called a “word boundary”. This match is zero-length.

There are four different positions that qualify as word boundaries:

1. Before the first character in the string, if the first character is a word character.
2. After the last character in the string, if the last character is a word character.
3. Between a word character and a non-word character following right after the word character.
4. Between a non-word character and a word character following right after the non-word character.

Simply put: `\b` allows you to perform a “whole words only” search using a regular expression in the form of `\bword\b`. A “word character” is a character that can be used to form words. All characters that are not “word characters” are “non-word characters”. 

This works for the grep command.

```swift
$ grep "\bword\b" README.md
```

![Screen Shot 2021-05-16 at 22 49 13](https://user-images.githubusercontent.com/24994818/118430178-1b58fb80-b699-11eb-83b1-326f421f0d60.png)

The exact list of characters is different for each regex flavor, but all word characters are always matched by the short-hand character class `\w`.

![Screen Shot 2021-05-16 at 22 45 36](https://user-images.githubusercontent.com/24994818/118429917-73433280-b698-11eb-9ebe-70cb8455b8d5.png)

All non-word characters are always matched by `\W`.

![Screen Shot 2021-05-16 at 22 46 22](https://user-images.githubusercontent.com/24994818/118429953-8d7d1080-b698-11eb-8184-01620851efa4.png)

In Perl and the other regex flavors discussed in this tutorial, there is only one metacharacter that matches both before a word and after a word. This is because any position between characters can never be both at the start and at the end of a word. Using only one operator makes things easier for you.

Note that `\w` usually also matches digits. So `\b4\b` can be used to match a 4 that is not part of a larger number. This regex will not match “44 sheets of a4”. So saying "`\b` matches before and after an alphanumeric sequence“ is more exact than saying ”before and after a word". **This is useless for VIM**.

#     * [Negated Word Boundary](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

`\B` is the negated version of `\b`. `\B` matches at every position where `\b` does not. Effectively, `\B` matches at any position between two word characters as well as at any position between two non-word characters.

#     * [Looking Inside the Regex Engine](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Let’s see what happens when we apply the regex `\bis\b` to the string:

```txt
This island is beautiful.
```

The engine starts with the first token `\b` at the first character “T”. Since this token is zero-length, the position before the character is inspected. `\b` matches here, because the T is a word character and the character before it is the void before the start of the string. The engine continues with the next token: the literal `i`. The engine does not advance to the next character in the string, because the previous regex token was zero-width. `i` does not match “T”, so the engine retries the first token at the next character position.

`\b` cannot match at the position between the “T” and the “h”. It cannot match between the “h” and the “i” either, and neither between the “i” and the “s”.

The next character in the string is a space. `\b` matches here because the space is not a word character, and the preceding character is. Again, the engine continues with the `i` which does not match with the space.

Advancing a character and restarting with the first regex token, `\b` matches between the space and the second “i” in the string. Continuing, the regex engine finds that `i` matches „i” and `s` matches „s”. Now, the engine tries to match the second `\b` at the position before the “l”. This fails because this position is between two word characters. The engine reverts to the start of the regex and advances one character to the “s” in “island”. Again, the `\b` fails to match and continues to do so until the second space is reached. It matches there, but matching the `i` fails.

But `\b` matches at the position before the third “i” in the string. The engine continues, and finds that `i` matches „i” and `s` matches `s`. The last token in the regex, `\b`, also matches at the position before the second space in the string because the space is not a word character, and the character before it is.

The engine has successfully matched the word „is” in our string, skipping the two earlier occurrences of the characters i and s. 

Using grep: `grep "\bis\b" README.md`

![Screen Shot 2021-05-17 at 23 44 40](https://user-images.githubusercontent.com/24994818/118591546-f2ed0200-b769-11eb-8339-922457878901.png)

If we had used the regular expression `is`, it would have matched the „is” in “This”.

Using grep: `grep "is" README.md`

![Screen Shot 2021-05-17 at 23 45 47](https://user-images.githubusercontent.com/24994818/118591610-131cc100-b76a-11eb-9010-e79045e949d1.png)

#     * [Tcl Word Boundaries](https://github.com/c4arl0s/RegularExpressions#regular-expression---content)

Word boundaries, as described above, are supported by all regular expression flavors described in in this book , except for the two POSIX RE flavors and the Tcl regexp command. POSIX does not support word boundaries at all. Tcl uses a different syntax.

In Tcl, `\b` matches a backspace character, just like `\x08` in most regex flavors (including Tcl’s). `\B` matches a single backslash character in Tcl, just like `\\` in all other regex flavors (and Tcl too).

Tcl uses the letter “y” instead of the letter “b” to match word boundaries. `\y` matches at any word boundary position, while `\Y` matches at any position that is not a word boundary. These Tcl regex tokens match exactly the same as `\b` and `\B` in Perl-style regex flavors. They don’t discriminate between the start and the end of a word.

cl has two more word boundary tokens that do discriminate between the start and end of a word. `\m` matches only at the start of a word. That is, it matches at any position that has a non-word character to the left of it, and a word character to the right of it. It also matches at the start of the string if the first character in the string is a word character. `\M` matches only at the end of a word. It matches at any position that has a word character to the left of it, and a non-word character to the right of it. It also matches at the end of the string if the last character in the string is a word character.

The only regex engine that supports Tcl-style word boundaries (besides Tcl itself) is the JGsoft engine. In PowerGREP and EditPad Pro, `\b` and `\B` are Perl-style word boundaries, and `\y`, `\Y`, `\m` and `\M` are Tcl-style word boundaries.

In most situations, the lack of `\m` and `\M` tokens is not a problem. `\yword\y` finds “whole words only” occurrences of “word” just like `\mword\M` would. `\Mword\m` could never match anywhere, since `\M` never matches at a position followed by a word character, and `\m` never at a position preceded by one. If your regular expression needs to match characters before or after `\y`, you can easily specify in the regex whether these characters should be word characters or non-word characters. E.g. if you want to match any word, `\y\w+\y` will give the same result as `\m.+\M`. Using `\w` instead of the dot automatically restricts the first `\y` to the start of a word, and the second `\y` to the end of a word. Note that `\y.+\y` would not work. This regex matches each word, and also each sequence of non-word characters between the words in your subject string. That said, if your flavor supports `\m` and `\M`, the regex engine could apply `\m\w+\M` slightly faster than `\y\w+\y`, depending on its internal optimizations.

If your regex flavor supports lookahead and lookbehind, you can use `(?<!\w)(?=\w)` to emulate Tcl’s `\m` and `(?<=\w)(?!\w)` to emulate `\M`. Though quite a bit more verbose, these lookaround constructs match exactly the same as Tcl’s word boundaries.

If your flavor has lookahead but not lookbehind, and also has Perl-style word boundaries, you can use `\b(?=\w)` to emulate Tcl’s `\m` and `\b(?!\w)` to emulate `\M`. `\b` matches at the start or end of a word, and the lookahead checks if the next character is part of a word or not. If it is we’re at the start of a word. Otherwise, we’re at the end of a word.

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


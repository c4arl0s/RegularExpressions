# [Regular Expression]()

Table of Contents

1. [Regular Expression Tutorial](https://github.com/c4arl0s/RegularExpressions#1-regular-expression-tutorial)
    * [What Regular Expressions Are Exactly - Terminology]()
    * [Different Regular Expression Engines]()
    * [Give Regexes a First Try]()
2. [Literal Characters](https://github.com/c4arl0s/RegularExpressions#2-literal-characters)
    * [Special Characters]()
    * [Special Characters and Programming Languages]()
    * [Non-Printable Characters]()
3. [First Look at How a Regex Engine Works Internally](https://github.com/c4arl0s/RegularExpressions#3-first-look-at-how-a-regex-engine-works-internally)
    * [The Regex-Directed Engine Always Returns the Leftmost Match]()
4. [Character Classes or Character Sets](https://github.com/c4arl0s/RegularExpressions#4-character-classes-or-character-sets)
    * [Useful Applications]()
    * [Negated Character Classes]()
    * [Metacharacters Inside Character Classes]()
    * [Shorthand Character Classes]()
    * [Negated Shorthand Character Classes]()
    * [Repeating Character Classes]()
    * [Looking Inside The Regex Engine]()
5. [The Dot Matches (Almost) Any Character](https://github.com/c4arl0s/RegularExpressions#5-the-dot-matches-almost-any-character-)
    * [Use The Dot Sparingly]()
    * [Use Negated Character Sets Instead of the Dot]()
6. [Start of String and End of String Anchors](https://github.com/c4arl0s/RegularExpressions#6-start-of-string-and-end-of-string-anchors)
    * [Useful Applications]()
    * [Using ^ and $ as Start of Line and End of Line Anchors]()
    * [Permanent Start of String and End of String Anchors]()
    * [Zero-Length Matches]()
    * [Strings Ending with a Line Break]()
    * [Looking Inside the Regex Engine]()
    * [Another Inside Look]()
    * [Caution for Programmers]()
7. [Word Boundaries](https://github.com/c4arl0s/RegularExpressions#7-word-boundaries)
    * [Negated Word Boundary]()
    * [Looking Inside the Regex Engine]()
    * [Tcl Word Boundaries]()
8. [Alternation with The Vertical Bar or Pipe Symbol](https://github.com/c4arl0s/RegularExpressions#8-alternation-with-the-vertical-bar-or-pipe-symbol)
    * [Remember That The Regex Engine Is Eager]()
9. [Optional Items](https://github.com/c4arl0s/RegularExpressions#9-optional-items)
    * [Important Regex Concept: Greediness]()
    * [Looking Inside The Regex Engine]()
10. [Repetition with Star and Plus](https://github.com/c4arl0s/RegularExpressions#10-repetition-with-star-and-plus)
    * [Limiting Repetition]()
    * [Watch Out for The Greediness!]()
    * [Looking Inside The Regex Engine]()
    * [Laziness Instead of Greediness]()
    * [An Alternative to Laziness]()
    * [Repeating \Q...\E Escape Sequences]()
11. [Use Round Brackets for Grouping](https://github.com/c4arl0s/RegularExpressions#11-use-round-brackets-for-grouping)
    * [Round Brackets Create a Backreference]()
    * [How to Use Backreferences]()
    * [The Entire Regex Match As Backreference Zero]()
    * [Using Backreferences in The Regular Expression]()
    * [Looking Inside The Regex Engine]()
    * [Repetition and Backreferences]()
    * [Useful Example: Checking for Doubled Words]()
    * [Parentheses and Backreferences Cannot Be Used Inside Character Classes]()
12. [Named Capturing Groups](https://github.com/c4arl0s/RegularExpressions#12-named-capturing-groups)
    * [Named Capture with Python, PCRE and PHP]()
    * [Named Capture with .NET’s System.Text.RegularExpressions]()
    * [Names and Numbers for Capturing Groups]()
    * [Other Regex Flavors]()
13. [Unicode Regular Expressions](https://github.com/c4arl0s/RegularExpressions#13-unicode-regular-expressions)
    * [Characters, Code Points and Graphemes or How Unicode Makes a Mess of Things]()
    * [How to Match a Single Unicode Grapheme]()
    * [Matching a Specific Code Point]()
    * [Unicode Character Properties]()
    * [Unicode Scripts]()
    * [Unicode Blocks]()
    * [Alternative Unicode Regex Syntax]()
    * [Do You Need To Worry About Different Encodings?]()
14. [Regex Matching Modes](https://github.com/c4arl0s/RegularExpressions#14-regex-matching-modes)
    * [
15. [Possessive Quantifiers](https://github.com/c4arl0s/RegularExpressions#15-possessive-quantifiers)
16. [Atomic Grouping](https://github.com/c4arl0s/RegularExpressions#16-atomic-grouping)
17. [Lookahead and Lookbehind Zero-Width Assertions](https://github.com/c4arl0s/RegularExpressions#17-lookahead-and-lookbehind-zero-width-assertions)
18. [Testing The Same Part of a String for More Than One Requirement](https://github.com/c4arl0s/RegularExpressions#18-testing-the-same-part-of-a-string-for-more-than-one-requirement)
19. [Continuing at The End of The Previous Match](https://github.com/c4arl0s/RegularExpressions#19-continuing-at-the-end-of-the-previous-match)
20. [If-Then-Else Conditionals in Regular Expressions](https://github.com/c4arl0s/RegularExpressions#20-if-then-else-conditionals-in-regular-expressions)
21. [XML Schema Character Classes ](https://github.com/c4arl0s/RegularExpressions#21-xml-schema-character-classes-)
22. [POSIX Bracket Expressions](https://github.com/c4arl0s/RegularExpressions#22-posix-bracket-expressions)
23. [Adding Comments to Regular Expressions](https://github.com/c4arl0s/RegularExpressions#23-adding-comments-to-regular-expressions)
24. [Free-Spacing Regular Expressions](https://github.com/c4arl0s/RegularExpressions#24-free-spacing-regular-expressions)

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


# 1. [Regular Expression Tutorial]()

In this tutorial, I will teach you all you need to know to be able to craft powerful time-saving regular expressions. I will start with the most basic concepts, so that you can follow this tutorial even if you know nothing at all about regular expressions yet.
But I will not stop there. I will also explain how a regular expression engine works on the inside, and alert you at the consequences. This will help you to understand quickly why a particular regex does not do what you initially expected. It will save you lots of guesswork and head scratching when you need to write more complex regexes.

    * [What Regular Expressions Are Exactly - Terminology]()
Basically, a regular expression is a pattern describing a certain amount of text. Their name comes from the mathematical theory on which they are based. But we will not dig into that. Since most people including myself are lazy to type, you will usually find the name abbreviated to regex or regexp. I prefer regex, because it is easy to pronounce the plural “regexes”. In this book, regular expressions are printed between guillemots: «regex». They clearly separate the pattern from the surrounding text and punctuation.

This first example is actually a perfectly valid regex. It is the most basic pattern, simply matching the literal text „regex”. A "match" is the piece of text, or sequence of bytes or characters that pattern was found to correspond to by the regex processing software. Matches are indicated by double quotation marks, with the left one at the base of the line.

«\b[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,4}\b» is a more complex pattern. It describes a series of letters, digits, dots, underscores, percentage signs and hyphens, followed by an at sign, followed by another series of letters, digits and hyphens, finally followed by a single dot and between two and four letters. In other words: this pattern describes an email address.

With the above regular expression pattern, you can search through a text file to find email addresses, or verify if a given string looks like an email address. In this tutorial, I will use the term “string” to indicate the text that I am applying the regular expression to. I will indicate strings using regular double quotes. The term “string” or “character string” is used by programmers to indicate a sequence of characters. In practice, you can use regular expressions with whatever data you can access using the application or programming language you are working with.

    * [Different Regular Expression Engines]()

A regular expression “engine” is a piece of software that can process regular expressions, trying to match the pattern to the given string. Usually, the engine is part of a larger application and you do not access the engine directly. Rather, the application will invoke it for you when needed, making sure the right regular expression is applied to the right file or data.

As usual in the software world, different regular expression engines are not fully compatible with each other. It is not possible to describe every kind of engine and regular expression syntax (or “flavor”) in this tutorial. I will focus on the regex flavor used by Perl 5, for the simple reason that this regex flavor is the most popular one, and deservedly so. Many more recent regex engines are very similar, but not identical, to the one of Perl 5. Examples are the open source PCRE engine (used in many tools and languages like PHP), the .NET regular expression library, and the regular expression package included with version 1.4 and later of the Java JDK. I will point out to you whenever differences in regex flavors are important, and which features are specific to the Perl-derivatives mentioned above.

    * [Give Regexes a First Try]()

You can easily try the following yourself in a text editor that supports regular expressions, such as EditPad Pro. If you do not have such an editor, you can download the free evaluation version of EditPad Pro to try this out. EditPad Pro’s regex engine is fully functional in the demo version. As a quick test, copy and paste the text of this page into EditPad Pro. Then select Search|Show Search Panel from the menu. In the search pane that appears near the bottom, type in «regex» in the box labeled “Search Text”. Mark the “Regular expression” checkbox, and click the Find First button. This is the leftmost button on the search panel. See how EditPad Pro’s regex engine finds the first match. Click the Find Next button, which sits next to the Find First button, to find further matches. When there are no further matches, the Find Next button’s icon will flash briefly.

Now try to search using the regex «reg(ular expressions?|ex(p|es)?)» . This regex will find all names, singular and plural, I have used on this page to say “regex”. If we only had plain text search, we would have needed 5 searches. With regexes, we need just one search. Regexes save you time when using a tool like EditPad Pro. Select Count Matches in the Search menu to see how many times this regular expression can match the file you have open in EditPad Pro.

If you are a programmer, your software will run faster since even a simple regex engine applying the above regex once will outperform a state of the art plain text search algorithm searching through the data five times. Regular expressions also reduce development time. With a regex engine, it takes only one line (e.g. in Perl, PHP, Java or .NET) or a couple of lines (e.g. in C using PCRE) of code to, say, check if the user’s input looks like a valid email address.

In this case we are going to use grep tool, from unix command line.

```console
Mon Jul 27 ~/iOS/30Properties_ObjectiveC 
$ cat README.md | grep "view"
In the last chapter, you created a class called **Appliance** that had two properties: **productName** and **voltage**. Let's review how those properties work.
```

It retrieves all lines where the sting "view" appears.


# 2. [Literal Characters]()

The most basic regular expression consists of a single literal character, e.g.: «a». It will match the first occurrence of that character in the string. If the string is “Jack is a boy”, it will match the „a” after the “J”.

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

    * [Special Characters]()

Because we want to do more than simply search for literal pieces of text, we need to reserve certain characters for special use. In the regex flavors discussed in this tutorial, there are 11 characters with special meanings: the opening square bracket «[», the backslash «\», the caret «^», the dollar sign «$», the period or dot «.», the vertical bar or pipe symbol «|», the question mark «?», the asterisk or star «*», the plus sign «+», the opening round bracket «(» and the closing round bracket «)». These special characters are often called **“metacharacters”**.

If you want to use any of these characters as a literal in a regex, you need to escape them with a backslash. If you want to match „1+1=2”, the correct regex is «1\+1=2». Otherwise, the plus sign will have a special meaning.

Note that «1+1=2», with the backslash omitted, is a valid regex. So you will not get an error message. But it will not match “1+1=2”. It would match „111=2” in “123+111=234”, due to the special meaning of the plus character.

If you forget to escape a special character where its use is not allowed, such as in «+1», then you will get an error message.

In the case of the grep tool, this does not happen, use a tool like vim to see it.

Doing this in vim, it is also succesfull. 

```console
/1+1 = 2
```

Most regular expression flavors treat the brace «{» as a literal character, unless it is part of a repetition operator like «{1,3}». So you generally do not need to escape it with a backslash, though you can do so if you want. An exception to this rule is the java.util.regex package: it requires all literal braces to be escaped.

All other characters should not be escaped with a backslash. That is because the backslash is also a special character. The backslash in combination with a literal character can create a regex token with a special meaning. E.g. «\d» will match a single digit from 0 to 9.

Escaping a single metacharacter with a backslash works in all regular expression flavors. Many flavors also support the \Q...\E escape sequence. All the characters between the \Q and the \E are interpreted as literal characters. E.g. «\Q*\d+*\E» matches the literal text „*\d+*”. The \E may be omitted at the end of the regex, so «\Q*\d+*» is the same as «\Q*\d+*\E». This syntax is supported by the JGsoft engine, Perl and PCRE, both inside and outside character classes. Java supports it outside character classes only, and quantifies it as one token.

    * [Special Characters and Programming Languages]()

If you are a programmer, you may be surprised that characters like the single quote and double quote are not special characters. That is correct. When using a regular expression or grep tool like PowerGREP or the search function of a text editor like EditPad Pro, you should not escape or repeat the quote characters like you do in a programming language.

In your source code, you have to keep in mind which characters get special treatment inside strings by your programming language. That is because those characters will be processed by the compiler, before the regex library sees the string. So the regex «1\+1=2» must be written as "1\\+1=2" in C++ code. The C++ compiler will turn the escaped backslash in the source code into a single backslash in the string that is passed on to the regex library. To match „c:\temp”, you need to use the regex «c:\\temp». As a string in C++ source code, this regex becomes "c:\\\\temp". Four backslashes to match a single one indeed.

See the tools and languages section in this book for more information on how to use regular expressions in various programming languages.

    * [Non-Printable Characters]()

You can use special character sequences to put non-printable characters in your regular expression. Use «\t» to match a tab character (ASCII 0x09), «\r» for carriage return (0x0D) and «\n» for line feed (0x0A). More exotic non-printables are «\a» (bell, 0x07), «\e» (escape, 0x1B), «\f» (form feed, 0x0C) and «\v» (vertical tab, 0x0B). Remember that Windows text files use “\r\n” to terminate lines, while UNIX text files use “\n”.
You can include any character in your regular expression if you know its hexadecimal ASCII or ANSI code for the character set that you are working with. In the Latin-1 character set, the copyright symbol is character 0xA9. So to search for the copyright symbol, you can use «\xA9». Another way to search for a tab is to use «\x09». Note that the leading zero is required.
Most regex flavors also support the tokens «\cA» through «\cZ» to insert ASCII control characters. The letter after the backslash is always a lowercase c. The second letter is an uppercase letter A through Z, to indicate Control+A through Control+Z. These are equivalent to «\x01» through «\x1A» (26 decimal). E.g. «\cM» matches a carriage return, just like «\r» and «\x0D». In XML Schema regular expressions, «\c» is a shorthand character class that matches any character allowed in an XML name.
If your regular expression engine supports Unicode, use «\uFFFF» rather than «\xFF» to insert a Unicode character. The euro currency sign occupies code point 0x20AC. If you cannot type it on your keyboard, you can insert it into a regular expression with «\u20AC».

# 3. [First Look at How a Regex Engine Works Internally]()

Knowing how the regex engineworks will enable you to craft better regexes more easily. It will help you understand quickly why a particular regex does not do what you initially expected. This will save you lots of guesswork and head scratching when you need to write more complex regexes.
There are two kinds of regular expression engines: text-directed engines, and regex-directed engines. Jeffrey Friedl calls them DFA and NFA engines, respectively. All the regex flavors treated in this tutorial are based on regex-directed engines. This is because certain very useful features, such as lazy quantifiers and backreferences, can only be implemented in regex-directed engines. No surprise that this kind of engine is more popular.
Notable tools that use text-directed engines are awk, egrep, flex, lex, MySQL and Procmail. For awk and egrep, there are a few versions of these tools that use a regex-directed engine.
You can easily find out whether the regex flavor you intend to use has a text-directed or regex-directed engine. If backreferences and/or lazy quantifiers are available, you can be certain the engine is regex-directed. You can do the test by applying the regex «regex|regex not» to the string “regex not”. If the resulting match is only „regex”, the engine is regex-directed. If the result is „regex not”, then it is text-directed. The reason behind this is that the regex-directed engine is “eager”.
In this tutorial, after introducing a new regex token, I will explain step by step how the regex engine actually processes that token. This inside look may seem a bit long-winded at certain times. But understanding how the regex engine works will enable you to use its full power and help you avoid common mistakes.

    * [The Regex-Directed Engine Always Returns the Leftmost Match]()

This is a very important point to understand: a regex-directed engine will always return the leftmost match, even if a “better” match could be found later. When applying a regex to a string, the engine will start at the first character of the string. It will try all possible permutations of the regular expression at the first character. Only if all possibilities have been tried and found to fail, will the engine continue with the second character in the text. Again, it will try all possible permutations of the regex, in exactly the same order. The result is that the regex-directed engine will return the **leftmost match**.

When applying «cat» to “He captured a catfish for his cat.”, the engine will try to match the first token in the regex «c» to the first character in the match “H”. This fails. There are no other possible permutations of this regex, because it merely consists of a sequence of literal characters. So the regex engine tries to match the «c» with the “e”. This fails too, as does matching the «c» with the space. Arriving at the 4th character in the match, «c» matches „c”. The engine will then try to match the second token «a» to the 5th character, „a”. This succeeds too. But then, «t» fails to match “p”. At that point, the engine knows the regex cannot be matched starting at the 4th character in the match. So it will continue with the 5th: “a”. Again, «c» fails to match here and the engine carries on. At the 15th character in the match, «c» again matches „c”. The engine then proceeds to attempt to match the remainder of the regex at character 15 and finds that «a» matches „a” and «t» matches „t”.
The entire regular expression could be matched starting at character 15. The engine is "eager" to report a match. It will therefore report the first three letters of catfish as a valid match. The engine never proceeds beyond this point to see if there are any “better” matches. The first match is considered good enough.


In this first example of the engine’s internals, our regex engine simply appears to work like a regular text search routine. A text-directed engine would have returned the same result too. However, it is important that you can follow the steps the engine takes in your mind. In following examples, the way the engine works will have a profound impact on the matches it will find. Some of the results may be surprising. But they are always logical and predetermined, once you know how the engine works.

# 4. [Character Classes or Character Sets]()


With a "character class", also called “character set”, you can tell the regex engine to match only one out of several characters. Simply place the characters you want to match between square brackets. If you want to match an a or an e, use «[ae]». You could use this in «gr[ae]y» to match either „gray” or „grey”. Very useful if you do not know whether the document you are searching through is written in American or British English.
A character class matches only a single character. «gr[ae]y» will not match “graay”, “graey” or any such thing. The order of the characters inside a character class does not matter. The results are identical.

```console

With a "character class", also called “character set”, you can tell the regex engine to match only one out of several characters. Simply place the characters you want to match between square brackets. If you want to match an a or an e, use «[ae]». You could use this in «gr[ae]y» to match either „gray” or „grey”. Very useful if you do not know whether the document you are searching through is written in American or British English.
A character class matches only a single character. «gr[ae]y» will not match “graay”, “graey” or any such thing. The order of the characters inside a character class does not matter. The results are identical.
```

You can use a hyphen inside a character class to specify a range of characters. «[0-9]» matches a single digit between 0 and 9. You can use more than one range. «[0-9a-fA-F]» matches a single hexadecimal digit, case insensitively. You can combine ranges and single characters. «[0-9a-fxA-FX]» matches a hexadecimal digit or the letter X. Again, the order of the characters and the ranges does not matter.

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
    * [Useful Applications]()

Find a word, even if it is misspelled, such as «sep[ae]r[ae]te» or «li[cs]en[cs]e».
Find an identifier in a programming language with «[A-Za-z_][A-Za-z_0-9]*».
Find a C-style hexadecimal number with «0[xX][A-Fa-f0-9]+».

    * [Negated Character Classes]()
    * [Metacharacters Inside Character Classes]()
    * [Shorthand Character Classes]()
    * [Negated Shorthand Character Classes]()
    * [Repeating Character Classes]()
    * [Looking Inside The Regex Engine]()


# 5. [The Dot Matches (Almost) Any Character ]()

# 6. [Start of String and End of String Anchors]()

Thus far, I have explained literal characters and character classes. In both cases, putting one in a regex will cause the regex engine to try to match a single character.
Anchors are a different breed. They do not match any character at all. Instead, they match a position before, after or between characters. They can be used to “anchor” the regex match at a certain position. The caret «^» matches the position before the first character in the string. Applying «^a» to “abc” matches „a”. «^b» will not match “abc” at all, because the «b» cannot be matched right after the start of the string, matched by «^». See below for the inside view of the regex engine.

```console
$ cat article.txt | grep "^A" | tail -1                                                                             
A second tweet from another leaker, @Jioriku, added to the iMac rumors by writing "The iMac redesign is not coming for this 10th-generation Intel refresh. They are saving it for their own silicon," referencing Apple Silicon.   
```

Similarly, «$» matches right after the last character in the string. «c$» matches „c” in “abc”, while «a$» does not match at all.

```console
$ cat article.txt | grep "2$"
1+1 = 2
```

# 7. [Word Boundaries]()
# 8. [Alternation with The Vertical Bar or Pipe Symbol]()
# 9. [Optional Items]()
# 10. [Repetition with Star and Plus]()
# 11. [Use Round Brackets for Grouping]()
# 12. [Named Capturing Groups]()
# 13. [Unicode Regular Expressions]()
# 14. [Regex Matching Modes]()
# 15. [Possessive Quantifiers]()
# 16. [Atomic Grouping]()
# 17. [Lookahead and Lookbehind Zero-Width Assertions]()
# 18. [Testing The Same Part of a String for More Than One Requirement]()
# 19. [Continuing at The End of The Previous Match]()
# 20. [If-Then-Else Conditionals in Regular Expressions]()
# 21. [XML Schema Character Classes ]()
# 22. [POSIX Bracket Expressions]()
# 23. [Adding Comments to Regular Expressions]()
# 24. [Free-Spacing Regular Expressions]()
# 
# Examples
# 
# 1. [Sample Regular Expression]()
# 2. [Matching Floating Point Numbers with a Regular Expression]()
# 3. [How to Find or Validate an Email Address]()
# 4. [Matching a Valid Date]()
# 5. [Matching Whole Lines of Text]()
# 6. [Deleting Duplicate Lines From a File ]()
# 8. [Find Two Words Near Each Other]()
# 9. [Runaway Regular Expressions: Catastrophic Backtracking]()
# 10. [Repeating a Capturing Group vs. Capturing a Repeated Group]()

# English Style Guide

This English Style Guide provides guidance for spelling, capitalization, and usage of common terms. All authors and editors should use this guide so that our articles are consistent site-wide. It's a good idea to skim through this guide before starting any new article, update, or edit as this document evolves continuously.

For questions not answered here, follow the [AP style guide](https://www.apstylebook.com/) and the [Apple Style Guide](http://help.apple.com/applestyleguide/#/). 

Finally, we use American English spelling and style in our publications. [See the General Style Guidelines](#general-style-guidelines) for resources to tell the difference between American and British English.

## Contributing

To contribute to this guide, please create a new branch for your changes (you can do this right on the GitHub website if you like), make your changes, then open a pull request and request one of the Maintainers to review your PR and merge it.

## General Style Guidelines

**above** and **below**
In situations like these: “Here’s how the above function works” and “Add the below function,” "above" and "below" should follow the noun. So it should be: “Here’s how the function above works...” and “Add the function below...”

**acronyms**
In general, write out the full term followed by the acronym in parentheses the first time the phrase appears if you are going to use the acronym at least three times in the article or if understanding the acronym is important for your article. After the first use, use the acronym.

_Example_: "Model-View-Viewmodel (MVVM) is a common architecture for app design... In this tutorial, you'll use MVVM to build..."

If an acronym is commonly-used and easily-recognized (i.e., API or HTTP://), don't write out the full term the first time you use it unless doing so is necessary for your article.

Pluralize acronyms by adding a lower-case s to the end, no apostrophe.

_Example_: "Three commonly-used APIs are..."

**American vs. British English**
Use American English in your articles. If you aren't sure if you're using the right version, you can refer to this [American to British dictionary](http://projectbritain.com/americanbritish/index.html), check a list of common [American vs. British idioms](https://www.italki.com/article/126/up-to-you-or-down-to-you-some-differences-between-british-and-american-english-idioms?hl=en), or paste your text into a [British to American converter](https://www.infoenglish.net/british-to-american-english/). You can also read this [comprehensive guide to British vs. American language](https://en.wikipedia.org/wiki/Comparison_of_American_and_British_English) on Wikipedia.

**apostrophes**
Wordpress needs straight apostrophes (') not curly or smart apostrophes (’). If your editing tool includes curly apostrophes, please make sure you remove them before adding your article to Wordpress. The same applies to curly quotation marks.

**app**
Use _app_ instead of _application_, unless _application_ is more clear or refers to a non-iOS or Android, or other mobile entity.

**Apple**
Use the pronoun *it* to refer to Apple and any other company or organization; do not use *they*.

_Example:_ Apple has its own solution...

**as-is**

**back end, back-end, backend**
"back end" is a noun. You develop the back end. 
"back-end" functions as a (compound) modifier and is hyphenated before a noun. You are the back-end developer who developed the back end. 
"backend" is used in the BFF pattern (Backend for Frontend) 

You are the back-end developer who used the Backend for Frontend pattern to develop the back end.

**base 10**
...or base 2 or base 16 or base 8 when “binary”, “hexadecimal” or “octal” won't do. No hyphenation.

**Bézier curves**

**bolding**
Use the bold style (&lt;em&gt; in WordPress) for things the reader needs to click, modify, enter into a text field or otherwise notice. This includes file and directory names, but only those that are the action item of a nearby instruction.

When instructing the reader to make changes, bold each object in the process, with the exception of UI elements.

_Example:_ In the hierarchy, select the **SpaceShip** and from the inspector, inside the **Alien Component**, set the **IsDead** property to `false`.

Also use the bold style to highlight important concepts that are being introduced for the first time.

Punctuation always goes outside of bold tags. For example, in div notes, you should always use **Note**: not **Note:**.

For bolding in lists, see **lists**.

**book names**
When you refer to books, italicize their names. 

_Example:_ If you’re new to iOS development and want to learn more, start with _iOS Apprentice_.

**Boolean**
In honor of George Boole. :]

**build and run**
Use lowercase and do not bold.

**button**
Use lowercase, including when instructing the reader to drag one into the scene.

**checkbox** 
Not check box. Note that we don't "tick" checkboxes, since that's British English. We either select or check them.

**client-side**

**code objects**
Methods, functions, protocols, classes, structs, variables and so on — those things that are properly marked inline as code — are treated as proper nouns. "Add the following to `generateLotteryTicket()`:", not "Add the following to the `generateLotteryTicket()` method".

**colons**
The first letter of a *complete sentence* following a colon should be capitalized. So both of the following examples are correct:
* There's one thing you should know: thing.
* There's one thing you should know: Never lick a frozen signpost.

Colons should never appear inside bold formatting.

**commas**
We do not use the serial (Oxford) comma. See the section below for more details.

**contractions**
In general, we prefer contractions, because they make our writing more informal and conversational. Look for phrases like "you will", "it is", "they are", etc. and replace them with "you'll", "it's," "they're", etc.

**Control-click**

**Control-drag**

**coordinates**
_(x, y)_ not _(x,y)_

Note that _coordinate_ refers to one of the group (_the x-coordinate_), while _coordinates_ refers to more than one and usually the entire group (_the GPS coordinates of Cupertino_).

**dashes**
We use three kinds of dashes in articles. Please make sure you're using the right one for your needs:
* **em dashes (—)** are used to join *parts of sentences*. For example, *Learning has never been easier — or more convenient.* Read more about [em dash usage](https://www.grammarly.com/blog/why-you-should-love-the-em-dash/) at grammarly.com. 
* **hyphens (-)** are used to join *words*. *Open-source* and *front-end design* are examples of correct hyphen usage.
* **en dashes (–)** are slightly shorter than em dashes. They are most commonly used to join spans of time or numbers: i.e., the 1950s–1960s.

**data**

The word is plural. Data are, not data is. Except for Lt. Commander Data. He's singular.

There are a few cases where **data** can be considered a singular, collective noun, when you consider the various pieces of data as a set. E.g.: The data is correct. (The data, as a singular collective unit, is correct.) One gigabyte of data **is** a lot of information to sort through.

**delight**

Please refrain from using this word when talking about UI animations. You’re a better writer than that.

**deselect vs. unselect**

If you are talking about removing a check from a checkbox, use "deselect". "Unselect" is incorrect. "Unselected" can be used for an option that hasn't been checked.

* **Correct**: Scroll down to the newsletter options and deselect "Opt-In".
* **Correct**: Because the user hasn't completed the form, "Opt-Out" is still unselected.

**document outline**
Apple tends to use the term _outline view_ in its documentation, so that is OK as well; however, use one or the other for consistency.

**double-click**

**drop-down**

**e-book**

**e-commerce**

**editors**
Use lowercase; e.g. _assistant editor_, _standard editor_, _scene editor_.

**emoticons/emojis**
These are not punctuation; sentences that end with an emoticon still need appropriate punctuation before the emoticon rather than after it. 

**file extensions**
either _XXX_ or _.xxx_

**frame rate**
_FPS_ not _fps_

**front end, front-end, frontend**
"front end" is a noun. You develop the front end. 
"front-end" functions as a (compound) modifier and is hyphenated before a noun. You are the front-end developer who developed the front end. 
"frontend" is used in the BFF pattern (Backend for Frontend) 

You are the front-end developer who used the Backend for Frontend pattern to develop the front end. 

**future tense**
Avoid phrases that have awkward future tenses like "will be verbing". When you can, use the present tense, which tends to be more exciting.

* **Incorrect**: In this tutorial, you'll be learning how to...
* **Correct**: In this tutorial, you'll learn how to...

**functions**
see _code objects_.

**game references**
Italicize the names of published games, like _Super Mario Bros._ or _Angry Birds_, but not the names of other software.

**Git**
Unless you're specifically referring to a command using the tool, Git should be a proper noun. When used as a command, make sure to mark it as code: `git`.

**GitHub**

**Gmail**

**hard-coded** as an adjective to describe something, but **hard code** when giving an instruction.

**headers**

* _Casing in articles:_ Capitalize headers, leaving any article, preposition or coordinating conjunction that is three letters or less lowercase, unless it is the first word in the sentence. For example, it is important to capitalize the verb _Go_ but _not_ the word _to_ in **Where to Go From Here?**

* _Casing in books:_ Use sentence casing by capitalizing only the first letter of the first word, except for proper nouns. So **Where to go from here?** or **New features in Swift**

* _Placement:_ Insert when the subject moves from one point to another. When in doubt, more subheadings are usually better than fewer. Also, ensure that if H2 and H3 headers are used, they are nested appropriately. For example, there's no point in having a single H2 and then seventeen H3 headings for the rest of the article. For standards on H2, H3 and bolding in headers, [see our formatting guide.](https://guides.raywenderlich.com/article-author-guide/finish-up/format-your-article#headers).

* _Structure_: Whenever possible, headers should start with gerunds: verbs in their _-ing_ form. So **Checking Your Code** rather than **Check Your Code**, for example.

* _Objects in code tags_: If a heading contains an term that usually uses inline code tags, preserve the term as written but do *not* use the code tags in the header.

    * _Incorrect_: &lt;h2&gt;Using <code>spawnEmoji()</code> Without Losing Your Mind&lt;/h2&gt;
    
    * _Correct_: &lt;h2&gt;Using spawnEmoji() Without Losing Your Mind&lt;/h2&gt;

**he/she, he or she**
Default to "they" instead. If you want to go the distance and correct some of the gender imbalance in this industry, use "she" if you like.

**him/her, him or her**
Use "them" instead. If you want to go the distance and correct some of the gender imbalance in this industry, use "her" if you like.

**his/her, his or her**
Use "their" instead. If you want to go the distance and correct some of the gender imbalance in this industry, use "her" if you like.

**home page**

**ID** not id.

**inline code**
Use the inline code style (&lt;code&gt; in WordPress) for all class, function and method names. Remember to use it for these words:

`nil`  
`if` statement  
`while` loop  
`if-else`  
`Int`  
`enum`  
`switch` statement

**information**
Please, not "info". 

**in order to...**
In almost all cases, "In order to..." can be shortened to "To..." This tightens your prose and saves time for your readers.

**internet**
Not Internet.

**introductory clauses**
Be sure to add a comma after [introductory clauses](https://www.grammarly.com/blog/commas-after-introductory-clauses/). Many grammar guides say that the comma is optional for very short introductory clauses, but our style is to always use it. 

_Examples_: "Now, add the following to..." and "To do that, you'll need to..."

**it** or **that**
Make sure that if you use "it" or "that" in place of a noun, it's abundantly clear what you are referring to. Avoid ambiguity.

**keyboard keys**

Spell meta keys as if you were speaking them out loud. So, for example, most people say "Alt" but not "Esc" or "Ctrl". Therefore, in articles, they should be written as: "Alt", "Escape", and "Control". Similarly, it's "Caps Lock" and "Num Lock" in common parlance, so write those keys that way in articles as well. Any key that makes its own symbol — ".", "a", "." or "-", for example — should just use that symbol.

Capitalize the first letter, whether alone or in multi-press combinations: **Shift-Command-Option-X**, **Control-Alt-F** or **Shift-Ctrl-,**.

You _press_ keys, you don't _type_ or _hit_ them.

**let's** as well as other first-person terms (**I**, **we**, etc.) should be avoided whenever possible. Keep the focus on the reader by using **you**, **your**, etc.

**lists**

When you have items introduced in an ordered (&lt;ol&gt;) or unordered (&lt;ul&gt;) list, bold (&lt;em&gt; in WordPress) each item, then follow it with a colon and the description. Do not use dashes as separators. Those items should be bolded even if they're code structures that would normally use inline code style. The colon should appear _outside_ the bold formatting.

Each list item should end with punctuation if it's a full sentence. If it's only a short sentence fragment, do not punctuate.

_Example_:

&lt;ol&gt;

   &lt;li&gt;&lt;em&gt;Function1&lt;/em&gt;: This function does a thing.&lt;/li&gt;

&lt;/ol&gt;

**login, log in**
"log in" is the verb. You log in to your WordPress account to write your article.
"login" is the adjective (or, if you _really_ must, the noun). "WordPress gives you access to writing tools when it processes your login request."

**long-press**

**menu separators**

We use the "▸" character for menu separators. For example: "File ▸ New ▸ From Template". The use of the backslashes — "File\New\From Template" — has been deprecated. However, please continue to use forward slashes as path separators as in "myproject/assets/puppy.jpg".

```none
▸
BLACK RIGHT-POINTING SMALL TRIANGLE
Unicode: U+25B8, UTF-8: E2 96 B8
```

**methods**
see _code objects_.

**numbers vs. numerals**
Spell out whole numbers up to and including nine, as well as larger numbers that can be expressed in one or two words.

_Examples_: zero, one, nine, six million.

Use numerals for numbers greater than nine; for decimals and percentages; for numbers that express mathematical figures; for addresses, dates, the time of day, and page or chapter numbers; and when a numeral is important for identification purposes.

_Examples_: 10; 25,000; 30%; divide 15 by 3; Chapter 6; Highway 4; Room 2.

Numbers in series should be consistent.

_Example_: She went to five countries on four continents in sixteen days _OR_ She went to 5 countries on 4 continents in 16 days.  
_Example_: The final score was 13–1 _OR_ The final score was thirteen to one.

_Note_: There are a lot of exceptions to these basic rules, so use your best judgment.

**OK**
Don't use _okay_ or _Ok_.

**offscreen**

**onscreen**

**open-source**

**paragraph tags**
We don't need paragraph tags (\<p\>) in our articles. Wordpress renders without them. They can cause problems, so please make sure to remove any you find.

**parentheses**
Edit out parentheses in prose whenever possible. Remember, parentheses tell the reader, “I don’t mind if you read over this.” Do you mind if they read over it? 

**playground**

**pluralization**
For acronyms such as API, no apostrophe is necessary as per AP style.

Wrong: API’s

Right: APIs

**pop-up** but **popover**

**protocols**
see _code objects_.

**quotation marks**

Periods, commas, dashes, semicolons, question marks and exclamation points go within quotation marks when they apply to the quoted matter *only*. They go outside quotation marks when they apply to the whole sentence.

**raywenderlich.com**
When referring to the website or our tutorials, refer to it as "raywenderlich.com" in all lower case. Not mixed case (RayWenderlich) or two words (Ray Wenderlich).

**real-time** when used as an adjective: "real-time analytics". **real time** when used on its own: "we're watching this in real time".

**right-click**

**screen gestures**
You _tap_ something on a screen, you don't _click_, _touch_ or _press_ it; the only exception to this is a _long press_ on an object on the phone's screen.

**server-side**

This includes the name of the Server-Side Swift pillar as well as all other uses.

**setup, set up, set-up**

"Set up" is the verb, where you _set up_ your computer.
"Setup" is the noun. The Catterwauls have quite a _setup_ in their video studio.

Take care of those first two forms properly and you’ve covered 95% of cases.

"Set-up" is a common adjectival noun: My mobile carrier has a steep _set-up_ fee. But I wouldn’t slap anyone with a trout for using the above noun form instead: a steep _setup_ fee

**TODOs** 
Not todos or to-dos. And certainly not todo's.

**up**
Don't use "up" as an adverb unless it is absolutely necessary. For example, "open up" can almost always be shortened to "open."

**URL**
Write URLs in lowercase, and leave off the leading www if possible: raywenderlich.com. You don't need to add special formatting (i.e., bold or inline code) when the website is part of the main body text.

**variables**
see _code objects_.

**webpage**
Note that this is a deviation from AP Style.

**web service**
Two words, lowercased. 

**website**

**Wi-Fi**
This is actually a trademark, though usage doesn't require additional decoration.

**× vs. x**

When you’re discussing a 10×10 array, use the typographically correct multiplication symbol **×**, as opposed to the letter **x** or, worse, **X**.

## iOS Terms and Capitalization

_Capitalize and style terms as below._

**app delegate**

**app group**

**Auto Layout**

**CocoaPod**

**Cocos2d**
Whether and how to capitalize this (_cocos2d? Cocos2D?_) has been notoriously difficult to pin down, but currently, _Cocos2d_ seems to be the most common form.

**Face ID**

**glance**
Use lowercase, including when instructing the reader to drag one into the scene.

**group**

**image view**

**In-App Purchase**
When referring to the feature or API. As a singular instance, simply in-app purchase.

**inspectors**
Capitalize when it's a button name or in a menu command. Otherwise, spell with a lowercase _i_. When referring to panes in Xcode, capitalize the name of the pane but not "inspector"; e.g., _Attributes inspector_, _File inspector_, _Size inspector_.

**Interface Builder**

**interface controller**
Use lowercase, even when referring a specific, named instance such as _the_ `GroceryList` _interface controller._

**iOS 7, iOS 8**
Not _iOS7_ or _iOS8_.

**iPhone 4s, 5s, 5c, SE, 6c, 6s, X, XR, Xs**
Not _iPhone 4S, 5S, 5C, Se, 6C, 6S, x, Xr, Xs, etc._ This is as per Apple.

**JavaScript**

**JavaScriptCore**

**key-value pair**
Not "key/value pair".

**label**
Use lowercase, including when instructing the reader to drag one into the scene.

**MacBook**

**macOS**

**minigame**

**navigators**
Capitalize when it's a button name or in a menu command. Otherwise, spell with a lowercase _n_. When referring to panes in Xcode, capitalize the name of the pane but not "navigator"; e.g., _Project navigator_, _Issue navigator_, _Test navigator_.

**Notification Center**
But a specific instance is usually termed "the user notification center" in lowercase.
When using the official term, do not include an article. "Send a notification to Notification Center." 

**Object Library**

**Objective-C**, not Objective C or Obj-C.

**OS X**
Don't use _OS X_ or _OSX_; it's now macOS.

**Podfile**

**Retina and non-Retina**

**results sidebar**
Area to the right-hand side of a playground showing the return value of a statement

**SceneKit**

**simulator**
_iOS Simulator_ is a simulator app. Generally speaking, use lowercase _simulator_ unless you omit the article:

_Correct_: run in the simulator  
_Correct_: run in iOS Simulator _(note lack of article)_  
_Incorrect_: run in the Simulator

It's OK to both use an article and capitalize _Simulator_ if you are using it as an attributive noun:

_Correct_: Close the Simulator window...

**size classes**

**SpringBoard**

**SpriteKit**

**storyboard**

**superclass**

**Swift**

**SwiftNIO**
Not "Swift NIO", "Swift-NIO" or "NIO".

**Swift standard library**
Not Swift Standard Library

**terminal**
macOS includes a terminal emulator program called _Terminal_. Generally speaking, use lowercase _terminal_ unless you omit the article:

_Correct_: Close the terminal  
_Correct_: Open a terminal window  
_Correct_: use the terminal command  
_Correct_: enter the following command into Terminal _(note lack of article)_  
_Correct_: open Terminal _(note lack of article)_  
_Incorrect_: open the Terminal

It's OK to both use an article and capitalize _Terminal_ if you are using it as an attributive noun: 

_Correct_: open a Terminal window  
_Correct_: use the Terminal command  
_Correct_: open the Terminal application

**Today**
As in Today extension, Today view, etc.

**top shelf**
No definite consensus on this one from Apple (Top Shelf is used as well); the top area of the tvOS Home Screen.

**Touch ID**

**view controller / View controller**

Use view controller when speaking of an instance in general. 

Use View control to reference the four-button unit for changing views of Finder windows. The View control comprises the Icon View button, the List View button, the Column View button and the Cover Flow button. 

**Watch app**
Not _watch app_ or _Watch App_.

**Xcode**

## Android Terms and Capitalization 

**Kotlin Standard Library** (when talking about the official library) 

**Material Design**

**Logcat**
No "the" before it.

## Unity Style and Capitalization

**animated GIFs** Use animated GIFs only once for an operation. When repeating the operation, use either a screenshot or refer the reader back to the animated GIF.

**Animator window**  
  
**animation**

**Animation view**  

**camera vs Camera** Some common terms like camera, light, collider also have components that are named the same. This can get confusing sometimes. Therefore, when referring to a **common GameObject** (e.g. the **camera**) use lowercase, when referring specifically to the attached **component** use UpperCamelCase.

**component**

**coroutine**

**Game view**  

**GameObject**

**gizmo**

**the Hierarchy**

**the Inspector**

**Material Design**

**Mecanim**  
  
**MonoBehaviour**
  
**object**

**prefab**

**project assets** 
All assets in a project should be named using UpperCamelCase.

**Project window**

**Rigidbody**

**runtime**

**scene**

**Scene view**  
  
**script**

**script vs. component** 
When talking about the actual .cs file (and the MonoBehaviour class that's inside) call it a **script**. When you're in the editor and you take that **script** and attach it to a GameObject, refer to it as a **component** ("instance" of a script).  

**Shaders**

**spoilers** 
Use spoilers to "quiz" readers on repeated operations in the article.

**sprite**

**Transform** 

**toolbar**  

**UI**

**Unity editor**

**Vector representations** 
If you describe a **Vector2**, **Vector3** or similar data, use this notation: **(X:1, Y:2, Z:3)**

## Apple Watch Style Guidelines

**complications**

**Digital Crown**
"The Digital Crown" when referring to the hardware component, but "Digital Crown" when referring to the API.

**Dock**
Also, "the Dock"
When referring more generally to a location you choose to store files, "dock" with lowercasing is appropriate. 

**Home screen**
Also "the Home screen"

**Time Travel**

**WatchKit**

## Book Chapter Style Guide

Books use a slightly different style guide than articles do. Here are points to keep in mind when editing books:

**Subheadings**

- It's especially important to have frequent subheadings in books. You don't want readers flipping through page after page of text with no subheading to mark where they area.
- Subheadings can go down to the fourth level (####) in books, if necessary.
- Subheadings that introduce a concept like, "The MVVM Pattern" don't need to be in gerund form.

**Ampersands in Titles**

In books, we prefer ampersands to spelling out "and" for titles and subheadings.
* **Correct**: Data Structures & Algorithms in Swift
* **Incorrect**: Data Structures and Algorithms in Swift

**Sentence Case for Subheadings**

We use sentence case for subheadings in books, whereas articles use Title Case. That means that only the first letter and proper nouns are capitalized in book subheadings.
* **Books**: Where to go from here?
* **Articles**: Where to Go From Here?

**Smart Quotes/Apostrophes**

Books use smart quotes and apostrophes (’), whereas articles in Wordpress need straight quotes and apostrophes ('). **Important Excpetion**: The metadata should include straight quotes and apostrophes _only_.

**Markdown**

While WordPress uses HTML to mark things like bold style, notes, bulleted lists, and so on, our books use Markdown. For example, WordPress marks subheaders using \<h2\> or \<h3\> but in Markdown, you'd use \## or \###. You can find the tags you need to use in the [Deckle-Flavored Markdown Guide](https://www.raywenderlich.com/codex-users-guide) (pw: tutteam).

**Paragraphs**

Paragraphs can be longer in books than in tutorials. However, be sure that any step-by-step instructions are broken out into lists.

**Required Sections**

The **Key points** section is always required in book chapters. The **Where to go from here?** section is only needed if the author is suggesting the reader check out a significant number of outside resources.

**Chapter References**
When referring to chapters in the same book, give the chapter number and place the chapter title in quotes: 

_Example:_ Chapter 15, “Performance Tips and Tricks”.

Refer to chapters in other books as follows:

_Example:_ Check out the “Doing Cool Stuff” chapter of _Ray’s Awesome Book_.

## Serial (Oxford) Commas

In general, digital copy looks best when the serial comma is NOT used. This is the general direction followed by several (but not all!) modern style manuals.

An example of the serial comma in use: "Ray wrote three posts, two product reviews, and a scathing exposé on Android."

The preferred practice is to remove the final comma in the list of elements (the one usually before the 'and', 'or' or 'nor' ): "Ray wrote three posts, two product reviews and a scathing exposé on Android."

However, retain the extra comma when necessary to avoid ambiguity: "Ray loves his employees, Tim Cook and Steve Ballmer." Well, we're pretty sure Tim Cook and Steve Ballmer don't work for Ray (just yet), so leave the comma in to be clear: "Ray loves his employees, Tim Cook, and Steve Ballmer."

But beware - the presence of AND following a comma does not imply a serial comma is in use: "Ray continues to throw fits when he sees a serial comma in use, and it's really nervewracking for editors to see their fearless leader in such a despondent state." Here you have two independent clauses that could be written as two separate sentences without losing meaning: "Ray continues to throw fits when he sees a serial comma in use. It's really nervewracking for editors to see their fearless leader in such a despondent state." However, the two share a common idea or thread and you can join them with a comma and a conjunction as I did above.

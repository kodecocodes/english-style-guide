# English Style Guide

This is an English style guide that we should follow to stay consistent in how we refer to common things in tutorials.

In general, we follow the [AP style guide](https://www.apstylebook.com/) and the [Apple Style Guide](https://help.apple.com/asg/mac/2013/ASG_2013.pdf). This guide has some tweaks and clarifications on top of those. The guide also covers terms used within Unity tutorials.

##iOS Terms and Capitalization

_Capitalize and style terms as below._

**app**
Use _app_ instead of _application_, unless _application_ is more clear or refers to a non-iOS entity.

**app delegate**

**app group**

**Auto Layout**

**button**
Use lowercase, including when instructing the reader to drag one into the scene.

**build and run**
Use lowercase and do not bold.

**CocoaPod**

**Cocos2d**
Whether and how to capitalize this (_cocos2d? Cocos2D?_) has been notoriously difficult to pin down, but currently, _Cocos2d_ seems to be the most common form.

**Control-click**

**Control-drag**

**document outline**
Apple tends to use the term _outline view_ in its documentation, so that is OK as well; however, use one or the other for consistency.

**double-click**

**drop-down**

**editors**
Use lowercase; e.g. _assistant editor_, _standard editor_, _scene editor_.

**frame rate**
_FPS_ not _fps_

**glance**
Use lowercase, including when instructing the reader to drag one into the scene.

**group**

**image view**

**inspectors**
Capitalize when referring to a specific inspector in Xcode; e.g., _Attributes Inspector_, _Identity Inspector_.

**Interface Builder**

**interface controller**
Use lowercase, even when referring a specific, named instance such as _the_ `GroceryList` _interface controller._

**iOS 7, iOS 8**
Not _iOS7_ or _iOS8_.

**iPhone 4s, 5s, 5c, 6c**
Not _iPhone 4S, 5S, etc._ This is as per Apple.

**keyboard keys**
Spell out and capitalize, whether alone or in multi-press combinations: _Shift-Command-Option-X_.

You _press_ keys, you don't _type_ or _hit_ them.

**label**
Use lowercase, including when instructing the reader to drag one into the scene.

**menu**

**Object Library**

**OK**
Don't use _okay_ or _Ok_.

**onscreen and off-screen**

**OS X**
Not _OSX_.

**Podfile**

**pop-up**

**project navigator**

**Retina and non-Retina**

**right-click**

**simulator**
_iOS Simulator_ is a simulator app. Generally speaking, use lowercase _simulator_ unless you omit the article:

_Correct:_ run in the simulator  
_Correct:_ run in iOS Simulator _(note lack of article)_  
_Incorrect_: run in the Simulator

It's OK to both use an article and capitalize _Simulator_ if you are using it as an attributive noun:

_Correct:_ close the Simulator window

**storyboard**

**superclass**

**terminal**
OS X includes a terminal emulator program called _Terminal_. Generally speaking, use lowercase _terminal_ unless you omit the article:

_Correct:_ close the terminal  
_Correct:_ open a terminal window  
_Correct:_ use the terminal command  
_Correct:_ enter the following command into Terminal _(note lack of article)_  
_Correct:_ open Terminal _(note lack of article)_  
_Incorrect:_ open the Terminal

It's OK to both use an article and capitalize _Terminal_ if you are using it as an attributive noun: 

_Correct:_ open a Terminal window  
_Correct:_ use the Terminal command  
_Correct:_ open the Terminal application

**view controller**

**Watch app**
Not _watch app_ or _Watch App_.

**Xcode**

## Other Style Guidelines

**Apple**
Use the pronoun *it* to refer to Apple and any other company or organization; do not use *they*.

_Example:_ Apple has its own solution...

**bolding**
Use the bold style (&lt;em&gt; in WordPress) for things the reader needs to click, enter into a text field or otherwise notice. This includes file and directory names, but only those that are the action item of a nearby instruction.

Use the bold style to highlight important concepts that are being introduced for the first time.

For bolding in lists, see **lists**.

**book references**
References to other books should be italicized: 

_Example:_ If you’re new to iOS development, we recommend you start with _iOS Apprentice_.

**chapter references**
When referring to chapters in the same book, give the chapter number and place the chapter title in quotes: 

_Example:_ Chapter 15, “Performance Tips and Tricks”

References to chapters in other books can be written as follows:

_Example:_ Check out the “Doing Cool Stuff” chapter of _Ray’s Awesome Book_.

**coordinates**
_(x, y)_ not _(x,y)_

Note that _coordinate_ refers to one of the group (_the x-coordinate_), while _coordinates_ refers to more than one and usually the entire group (_the GPS coordinates of Cupertino_).

**emoticons**
These are not punctuation; sentences that end with an emoticon still need appropriate punctuation that should fall before the emoticon rather than after it.

**file extensions**
either _XXX_ or _.xxx_

**game references**
Italicize the names of published games, like _Super Mario Bros._ or _Angry Birds_, but not the names of other software.

**headers**

* _Casing in tutorials:_ Capitalize headers, leaving any article, preposition or coordinating conjunction that is three letters or less lowercase, unless it is the first word in the heading. For example, it is important to capitalize the verb _Go_ but _not_ the word _to_ in **Where to Go From Here?**</li>

* _Casing in books:_ Use sentence casing by capitalizing only the first letter of the first word, except for proper nouns.</li>

* _Placement:_ Insert when the subject moves from one point to another; more is usually better than less. Also ensure that if H2 and H3 headers are used they are nested appropriately. For example, there is no point in having a single H2 and then seventeen H3 headings for the rest of the article.</li>

**inline code**
Use the inline code style (&lt;code&gt; in WordPress) for all class, function and method names. Remember to use it for these words:

`nil`  
`if` statement  
`while` loop  
`if-else`  
`Int`  
`enum`  
`switch` statement

**lists**
List items should be followed by colons, not dashes.

If a list includes items, bold them (&lt;em&gt; in WordPress). If the list items are code structures, use the bold style rather than the inline code style.

**numbers vs. numerals**
Spell out whole numbers up to and including nine, as well as larger numbers that can be expressed in one or two words.

_Examples:_ zero, one, nine, six million.

Use numerals for numbers greater than nine; for decimals and percentages; for numbers that express mathematical figures; for addresses, dates, the time of day, and page or chapter numbers; and when a numeral is important for identification purposes.

_Examples:_ 10; 25,000; 30%; divide 15 by 3; Chapter 6; Highway 4; Room 2.

Numbers in series should be consistent.

_Example:_ She went to five countries on four continents in sixteen days _OR_ She went to 5 countries on 4 continents in 16 days.  
_Example:_ The final score was 13-1 _OR_ The final score was thirteen to one.

_Note:_ There are a lot of exceptions to these basic rules, so use your best judgment.

**quotation marks**
Punctuation not essential to a quote should be placed outside of the quotes (British style) so as to avoid any possible confusion about whether a punctuation mark is part of a string or any other bit of code.

**screen gestures**
You _tap_ something on a screen, you don't _click_, _touch_ or _press_ it; the only exception to this is a _long press_ on an object on the phone's screen.

## Unity Terms and Capitalization

_Capitalize and style terms as below._

Animator

Animation View

Component

Coroutine

Game View

GameObject

Hierarchy

Inspector

Mecanim

Prefab

Project Browser

Scene

Scene View

Transform

UI 

Unity Editor

## Other Unity Style Guidelines

**animated GIFs** Use animated GIFs only once for an operation. When repeating the operation, use either a screenshot or refer the reader back to the animated GIF.

**bolding** Often times when writing Unity tutorials, bolding is a multi-step process when making adjustments. Bold each object in the process:

_Example:_ In the **Hierarchy**, select the **SpaceShip** and from the **Inspector**, and inside the **Alien Component**, set the **IsDead** property to **false**.  

**project assets** All assets in a project should be named using UpperCamelCase.

**spoilers** Use spoilers to "quiz" readers on repeated operations in the tutorial.


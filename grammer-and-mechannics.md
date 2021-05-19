 # <div align='center'> Grammar and Mechanics

To keep our content consistent we adhere to the following grammar rules and mechanics. This guide will define our style for how we write technical documentation.

[Links](#links)
<br/>
[Click vs Select](#click-vs-select)
<br/>
[Italics](#italics)
<br/>
[Capitlization](#capitalization)
<br/>
[Code in Text](#code-in-text)
<br/>
[Contractions](#contractions)
<br/>
[Dates](#dates)
<br/>
[Hyphens](#hyphens)
<br/>
[Numbers](#numbers)
<br/>
[Emojis](#emojis)
<br/>
[Writing About Revenuecat](#writing-about-revenuecat)
</br>

## Links

Write links that are descriptive and have meaning. Link descriptions should have words describing where they go and what content is there. It is best to use keywords from the linked page. Using descriptive links allows the reader to scan pages and assists with screen reading technologies. 

<pre>
❌  You will find more documentation <a href="url">here</a>.
</pre>
<pre>
✅  For additional information, review the <a href="url">Configuring Products</a> guide. 
</pre>
<br/>

## Click vs. Select

We use the word **select** instead of **click** when addressing our readers. This action is used agnostically across devices. 

<br/>

## Italics

In general, we don’t *italicize*; instead, we **bold** words. Readers can quickly scan our documentation.

<br/>

## Capitalization

We use a couple of different capitalizations: title case and sentence case. 


### Headers/Titles - Title Case
Title case is when the first letter of every word except articles, prepositions, and conjunctions is capitlized.  

When writing titles and headers we follow title case guidelines. 
<pre>
❌  Create an In-app purchase
 </pre>
<pre>
✅  Create an In-App Purchase
</pre>



### Other Content - Sentence Case 
Sentence case is when the first letter in the first word and proper nouns in a phrase is capitalized.


We write all other content (except tiles and headers) in sentence case. 
<pre>
✅  Capitalize the name of RevenueCat terms such as the Purchases SDK or Offerings. 
</pre>
<pre>
❌  We don’t capitalize words such as email, internet, etc. 
</pre>

### Referencing Other Companies
Honor’s the companies own names for themselves. Go by the official website.
<pre>
✅  In the Google Play Console.
</pre>

<br/>

## Code in Text

When writing code in the documentation it’s best to separate it from regular text.

### Large Code Blocks

For longer blocks of code, use a code snippet block to keep all of the code contained and formatted

````Swift
✅  Purchases.shared.offerings { (offerings, error) in
    if let packages = offerings?.current?.availablePackages {
        // Display packages for sale
    }
}
````

### Small Code References 

For small code references, such as an SDK method or parameter from a webhook event, always contain it in backticks

> ✅   The `getOfferings` method will fetch the Offerings from RevenueCat


> ❌  The getOfferings() method will fetch the Offerings from RevenueCat


<br/>

## Contractions

We like to keep our tone conversational so we use contractions regularly. 

<br/>

## Dates

Spell out months and days of the week in either long or short form. 

### Short form:  Abbreviate to 3 letters, no period 
<pre>
✅  Mon, Tue, Wed - Jan, Feb, Mar
</pre>
### Long-form: Spell out whenever other words frame the day or month
<pre>
✅  Saturday, August 18
</pre>

<br/>

## Exclamation Points

We love sharing our enthusiasm with an exclamation point! They can help keep communication light. Use them when needed. 

<br/>

## Hyphens 

### Email vs E-mail

We reference email without the hyphen.


### Sign -in/up vs Sign in/up 

When it is used as a verb, it’s two words 
<pre>
✅  Please sign in to your account
</pre>

When used as an adjective, it’s hyphenated. 
<pre>
✅  The sign-up page crashed
</pre>

### Login vs  Log in vs Log-in

When used as an adjective or noun, it’s one word or hyphenated.
<pre>
✅  Enter your login (log-in) information
</pre>

When it is used as a verb, it’s two words  
<pre>
✅  Log in with your account
</pre>

<br/>

## Numbers 

When referring to numbers it’s best to use digits instead of spelling the word out in most cases. It helps draw the eye of the reader to the critical content. 
<pre>
✅  The Apple subscription terms require users to cancel subscriptions at least 24 hours before the next renewal.
</pre>
When the number doesn’t represent a fact, but generalization spell out the word
<pre>
✅  We have thousands of developers using RevenueCat.
</pre>

<br/>

## Emojis

Emojis are a fun way to add humor and visual interest to your writing but use them infrequently and deliberately.

<br/>

## Active Voice
Use active voice, not passive voice

Active voice is when the subject of a sentence performs the verb’s action. Passive voice is when the verb acts on the subject. 
<div>
<pre>
 ✅  The PurchaserInfo object contains all of the purchase and subscription data available about the user.
 </pre>
<pre>
❌   All subscription and purchase data can be found in the PurchaserInfo object. 
</pre>
 </div>

<br/>

## Writing About RevenueCat 

When we refer to ourselves we always capitalize the ‘R’ and ‘C’ and use ‘we’ not ‘it’.










# Testing features

## A collapsible section with markdown
<details>
  <summary markdown="block">Click to expand!</summary>
  
  ### Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>

Reminder: Both the <summary> and </details> tags need a blank line afterward, or Github may not cooperate.

## External Links

External link that opens in same tab, nie dobje: [a test link](https://hebrewlion.com)

External link that opens in a new tab: <a href="http://hebrewlion.com" target="_blank">this is descriptive text</a>

## Images

This first cat has alt text and title, but cannot be resized
![Alt text describing image](https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png "How do you like this image? This is additional info, beyond alt text")

Now, this is the same cat resized, but using different code. I am not sure it be alt texted, etc.
<img src="https://1000logos.net/wp-content/uploads/2021/05/GitHub-logo.png" width="100">

Further info and options at [a https://www.xaprb.com/blog/how-to-style-images-with-markdown/](https://www.xaprb.com/blog/how-to-style-images-with-markdown/)

---------------

## Reusables

Reusables are long strings of reusable text that can be referenced in multiple content files. Each reusable lives in its own Markdown file. The path and filename of each Markdown file determines what its path will be in the data object.

Now, let's prove it. Here's the code for a reusable: {% assets/reusable-lion.md %}





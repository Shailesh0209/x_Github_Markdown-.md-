# x_Github_Markdown-.md-
Basic writing and formatting syntax

# Styling tet
All bold and italic: ***All this text is important***

# Quoting text
Text that is not a quote: > Text that is not a quote

# Quoting code
`rrrrr`
some basic commands are:
```
git status 
git add
git commit
```

# Links 
This site was built using [GitHub Pages](https://pages.github.com/).

# Relative links
You can define relative links and image paths in your rendered files to help readers navigate to other files in your repository.

A relative link is a link that is relative to the current file. For example, if you have a README file in root of your repository, and you have another file in docs/CONTRIBUTING.md, the relative link to CONTRIBUTING.md in your README might look like this:

[Contribution guidelines for this project](docs/CONTRIBUTING.md)

# Images

You can display an image by adding ! and wrapping the alt text in [ ]. Then wrap the link for the image in parentheses ().

![This is an image](https://myoctocat.com/assets/images/base-octocat.svg)

Here are some examples for using relative links to display an image.

Context	Relative Link
In a .md file on the same branch	/assets/images/electrocat.png
In a .md file on another branch	/../main/assets/images/electrocat.png
In issues, pull requests and comments of the repository	../blob/main/assets/images/electrocat.png
In a .md file in another repository	/../../../../github/docs/blob/main/assets/images/electrocat.png
In issues, pull requests and comments of another repository	../../../github/docs/blob/main/assets/images/electrocat.png?raw=true



Context	URL
Dark Theme	![GitHub Light](https://github.com/github-light.png#gh-dark-mode-only)
Light Theme	![GitHub Dark](https://github.com/github-dark.png#gh-light-mode-only)


# Lists
You can make an unordered list by preceding one or more lines of text with - or *.

- George Washington
- John Adams
- Thomas Jefferson

To order your list, precede each line with a number.

1. James Madison
2. James Monroe
3. John Quincy Adams

# Nested Lists
1. First list item
   - First nested list item
     - Second nested list item

# Task lists
- [x] #739
- [ ] https://github.com/octo-org/octo-repo/issues/740
- [ ] Add delight to the experience when all tasks are complete :tada:

# Mentioning people and teams
@github/support What do you think about these updates?

# Referencing issues and pull requests
You can bring up a list of suggested issues and pull requests within the repository by typing #. Type the issue or pull request number or title to filter the list, and then press either tab or enter to complete the highlighted result.

For more information, see "Autolinked references and URLs."

# Referencing external resources
If custom autolink references are configured for a repository, then references to external resources, like a JIRA issue or Zendesk ticket, convert into shortened links. To know which autolinks are available in your repository, contact someone with admin permissions to the repository. For more information, see "Configuring autolinks to reference external resources."

# Using emoji
@octocat :+1: This PR looks great - it's ready to merge! :shipit:

[Paragraph](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#paragraphs)

# Footnotes
Here is a simple footnote[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: My reference.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.

# Hiding content with comments
<!-- This content will not appear in the rendered Markdown -->

# Ignoring Markdown formatting
You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.

Let's rename \*our-new-project\* to \*our-old-project\*.

# Disabling Markdown rendering: [Disabling Markdown rendering](You can tell GitHub to ignore (or escape) Markdown formatting by using \ before the Markdown character.)

Let's rename \*our-new-project\* to \*our-old-project\*.)


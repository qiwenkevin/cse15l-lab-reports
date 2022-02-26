# Lab Report 4

Here are the repositories used in this lab:
[My Group's Repo](https://github.com/JaredJose/markdown-parse)
[Reviewed Group's Repo](https://github.com/christopherthomason/markdown-parse)

## Snippet 1

```text
`[a link`](url.com)

[another link](`google.com)`

[`cod[e`](google.com)

[`code]`](ucsd.edu)
```

![link1](images/snip1link1.png)
![link2](images/snip1link2.png)
![link3](images/snip1link3.png)

We can see from the above that the three bottom links should be recognized as normal links, because they are underlined when moused over.

![test1](images/testsnip1.png)

Here is the implementation for testing the first snippet, after adding in snippet 1 as a markdown file.

### My Group implementation results

![our](images/result-our-1.png)

### Reviewed Group implementation results

![other](images/result-other-1.png)

---

## Snippet 2

```text
[a [nested link](a.com)](b.com)

[a nested parenthesized url](a.com(()))

[some escaped \[ brackets \]](example.com)
```

![link1](images/snip2link1.png)
![link2](images/snip2link2.png)
![link3](images/snip2link3.png)

We can see from the above that all three links should be recognized as normal links, because they are underlined when moused over.

![test2](images/testsnip2.png)

Here is the implementation for testing the second snippet, after adding in snippet 2 as a markdown file.

### My Group implementation results

![our](images/result-our-2.png)

### Reviewed Group implementation results

![other](images/result-other-2.png)

---

## Snippet 3

```text
[this title text is really long and takes up more than 
one line

and has some line breaks](
    https://www.twitter.com
)

[this title text is really long and takes up more than 
one line](
    https://ucsd-cse15l-w22.github.io/
)


[this link doesn't have a closing parenthesis](github.com

And there's still some more text after that.

[this link doesn't have a closing parenthesis for a while](https://cse.ucsd.edu/



)

And then there's more text
```

![link1](images/snip3link1.png)

We can see from the above that only one link should be recognized as normal links, because it's the only one underlined when moused over.

![test3](images/testsnip3.png)

Here is the implementation for testing the third snippet, after adding in snippet 3 as a markdown file.

### My Group implementation results

![our](images/result-our-3.png)

### Reviewed Group implementation results

![other](images/result-other-3.png)

---

## Questions

- Do you think there is a small (<10 lines) code change that will make your program work for snippet 1 and all related cases that use inline code with backticks? If yes, describe the code change. If not, describe why it would be a more involved change.
  - For snippet one, we did not really account for the effect of backticks in 
- Do you think there is a small (<10 lines) code change that will make your program work for snippet 2 and all related cases that nest parentheses, brackets, and escaped brackets? If yes, describe the code change. If not, describe why it would be a more involved change.
- Do you think there is a small (<10 lines) code change that will make your program work for snippet 3 and all related cases that have newlines in brackets and parentheses? If yes, describe the code change. If not, describe why it would be a more involved change.

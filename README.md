# The Pretty Nice Semantic Commit Messages Style Guide

Inspired by https://seesparkbox.com/foundry/semantic_commit_messages here's a style guide for your git log. A good software project has style, so why not extend this to git logs as well? 

In this style guide the commit message always starts with a **type** that is **four characters long** followed by a colon and a space. Then an **action verb** is inserted followed by the rest of the message. Togeather the verb + rest constitutes the summary. Max length for the summary is **60 characters**. This ensures that the commit message will look nice on github as well. Further explanations and info about the commit can be entered on new lines.

### Structure of the message

```
feat: add email send functionality for admin 
^--^  ^------------^
|     |
|     +-> Summary in present tense (verb + rest) - max length 60 chars.
|
+-------> Type: docs, feat, bfix, rfac, dvop, deps, test, deps, styl, misc
```

### Examples usage
```
docs: explain how to setup dev env (explain|update|add|remove|rewrite|fix project documentation)
feat: add email send functionality for admin (add a feature to the program)
bfix: fix nullpointer exception in FooService (fix|workaround|resolve|improve a bug or issue with the program)
rfac: rewrite email sending to non-blocking (share|rewrite|improve some code, wow it's a lot smoother now)
dvop: add travis & beanstalk ci/cd pipeline (add|update something to do with your ci/cd pipeline)
deps: update to play 2.5.18 (update|add a project dependancy/libarary)
test: add it-tests for login flow (ensure|add|rewrite| a test or improve the test infrastructure)
styl: convert tabs to spaces (you added/updated some styling related stuff)
misc: other random stuff here that doesn't fit anywhere else
```

### That's all folks
Include a link to these guidelines in your project and then enforce the style guide rules. You're git log will be cool and clean!

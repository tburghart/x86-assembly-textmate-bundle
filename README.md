## TextMate x86 Assembly Language Bundle

This is a [TextMate][1]/Sublime&ast; bundle providing language support for
16/32/64 bit x86 Assembly Language sources in Intel and AT&amp;T formats.

_&ast; Sublime is untested, but the original before I started mucking about in
it claimed support, and my changes **shouldn't** have changed that.
As always, YMMV._

### History

I forked this repo because I wanted to separate AT&amp;T and Intel assembler
dialects - I use both, and there are enough differences that trying to handle
them both with a single syntax description didn't seem worth the effort. By
separating them, it'll be easier to enhance them properly, rather than living
with the lowest common denominator and having even that be far less than
accurate.

You can follow the forks back through GitHub if you want all the gory details,
but basically I used [Andrew Fox's][3] version as the basis for my AT&amp;T
syntax and [Ryan Hileman's][4] version as the basis for my Intel syntax, the
latter also based on the former.

### License

All of this stuff has at its roots in some tangentially related PLC assembler
handling bundles by [Andy Morrow][2] that had no associated license statements,
meaning they're subject to default copyright protections broadened by implicit
acceptance of GitHub's [Terms of Service][5].

Some intermediate revisions are explicitly in the public domain, and others are
also subject to default copyright rules. Because I prefer explicitly permissive
licenses I've elected to place what I hope is an appropriate [license](LICENSE)
on the work, and if any of the prior contributors object they should get in
touch with me and we'll work out something satisfactory.


  [1]: http://macromates.com/
  [2]: https://github.com/amorrow/pic-assembly-textmate-bundle
  [3]: https://github.com/foxostro/x86-assembly-textmate-bundle
  [4]: https://github.com/lunixbochs/x86-assembly-textmate-bundle
  [5]: https://help.github.com/articles/github-terms-of-service/#f-copyright-and-content-ownership

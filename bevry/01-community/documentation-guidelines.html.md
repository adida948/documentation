All pull requests must conform to the following criteria in order to get merged in:

- ### GitHub Flavoured Markdown
	We use [GitHub Flavoured Markdown](http://github.github.com/github-flavored-markdown/) for all our documents. This can be seen by the usage of the `.md` extension on our files.

- ### Single paragraph pull requests only
	Each pull request should only alter one paragrah each, pull requests that alter more than one paragraph at a time will likely need to be redone. This is because monolithic/bundled pull requests are impossible to merge in due to the extreme level of overhead they cause by conflicting +1s and -1s in the same pull request, getting out of date with other changes quicker, getting in conflict with other merged in changes quicker.

- ### International/British English for Text, USA/American English for Code
	We love it when people fix spelling errors and typos! We use International/British English for text (only 27% of our visitors are from the USA), and USA/American English for code (this is more a technical constraint). Code examples should (where it makes sense to) comply with the [Bevry Coding Standards](https://github.com/bevry/community/wiki/Coding-Standards).

- ### Explain changes
	Fixing grammar as well any other sentence restructuring will require a description along with the pull request on why this change is better than the original. It turns out that such changes are largely subjective, and that the original may be that way for sound reasons.

- ### No external documentation supplements yet
	We are not yet ready to add resources to community documentation and videos yet. We need to figure out the best way to present the data while avoiding common pitfalls like out of sync or conflicting documentation.

- ### Use the "Files Changed" tab to comment on pull requests
	When commenting on pull request changes, instead of commenting on individual commits, instead used the pull request's "Files Changed" tab. This allows your comments to persist as the pull request developers, rather than be forgotten when the next commit comes in.

[Discussion about this criteria here.](https://github.com/docpad/documentation/issues/63)
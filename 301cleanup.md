# 301 cleanup

- Facilitator's Guide
  - Move RWD to class 01 & Push current jQuery days to class 02-03


- all starter code
  - after hackerIpsum: rm `blogArticles.js`
  - after HBS: rm articleView.popfilters `if ($(this).hasClass(template))`
  - server: rm IIFE from GHProxy
  - remove ref to /brookr/ from starter code

- class 01
  - double-check GH link to .eslintrc file for lab01 readme
  - replace index.html with [this](https://github.com/codefellows-seattle-301d7/01-mobile-first/blob/master/starter-code/index.html)
  - create TODO for articleView.toggleNavDisplay
    - no such thing as :hover on mobile!
    - how to do this?? relies on a JQ event but we don't cover that until class03. could write vanilla event handler & refactor in lab03

```articleView.toggleNavDisplay = function() {
  document.querySelector('.icon-menu')
    .addEventListener('click', function() {
      var navMenu = document.querySelector('nav').children[1];
      navMenu.classList.toggle('hidden');
    });
};
```

- class 02
  DONE: pair lab readme: simplify forking/cloning instructions
  DONE: remove articleView.js except articleView.toggleNavDisplay
  DONE: pass linter
  DONE: strict mode
  DONE: delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  DONE: var ourLocalData -> rawData

- class 03
  DONE: pass linter
  DONE: strict mode
  DONE: delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  DONE: var ourLocalData -> rawData
  DONE: correct typo 'intrests' in index.html

- class 04
  DONE: pass linter
  DONE: strict mode
  DONE: correct typo 'intrests' in index.html

- class 05
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

- class 06
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

- class 07
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

- class 08
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html
  - Review SQL / WebDB
  - Can we migrate this to a server-side SQL intro, still introducing SQL as a language
    - Requires installation of SQL on all possible OS versions, can we get this simplified for any user?

- class 09
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html
  - Continue Joins and Relations as a secondary topic to SQL
  - Introduce Sequelize.io as an ORM - refactor SQL commands to JS-like code
    - OR Continue with stand-alone assignment for zip-codes, and implement the use of joins & Relations

- class 10
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

- class 11
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html
  - Remove Express-request-proxy from server.js

- class 12
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html
  - Update github API URL to point to Authentication-required endpoint rather than open/generic endpoint

- class 13
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

- class 14
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

- class 15
  - pass linter
  - strict mode
  - delete nav:hover rule from modules.css (articleView.toggleNavDisplay should do it)
  - correct typo 'intrests' in index.html

##  Branches and workflows
(This document optimized for [reveal-md](https://github.com/webpro/reveal-md))

---

### Agenda
1. Client Tools
1. Conventions and tips
1. Collaboration Practice



---

### Client Tools

* vscode & the comparing changes

* git lens

* git graph

* Additional clients: [gitkraken](https://www.gitkraken.com/git-client/features), [sourcetree](https://www.sourcetreeapp.com/)

---

### Conventions and tips

Github Organizations vs Private repos

An organizations can have multiple "Organization" entities
<!-- .element: class="fragment" -->

Organizations can be used to group together a related repos 
<!-- .element: class="fragment" -->

---

### Conventions and tips

Branch names

* Keep it clear and simple
* May [contain issue name and type](https://github.com/hasadna/anyway-newsflash-infographics#branch-naming), like:

```
bugfix-123-solve-crash-on-startup
```

---

### Conventions and tips

Small steps are best

* Keep your commit small (why?)
* Keep your PR small (why?)
* A word about [conflicts](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/addressing-merge-conflicts/resolving-a-merge-conflict-using-the-command-line)
```
If you have questions, please
<<<<<<< HEAD
open an issue
=======
ask your question in IRC.
>>>>>>> branch-a
```
<!-- .element: class="fragment" -->

---

### Conventions and tips

Commit messages

* It is important to have a clear and specific commit message - no something like "bug fix" or "add button"
<!-- .element: class="fragment" -->

* Good message description would be useful for debugging
<!-- .element: class="fragment" -->

* You may add a convention you like from an  [opensource project](https://gist.github.com/brianclements/841ea7bffdb01346392c)
<!-- .element: class="fragment" -->

---

### Conventions and tips

Protecting branches

Keep your main branches [protected](https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/managing-a-branch-protection-rule) (e.i. prevent direct push)

Demo
<!-- .element: class="fragment" -->

---

### Conventions and tips

PR description

Like with commit messages, there is no common practice here, but description should be useful:
<!-- .element: class="fragment" -->

* For code review (contain link to issue, important background etc.)
<!-- .element: class="fragment" -->

* For retrospective
<!-- .element: class="fragment" -->

---

### Conventions and tips

Code Review

[Demo](https://github.com/hasadna/anyway-newsflash-infographics/pulls)

---

### Conventions and tips

Commands & Tips which saves the day

* `git status` - whenever something is wrong and you're not sure what
* `git help` - whenever you forget command options
* [Git SCM](https://git-scm.com/) - a great source for understanding git
* [Atlassian Git tutorials](https://www.atlassian.com/git/tutorials) are great for learning / refresh

---

### Collaboration Practice

1. open a collaboration-practice repo
2. add index.html
3. protect "main" branch
4. set your name by location and open a PR
5. Bonus: change the image (A) in a separate next PR, or 
5. (B) push another commit to the same branch
## Advanced git

(This document optimized for [reveal-md](https://github.com/webpro/reveal-md))

---

### Agenda

1. Git hooks
2. CI and CD 
3. Advanced commands

---

### [Git hooks](https://www.atlassian.com/git/tutorials/git-hooks)
Git hooks are scripts that run automatically every time a particular event occurs in a Git repository

* Can be used by [manual install](https://www.atlassian.com/git/tutorials/git-hooks) (do it carefully!)
<!-- .element: class="fragment" -->

* Can be used by package.json (for node projects) / plugins 
<!-- .element: class="fragment" -->

---

### [Git hooks](https://www.atlassian.com/git/tutorials/git-hooks)
Common hooks
* pre-commit
* prepare-commit-msg
* post-commit
* post-checkout

---

### [Git hooks](https://www.atlassian.com/git/tutorials/git-hooks)
Demo - add [pre-commit lint rule](https://codeburst.io/continuous-integration-lint-staged-husky-pre-commit-hook-test-setup-47f8172924fc)
1. start a node package - `npm init`
1. `npm install eslint`
1. `npm init @eslint/config`
1. install [husky](https://github.com/typicode/husky) and set lint as pre-commit
1. create a script which will not pass linter
1. Try to commit

---

### CI and CD

Methodologies aim to automate common tasks

* Continuous Integration (CI): Automated process which integrate code on each change
<!-- .element: class="fragment" -->

* Continuous Delivery (CD): The Capability to deploy an Environment at any given time
<!-- .element: class="fragment" -->

* Continuous Deployment (CD): Automated process which deploy on each code change
<!-- .element: class="fragment" -->

---
### CI and CD

Github actions -easy way to automate workflows (CI/CD)

What's the big deal? (A bit history)
<!-- .element: class="fragment" -->

[How it's looks like?](https://github.com/hasadna/anyway-newsflash-infographics/actions)
<!-- .element: class="fragment" -->

---

### CI and CD
Hello CI

[Setting up CI/CD with Github Actions](https://learn.vonage.com/blog/2021/02/17/setting-up-ci-cd-with-github-actions)

Demo
1. create a repo
2. Go to github actions tab, select a workflow (node) 
3. Set workflow to trigger `npm run lint`
4. Test it with a bad PR

---
### CI and CD
Hello CD - Review [Anyway Project CD](https://github.com/hasadna/anyway-newsflash-infographics)

---

### Advanced Concepts & More commands
1. [merge and fast forward](https://www.tutorialspoint.com/what-is-a-fast-forward-merge-in-git)
1. squash
1. [rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)
1. force push
1. [git reset options (soft, hard, mixed)](https://www.atlassian.com/git/tutorials/undoing-changes/git-reset)
1. cherry-picking
1. diff

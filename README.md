# CSP Badge ![CSP strict](./strict.svg) ![CSP friendly](./friendly.svg) ![CSP hostile](./hostile.svg)

![Security Matters](./security-matters.jpg)

<sup>**Social Media Photo by [Franck](https://unsplash.com/@franckinjapan) on [Unsplash](https://unsplash.com/)**</sup>

---

This repository exists only to allow other repositories to add a *badge* about the [CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) state of the module, library, or helper.

The offered *SVG* images are the following:

  * ![CSP strict](./strict.svg) suitable for projects that *don't* use `eval` or `Function` or scripts served as `Blob`, hence don't ever need any particular *CSP* rule
  * ![CSP friendly](./friendly.svg) suitable for projects that *might need* particular *CSP* rules to fully work as expected
  * ![CSP hostile](./hostile.svg) for all projects humble enough to declare such project is *everything but secure*, and inform users about the risk they might have if such project is used in production

---


## ![CSP strict](./strict.svg) CSP strict

The project does *not* need any specific [CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) configuration because it does *not* include, use, or inject, any *Function*, *eval*, or other workarounds to evaluate anything at all, hence the security is granted to be the best possible.

---


## ![CSP friendly](./friendly.svg) CSP friendly

The project *might* need some specific [CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) configuration, because it could need to use *Function*, *eval*, or any other workaround to evaluate code at runtime, hence security needs to be considered, and best practices followed.

---


## ![CSP hostile](./hostile.svg) CSP hostile

The project shamelessly needs, use, or pollute the running software, with *Function*, *eval*, or any other workaround to evaluate code at runtime, so that even [CSP](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) might not be enough to grant a secure execution of the program.

---


### How to include

If your project would like to inform its users about its *CSP* compliancy, you can add one of these badges on top of your *GitHub*, *GitLab*, or any other service, so that it'll be instantly visible:

**Markdown** - Basic
```md
![CSP strict](https://webreflection.github.io/csp/strict.svg)
![CSP friendly](https://webreflection.github.io/csp/friendly.svg)
![CSP hostile](https://webreflection.github.io/csp/hostile.svg)
```

**Markdown** - Informative
```md
[![CSP strict](https://webreflection.github.io/csp/strict.svg)](https://webreflection.github.io/csp/#-csp-strict)
[![CSP friendly](https://webreflection.github.io/csp/friendly.svg)](https://webreflection.github.io/csp/#-csp-friendly)
[![CSP hostile](https://webreflection.github.io/csp/hostile.svg)](https://webreflection.github.io/csp/#-csp-hostile)
```

**HTML** - Basic
```html
<img alt="CSP strict" src="https://webreflection.github.io/csp/strict.svg">
<img alt="CSP friendly" src="https://webreflection.github.io/csp/friendly.svg">
<img alt="CSP hostile" src="https://webreflection.github.io/csp/hostile.svg">
```

**HTML** - Informative
```html
<a href="https://webreflection.github.io/csp/#-csp-strict">
  <img alt="CSP strict" src="https://webreflection.github.io/csp/strict.svg">
</a>
<a href="https://webreflection.github.io/csp/#-csp-friendly">
  <img alt="CSP friendly" src="https://webreflection.github.io/csp/friendly.svg">
</a>
<a href="https://webreflection.github.io/csp/#-csp-hostile">
  <img alt="CSP hostile" src="https://webreflection.github.io/csp/hostile.svg">
</a>
```

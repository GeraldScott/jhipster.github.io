---
layout: default
title: Release 2.27.0
---

JHipster release 2.27.0
==================

*JHipster gives you Spring Boot + AngularJS working together in one handy Yeoman generator.*

What's new
----------

This new version comes with 116 bug fixes and PRs!

- We have completely refactored our code base, in order to follow the new Yeoman best practices and structure. This means our code is cleaner, and in the long run everybody should benefit from it. This was a huge work!
- The UI to manage entities has been improved.
- The Docker files have moved under `src/main/docker` - see [#2600](https://github.com/jhipster/generator-jhipster/issues/2600)
- The Openshift sub-generator has been removed, as it has been broken for a long time - see [#1896](https://github.com/jhipster/generator-jhipster/issues/1896).
- And we have merged several small bug fixes, which you can list [using the 2.27.0 milestone with the `bug` label](https://github.com/jhipster/generator-jhipster/issues?utf8=%E2%9C%93&q=is%3Aissue+milestone%3A2.27.0+is%3Aclosed+label%3Abug).

Closed tickets
------------

As always, __[you can check all the closed tickets here](https://github.com/jhipster/generator-jhipster/issues?q=milestone%3A2.27.0+is%3Aclosed)__.

How to upgrade
------------

Update your version of JHipster with:

```
npm update -g generator-jhipster
```

And then you can update your project when you run again

```
yo jhipster
```

You can also update your entities by running again the entity sub-generator, for example if your entity is named _Foo_

```
yo jhipster:entity Foo
```

Help and bugs
--------------

If you find any issue with this release, don't hesitate to:

- Contact [@java_hipster](https://twitter.com/java_hipster) on Twitter
- Add a bug on our [bug tracker](https://github.com/jhipster/generator-jhipster/issues?state=open)
- Post a question on [Stack Overflow](http://stackoverflow.com/tags/jhipster/info)
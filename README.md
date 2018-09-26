📦 setup.py (for humans)
=======================

This repo exists to provide [an example setup.py] file, that can be used
to bootstrap your next Python project. It includes some advanced
patterns and best practices for `setup.py`, as well as some
commented–out nice–to–haves.

For example, this `setup.py` provides a `$ python setup.py upload`
command, which creates a *universal wheel* (and *sdist*) and uploads
your package to [PyPi] using [Twine], without the need for an annoying
`setup.cfg` file. It also creates/uploads a new git tag, automatically.

In short, `setup.py` files can be daunting to approach, when first
starting out — even Guido has been heard saying, "everyone cargo cults
thems". It's true — so, I want this repo to be the best place to
copy–paste from :)

**If you're interested in financially supporting Kenneth Reitz open source, consider [visiting this link](https://cash.me/$KennethReitz). Your support helps tremendously with sustainability of motivation, as Open Source is no longer part of my day job.**

[Check out the example!][an example setup.py]

![image]

To Do
-----

-   Tests via `$ setup.py test` (if it's concise).

Pull requests are encouraged!

More Resources
--------------

-   [What is setup.py?] on Stack Overflow
-   [The Hitchhiker's Guide to Packaging]
-   [Cookiecutter template for a Python package]

License
-------

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any means.

✨🍰✨

  [an example setup.py]: https://github.com/kennethreitz/setup.py/blob/master/setup.py
  [PyPi]: https://docs.python.org/3/distutils/packageindex.html
  [Twine]: https://pypi.python.org/pypi/twine
  [image]: https://farm1.staticflickr.com/628/33173824932_58add34581_k_d.jpg
  [What is setup.py?]: https://stackoverflow.com/questions/1471994/what-is-setup-py
  [The Hitchhiker's Guide to Packaging]: https://the-hitchhikers-guide-to-packaging.readthedocs.io/en/latest/creation.html
  [Cookiecutter template for a Python package]: https://github.com/audreyr/cookiecutter-pypackage




    所有项目都应该包含一个涵盖项目目标的自述文件。最常见的格式是带有“rst”扩展名的reStructuredText，虽然这不是要求;Markdown的多种变体也被支持（查看setup（）的long_description_content_type参数）

    有关示例，请参阅PyPA示例项目中的README.md

注意使用setuptools的项目默认情况下包含在源代码分发中的README.rst（自0.6.27开始）。
内置的distutils库在Python 3.7中开始采用这种行为。
如果您使用setuptools，则不需要在MANIFEST.in中列出README.rst。
否则，包括它是明确的。

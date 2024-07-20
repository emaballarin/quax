# Contributing

Contributions (pull requests) are very welcome! Here's how to get started.

---

**Getting started**

First fork the library on GitHub.

Then clone and install the library in development mode:

```bash
git clone https://github.com/your-username-here/quax.git
cd quax
pip install -e .
```

Then install the pre-commit hooks:

```bash
pip install pre-commit
pre-commit install
```

These hooks use ruff to format and lint the code, and pyright to typecheck it.

---

**If you're making changes to the code:**

Now make your changes. Make sure to include additional tests if necessary.

Next verify the tests all pass:

```bash
pip install pytest
pytest
```

Then push your changes back to your fork of the repository:

```bash
git push
```

Finally, open a pull request on GitHub!

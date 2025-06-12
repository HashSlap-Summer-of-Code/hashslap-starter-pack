# 🧑‍💻 Contributing to HashSlap Summer of Code

Welcome to the HashSlap Summer of Code! 🎉 We’re thrilled to have you contribute to our open-source projects. This guide explains how to get started, submit contributions, and follow best practices to ensure a smooth experience for everyone.

## 📄 Reading Key Files

Every project in the HashSlap ecosystem has important files to guide you:

- **`README.md`**: Contains the project overview, setup instructions, and usage details. Always start here to understand the project.
- **`CONTRIBUTING.md`**: You’re reading it! This file outlines how to contribute to the project.
- **`LICENSE`**: Specifies the legal terms for using and contributing to the code (e.g., MIT License). Check it to understand your rights and responsibilities.

**Tip**: If a project lacks clear documentation, consider submitting a pull request (PR) to improve it!

## ✍️ Commit Etiquette

Good commit messages make collaboration easier. Follow these guidelines:

- **Keep it Clear**: Write concise, descriptive commit messages. Examples:
  - ✅ `Add user authentication to login page`
  - ✅ `Fix bug in file sorting script`
  - ❌ `Changes`, `Update`, or `Fix stuff`
- **Keep it Small**: Each commit should focus on one change (e.g., one feature or bug fix).
- **Use Present Tense**: Write messages like `Add feature` instead of `Added feature`.
- **Reference Issues**: If your commit addresses an issue, include the issue number (e.g., `Fix #42: Resolve login error`).

**Example**:
```bash
git commit -m "Add file sorting by extension #15"
```

## 🐛 Writing Issues

Clear issues help maintainers and contributors understand problems or feature requests. When opening an issue:

- **Title**: Summarize the problem or feature in a few words (e.g., `Bug: FileSorter crashes on empty folder`).
- **Body**:
  - Describe the issue or feature in detail.
  - Include steps to reproduce (for bugs).
  - Specify the expected behavior and actual behavior.
  - Add screenshots or code snippets if relevant.
- **Labels**: Use appropriate labels like `bug`, `feature`, `docs`, or `beginner-friendly` to categorize the issue.
- **Check for Duplicates**: Search existing issues to avoid duplicates.

**Example Issue**:
```
Title: Bug: NewsBot fails to scrape HTTPS sites

Description:
The NewsBot scraper throws a connection error when scraping HTTPS sites.

Steps to Reproduce:
1. Run `newsbot.py` with `https://example.com`.
2. Observe error: `SSL: CERTIFICATE_VERIFY_FAILED`.

Expected Behavior:
NewsBot should scrape HTTPS sites without errors.

Actual Behavior:
Crashes with SSL error.

Environment:
- OS: Ubuntu 20.04
- Python: 3.8

Suggested Fix:
Add SSL verification bypass or update certificate handling.
```

## 📝 Documentation Practices

Good documentation is as valuable as code! Follow these tips:

- **Update `README.md`**: If you add or change functionality, update the project’s `README.md` to reflect it.
- **Add Code Comments**: Include clear comments in your code to explain complex logic.
- **Submit Docs PRs**: If you improve documentation (e.g., fixing typos, adding examples), submit it as a pull request.
- **Be Clear and Concise**: Write documentation that’s easy for beginners to understand.

**Example**:
```python
# Sort files by extension in the given directory
def sort_files(directory):
    for file in os.listdir(directory):
        # Skip hidden files
        if file.startswith('.'):
            continue
        # ... rest of the code
```

## 🚀 How to Contribute

1. **Find a Project**: Browse the [Project Directory](docs/03_project_directory.md) to find a project that interests you.
2. **Claim an Issue**: Comment on a GitHub issue to let others know you’re working on it (e.g., “I’d like to take this!”).
3. **Fork and Clone**: Fork the project repo and clone it locally (`git clone <your-fork-url>`).
4. **Create a Branch**: Use a descriptive branch name (e.g., `git checkout -b fix-issue-42`).
5. **Make Changes**: Write your code or update documentation.
6. **Test Your Changes**: Ensure your code works and doesn’t break existing functionality.
7. **Submit a PR**:
   - Push your changes: `git push origin <branch-name>`
   - Open a pull request on GitHub with a clear title and description.
   - Link the issue your PR addresses (e.g., `Closes #42`).
8. **Respond to Feedback**: Address any review comments from maintainers.

## 🌐 Community Support

- **Join Discord**: Ask questions or share ideas in our [Discord server](https://discord.gg/hashslap).
- **Open an Issue**: If you’re stuck, open an issue in this repo or the project’s repo.
- **Practice First**: Try a dummy PR in our [practice repo](practice_repo/README.md) to get comfortable.

## ✅ Code of Conduct

Be kind, respectful, and inclusive. Follow our [Code of Conduct](CODE_OF_CONDUCT.md) to ensure a positive community for everyone.

---

*Thank you for contributing to HashSlap! Let’s build something amazing together. 💻*
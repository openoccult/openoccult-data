# Contributing to OpenOccult Data

Thank you for considering contributing to the OpenOccult Data repository! We welcome contributions from everyone, whether you're an experienced developer, translator, or simply passionate about the occult and metaphysics. This guide will help you get started.

---

## ✨ How to Contribute
**1. Report Issues or Suggest Features**

If you’ve found a bug, have a feature request, or want to suggest new data, you can:
- **Open a GitHub Issue**: Provide as much detail as possible.
- Include examples or screenshots (if applicable).

**2. Add or Edit Data**
Help improve our datasets by contributing additional data or refining existing ones:

- **Data Format**: All data should be in JSON format and follow the existing structure for consistency.

**3. Translate Data (i18n)**
Expand accessibility by translating content into other languages:

- **Locate the files**: `i18n/[language_code]/data/`.
- **Maintain the structure**: Match the original file structure and keys.
- **Contribute via Pull Request** (see below).
  
**4. Improve Documentation**
Help us refine this README, `CONTRIBUTORS.md`, or other docs.

---

## 🔄 Process for Contributing

### Step 1: Fork the Repository
1. Click the **Fork** button on the top-right corner of this repository.
2. Clone your forked repository to your local system:

```bash
git clone https://github.com/openoccult/openoccult-data.git
cd openoccult-data
```

### Step 2: Create a Branch
Create a branch for your changes:
```bash
git checkout -b feature-name
```

### Step 3: Make Your Changes
1. Add new files or modify existing ones.
2. Ensure your JSON is properly formatted and validated.

### Step 4: Test Your Changes
Run your JSON files through a linter or validator to ensure correctness. For example:

- [JSONLint](https://jsonlint.com/) for manual checks.
- Use CLI tools like `jq`:

```bash
jq . yourfile.json
```

### Step 5: Commit and Push
Commit your changes with a meaningful message:

```bash
git add .
git commit -m "Added new tarot deck translations for French"
git push origin feature-name
```

### Step 6: Open a Pull Request (PR)
1. Navigate to your forked repository on GitHub.
2. Click the **Compare & pull** request button.
3. Fill in a descriptive title and include details about your contribution.
4. Submit your pull request for review.

---

## 🛠 Guidelines
### Coding Standards
- Use camelCase for JSON keys.
- Follow the existing file structure and organization.
- Avoid duplicate IDs or conflicting keys.
  
### Translation Guidelines
- Keep translations culturally appropriate.
- Ensure proper grammar and spelling.
- If unsure about a term, consult with the community or leave a comment in the PR.
  
### Commit Messages
- Use clear and concise commit messages.
- Example: `Added Spanish translations for runes data`.

## 🧪 Validation and Testing
To ensure the integrity of the repository:

- Validate JSON files for syntax errors.
- Review and test file structure against existing guidelines.

## 🤝 Code of Conduct
We strive to create a welcoming and inclusive environment. By participating in this project, you agree to abide by our [Code of Conduct](https://github.com/openoccult/openoccult-data/blob/main/metadata/CODE_OF_CONDUCT.md).

## 🧑‍💻 Getting Help
If you encounter issues while contributing:

- Open an issue in this repository.
- Contact us at openoccult.com/support.

## 🎉 Thank You!
Your contributions make OpenOccult Data better for everyone. Whether you're sharing new insights or helping with translations, your efforts are greatly appreciated!
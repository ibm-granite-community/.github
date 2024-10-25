### PR Checklist

- [ ] **Commits signed**: All commits must be GPG or SSH signed.
- [ ] **DCO Compliance**: Developer Certificate of Origin (DCO) applies to the code, documentation, and any example data provided. Ensure commits are signed off.
- [ ] **Notebook outputs cleared**: Ensure all notebook outputs are cleared.
- [ ] **Automated testing**: Add the recipe to the automated tests.
- [ ] **Test in Google Colab**:
    - [ ] Test that it works in Google Colab (Python 3.10.12).
    - [ ] Colab has its own package set and Python version, so ensure compatibility.
- [ ] **Test locally**:
    - [ ] Ensure the code works in a fresh Python virtual environment (venv).
- [ ] **Standard access to secrets and variables** Include `!pip install git+https://github.com/ibm-granite-community/utils` in the first code cell in order to make `get_env_var` available to accessing secrets and variables in the recipe.
- [ ] **Flexible LLM platform support** The platform should be easily switchable. Use LangChain or LlamaIndex.
- [ ] **Example data**: Follow the example data guidance.
- [ ] **README.md updates**:
    - [ ] Add a link to the recipe in the Table of Contents (ToC).
    - [ ] Include a Colab button after that link.

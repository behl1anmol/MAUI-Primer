# Contributing Guidelines

Thank you for considering contributing to MAUI-Primer! Contributions are always welcome and appreciated.

**Please follow these guidelines to make the code review process go smoothly and increase the likelihood of your contribution being merged.**

## Bug Reports

If you encounter a bug or have a feature request, please submit an issue [here](https://github.com/behl1anmol/MAUI-Primer/issues).

## Pull Requests

To contribute, please follow these steps:

1. Fork the [main repository](https://github.com/behl1anmol/MAUI-Primer) by clicking the "Fork" button located at the top of the page.

2. Clone your forked repository to your local machine:

    ```
    $ git clone git@github.com:YourLogin/MAUI-Primer.git
    $ cd MAUI-Primer
    ```

3. Create a new branch to hold your changes and make your changes in that branch. It is important that you do not work in the `master` branch:

    ```
    $ git checkout -b my-feature
    ```

4. Use Git to manage your changes. Once you have finished making changes, use the following command to record your changes in Git:

    ```
    $ git add modified_files
    $ git commit
    ```

5. Push your changes to your forked repository on GitHub:

    ```
    $ git push -u origin my-feature
    ```

6. Finally, open your forked repository in your web browser and click the "Pull Request" button to submit your changes for review.

## GitHub Pull Requests Docs

If you are unfamiliar with pull requests, please review the [GitHub pull request documentation](https://help.github.com/articles/using-pull-requests/) for more information.

## Translations

To make the guide available to a wider audience, we encourage translations of the content. Here's how you can contribute to maintaining translations:

- The original version and content of the guide is maintained in English.
- Translations follow the content of the original. Contributors must speak at least some English, so that translations do not diverge.
- Each translation has a maintainer to update the translation as the original evolves and to review others' changes. It doesn't require a lot of time, but a review by the maintainer is important to maintain quality.

Please refer to [Translations](TRANSLATIONS.md) for more information.

### Updating Translations

- Changes to content should be made to the English version first, and then translated to each other language.
- Changes that improve translations should be made directly on the file for that language. Pull requests should only modify one language at a time.
- Submit a pull request with changes to the file in that language. Each language has a maintainer, who reviews changes in that language. Then the primary maintainer [@behl1anmol](https://github.com/behl1anmol) merges it in.
- Prefix pull requests and issues with language codes if they are for that translation only, e.g. "es: Improve grammar", so maintainers can find them easily.
- Tag the translation maintainer for a code review, see the list of [translation maintainers](TRANSLATIONS.md).
    - You will need to get a review from a native speaker (preferably the language maintainer) before your pull request is merged.

### Adding Translations for New Languages

We welcome translations to new languages! Here are the steps to follow:

- Check the [Translations](TRANSLATIONS.md) page, issues, and pull requests to see if a translation is already in progress or stalled. If it's in progress, offer to help. If it's stalled, consider becoming the maintainer if you can commit to it.
- If a translation has not yet been started, file an issue for your language so people know you are working on it and we can coordinate. Please confirm that you are a native speaker of the language and are willing to maintain the translation.
- To get started, fork the repository, then submit a pull request to the main repository with the single file README-xx.md added, where xx is the language code. Use standard [IETF language tags](https://www.w3.org/International/articles/language-tags/), i.e., the same as is used by Wikipedia, *not* the code for a single country. For example, `fr` for French and `uk` for Ukrainian (not `ua`, which is for the country). For languages that have variations, use the shortest tag, such as `zh-Hant`.
- Feel free to invite friends to help your original translation by having them fork your repository, then merging their pull requests to your forked repository. Translations are difficult and usually have errors that others need to find.
- Add links to your translation at the top of every README-XX.md file. For consistency, the link should be added in alphabetical order by ISO code, and the anchor text should be in the native language.
- When you have fully translated the English README.md, comment on the pull request in the main repository that it's ready to be merged.
    - You'll need to have a complete and reviewed translation of the English README.md before your translation will be merged into the `master` branch.
    - Once accepted, your pull request will be squashed into a single commit into the `master` branch.

### Translation Template Credits

Thanks to [The Art of Command Line](https://github.com/jlevy/the-art-of-command-line) for the translation template.

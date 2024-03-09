# Contributing to Clockworkz

We're thrilled you're considering contributing to Clockworkz! It's contributions from the community like yours that help make Clockworkz even better.

## Our Code of Conduct

In our community, we've embraced a Code of Conduct to ensure everyone feels welcome and respected. Please take a moment to [read the full text](CODE_OF_CONDUCT.md) to understand acceptable and unacceptable behaviors.

## Getting Started

### Understanding Clockworkz Projects

Each Clockworkz project resides in its own GitHub repository. To contribute effectively, start by familiarizing yourself with the project of interest. You'll typically find a [`README.md`](README.md) in each repository, offering a project overview and setup instructions.

## Contributing

### Reporting Bugs

To report a bug, please follow our guidelines, which help us understand, reproduce, and address the issue more efficiently. Before submitting a bug report, check existing GitHub Issues to avoid duplicates. When reporting, detail is key—fill out our issue template with as much information as possible.

### Suggesting Enhancements

We welcome suggestions for enhancements, including new features and improvements. Adhering to our guidelines ensures that we fully grasp your ideas. Similar to bug reporting, please search existing issues before submitting your suggestion.

### Your First Contribution

Not sure where to start? Look for issues tagged with `help-wanted` or `beginner`. These are great entry points:

- `help-wanted`: Simple fixes needing a few lines of code and possibly a test.
- `beginner`: Issues well-suited for newcomers.

### Making a Pull Request

Our goals are to maintain quality, address user issues, engage the community, and foster a sustainable review system. Here's how to proceed:

1. Complete the [Pull Request template](.github/PULL_REQUEST_TEMPLATE.md).
2. Adhere to our [style guides](#styleguides).
3. Ensure all status checks pass after submission.
4. Request a review in the #pr-reviews Slack channel if necessary.

**Versioning:** We use labels to manage semantic versioning. Unless specified, we assume a "minor" change. Here's how labels correlate with [semver](https://semver.org/):

- `Patch`: Backward compatible fixes. Increments the patch version.
- `Minor`: New, non-breaking features.
- `Major`: Changes that break backward compatibility.
- `No-release`: No new version release needed.

Transitioning from v0 to v1 signifies stability and is typically non-breaking. It's a decision made by Clockworkz engineers.

## Style Guides

### Git Commit Messages

- Present tense and imperative mood.
- Keep the first line under 72 characters.

### Pull Requests

- Use a `## References` section for mentioning related issues and PRs.
- Use `Closes #1234` to link PRs to issues they resolve.

### Terraform Style Guide & Best Practices

Follow our [Best Practices](https://docs.clockworkz.io/reference/best-practices/best-practices/) for consistent and maintainable code.

## Terraform Module Contributions

### Updating Module Documentation

Ensure variable descriptions are clear, especially after adding attributes. Use the commands below to update documentation:

```shell
make init
make readme
# Contributing to Clockworkz

We're thrilled you're considering contributing to Clockworkz! It's contributions from the community like yours that help make Clockworkz even better.

## Our Code of Conduct

In our community, we've embraced a Code of Conduct to ensure everyone feels welcome and respected. Please take a moment to [read the full text](CODE_OF_CONDUCT.md) to understand acceptable and unacceptable behaviors.

## Getting Started

### Understanding Clockworkz Projects

Each Clockworkz project resides in its own GitHub repository. To contribute effectively, start by familiarizing yourself with the project of interest. You'll typically find a [`README.md`](README.md) in each repository, offering a project overview and setup instructions.

## Contributing

### Reporting Bugs

To report a bug, please follow our guidelines, which help us understand, reproduce, and address the issue more efficiently. Before submitting a bug report, check existing GitHub Issues to avoid duplicates. When reporting, detail is key—fill out our issue template with as much information as possible.

### Suggesting Enhancements

We welcome suggestions for enhancements, including new features and improvements. Adhering to our guidelines ensures that we fully grasp your ideas. Similar to bug reporting, please search existing issues before submitting your suggestion.

### Your First Contribution

Not sure where to start? Look for issues tagged with `help-wanted` or `beginner`. These are great entry points:

- `help-wanted`: Simple fixes needing a few lines of code and possibly a test.
- `beginner`: Issues well-suited for newcomers.

### Making a Pull Request

Our goals are to maintain quality, address user issues, engage the community, and foster a sustainable review system. Here's how to proceed:

1. Complete the [Pull Request template](.github/PULL_REQUEST_TEMPLATE.md).
2. Adhere to our [style guides](#styleguides).
3. Ensure all status checks pass after submission.
4. Request a review in the #pr-reviews Slack channel if necessary.

**Versioning:** We use labels to manage semantic versioning. Unless specified, we assume a "minor" change. Here's how labels correlate with [semver](https://semver.org/):

- `Patch`: Backward compatible fixes. Increments the patch version.
- `Minor`: New, non-breaking features.
- `Major`: Changes that break backward compatibility.
- `No-release`: No new version release needed.

Transitioning from v0 to v1 signifies stability and is typically non-breaking. It's a decision made by Clockworkz engineers.

## Style Guides

### Git Commit Messages

- Present tense and imperative mood.
- Keep the first line under 72 characters.

### Pull Requests

- Use a `## References` section for mentioning related issues and PRs.
- Use `Closes #1234` to link PRs to issues they resolve.

### Terraform Style Guide & Best Practices

Follow our [Best Practices](https://docs.clockworkz.io/reference/best-practices/best-practices/) for consistent and maintainable code.

## Terraform Module Contributions

### Updating Module Documentation

Ensure variable descriptions are clear, especially after adding attributes. Use the commands below to update documentation:

```shell
make init
make readme

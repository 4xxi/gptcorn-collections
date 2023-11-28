# GPTCorn Collections

## Introduction

Welcome to the `gptcorn-collections` repository, a community-driven, open-source hub of prompt templates and
placeholders designed for both the [Open-Source](https://github.com/4xxi/gptcorn)
and [Cloud Hosted](https://app.gptcorn.ai) versions of GPTCorn. Our goal is to create a collaborative environment where
users from all backgrounds can share, explore, and leverage a wide variety of prompt templates for different purposes.

## Purpose

This repository serves as a hub for GPTCorn users to:

- Access a diverse range of prompt templates and placeholders.
- Contribute their own templates to enrich the community.
- Find inspiration for new and creative ways to use GPTCorn.

## Contributing

We warmly welcome contributions from the community! Here's how you can contribute:

1. **Fork the Repository**: Create your own copy of the repository to start adding your templates.
2. **Add Your Templates**: Place your prompt templates and placeholders in the designated folders.
3. **Submit a Pull Request**: Once you're ready, submit a pull request with a clear description of your templates and
   how they can be used.

Please refer to our [Contribution Guidelines](CONTRIBUTING.md) for more detailed instructions and coding standards.

## Using the Collections

Here’s how to add collections to your GPTCorn account:

1. Navigate to the 'Collections' area in your GPTCorn account.
2. You can either import a collection directly using its GitHub file URL, or first download the collection as a JSON
   file and then upload it in the import section of GPTCorn.

## JSON Template for Collection
Below is a JSON template for creating a collection:
```json
{
  "collections": [
    {
      "title": "GitHub helper",
      "description": "GPTCorn GitHub helper collection",
      "promptTemplates": [
        {
          "title": "Readme",
          "content": "Generate a README.md file for {github_helper_readme_repository_url}"
        }
      ],
      "placeholders": [
        {
          "key": "github_helper_readme_repository_url",
          "value": "https://github.com/4xxi/gptcorn-collections",
          "headline": "GitHub helper README.md repository URL",
          "description": "(Optional) GitHub repository URL to generate README.md file"
        }
      ]
    }
  ]
}
```

## Community Guidelines

As a community-driven project, we adhere to a code of conduct that ensures a respectful and constructive environment.
Please read our [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

## License

The `gptcorn-collections` repository is released under the MIT License. For more details, see the [LICENSE](LICENSE)
file.

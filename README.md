# Awesome WindsurfRules [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> This project is a fork of [awesome-cursorrules](https://github.com/PatrickJS/awesome-cursorrules), specifically adapted for Windsurf. The main difference is the support for global rules in Windsurf, which is reflected in the modified directory structure. While workspace rules are forked from the original project, the global rules feature is unique to this implementation.

A curated list of awesome `global_rules` and `.windsurfrules` files for enhancing your Windsurf experience.

[Windsurf](https://codeium.com/windsurf) is an AI-powered code editor. `global_rules` or `.windsurfrules` files define custom rules for Windsurf to follow when generating code, allowing you to tailor its behavior to your specific needs and preferences.

## Why Use Rules in Windsurf?

Windsurf offers two powerful types of rules - global rules that apply across all projects, and workspace rules for project-specific customization.

### Benefits of Global Rules

1. **Consistent Communication**: Global language rules ensure all interactions follow the same communication standards across projects.

2. **Standardized Practices**: Define organization-wide conventions for commit messages, code style, and documentation that apply uniformly.

3. **Security Baseline**: Establish common security practices and data handling rules that protect all projects.

4. **Performance Standards**: Set universal performance optimization guidelines that benefit every project.

### Benefits of Workspace Rules

1. **Project-Specific Customization**: Tailor the AI's behavior to your specific project's needs and requirements.

2. **Framework Alignment**: Ensure generated code follows the conventions of your chosen framework or technology stack.

3. **Context Awareness**: Provide project-specific context about architecture, libraries, and common patterns.

4. **Team Collaboration**: Share project-specific guidelines that keep the entire team aligned with local conventions.

5. **Dependency Management**: Define project-specific dependencies and version requirements.

By combining both global and workspace rules, you create a comprehensive set of guidelines that ensure consistency across your organization while maintaining the flexibility to address project-specific needs.

## Content

### Global Rules
Global rules are a unique feature in Windsurf that apply across all projects. They are organized in the following structure:

- [**./rules/global_rules/**](./rules/global_rules) - Root directory for global rules
  - [**global-en-language-global_rules-prompt-file/**](./rules/global_rules/global-en-language-global_rules-prompt-file)
    - English-only responses
    - Localization preferences
  - [**commit-message-short-global_rules-prompt-file/**](./rules/global_rules/commit-message-short-global_rules-prompt-file)
    - Standard prefixes (feat, fix, docs, etc.)
    - Short commit Message structure guidelines
  - [**commit-message-long-global_rules-prompt-file/**](./rules/global_rules/commit-message-long-global_rules-prompt-file)
    - Standard prefixes (feat, fix, docs, etc.)
    - Long commit Message structure guidelines

### Workspace Rules
Workspace rules are specific to each project and are organized in the following structure:

- [**./rules/windsurfrules/**](./rules/windsurfrules) - Root directory for workspace rules
  - [**./rules/windsurfrules/blueprint-windsurfrules-prompt-file**](./rules/windsurfrules/blueprint-windsurfrules-prompt-file)
    - Blueprint
  - [**./rules/windsurfrules/nextjs-vercel-supabase-windsurfrules-prompt-file**](./rules/windsurfrules/nextjs-vercel-supabase-windsurfrules-prompt-file)
    - Next JS, Vercel, Supabase using Blueprint

## Directories

## How to Use
1. Install [Windsurf](https://codeium.com/windsurf) if you haven't already.
2. Browse the rules above to find a `global_rules` or `.windsurfrules` file that suits your needs.
3. Copy the chosen `global_rules` or `.windsurfrules` file to your project's root directory or Windsurf's `Global Rules` file.
4. Customize the rules as needed for your specific project requirements.


## Contributing

Contributions are welcome! If you have a great `.windsurfrules` file to share:

1. Fork this repository.
2. Create a new folder in the `global_rules` or `.windsurfrules` directory. The folder name should follow this pattern:
   `technology-focus-windsurfrules-prompt-file`
   For example: `react-typescript-windsurfrules-prompt-file`
3. Add your `global_rules.md` or `.windsurfrules` file to the new folder.
4. Optionally, include a README.md in the folder to provide credit and a brief description.
5. Update the main README.md file, adding your contribution to the appropriate category.
6. Ensure your contribution follows the guidelines in the [`.windsurfrules`](./.windsurfrules) file at the root of this repository.
7. Submit a pull request.

Please ensure your contribution is original or properly credited if based on existing work. Refer to the `global_rules.md` or `.windsurfrules` file in the root of this repository for detailed guidelines on formatting, naming conventions, and best practices for contributions.

---

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

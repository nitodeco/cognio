# Cognio
### Game development Agents powered by GPT

Cognio is a Node.js Electron application that leverages the OpenAI Completions endpoint and an AI agent architecture to simulate an indie game development studio. Its primary purpose is to assist solo developers or small teams in completing larger game development projects faster than ever before.

## Features

-   Context preservation: Cognio remembers everything about your project without the need for reminders. 

-   Agents: AI Agents make up an entire development team, dedicated to bringing your idea to life.

-   Code Generation: Cognio assists in generating code for any game development task, reducing development time and effort.

-   Narrative Creation: Cognio can generate and review text, dialogue, and narrative content, making interactive storytelling easier than ever.

-   Localisation: Generate as many localisations as you need and have them reviewed by dedicated language agents.

## Getting Started

To get started with Cognio, follow these steps:

1.  Clone the repository to your local machine.

```bash
git clone https://github.com/nitodeco/cognio
```

2.  Install Node.js and npm if you haven't already.
3.  Install project dependencies.

```bash
npm install
```

4.  Configure your OpenAI API credentials. See more under [configuration](#configuration)

### Start development environment
```
npm run serve
```

### Build production version
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

## Configuration

To use Cognio, you need to have a topped up OpenAI platform account. Configure your API-key in a .env.local file in the root directory as OPENAI_API_KEY. If you don't already have API access or need help setting it up, please visit the [OpenAI developer platform](https://platform.openai.com/docs/overview).

## Usage

Cognio's user interface is designed to be intuitive and user-friendly. Explore the different features and functionalities to streamline your game development process.

## License

This project is licensed under the MIT License - see the [license file](LICENSE) for details.

Additionally, please note that large game distributors like Steam currectly forbid games with AI generated content on their platform. so use Cognio at your own discretion.

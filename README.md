# LangChain4J Dall-E3 Demo

A super simple Java Spring project that utilizes DALL-E3, LangChain4J, and Azure Open AI.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/sandraahlgrimm/langchain4j-dalle3-demo.git
    ```

2. Set up the environment variables:

    - `AZURE_OPENAI_ENDPOINT`: Your Azure OpenAI Endpoint.
    - `AZURE_OPENAI_DEPLOYMENT_NAME`: Your Azure Open AI Deployment name.
    - `AZURE_OPENAI_API_KEY`: Your Azure Open AI API key.

3. Install the required dependencies:

    ```bash
    mvn clean install
    ```

4. Build and run the Java Spring project:

    ```bash
    mvn spring-boot:run
    ```

## Usage

1. By running the Java Spring project, you can see the image generated in the System output and also the revised prompt generated by Azure Open AI Text Completion.

![Screenshot of the executed project](./images/screenshot-run-image-creation.png)

2. Please, change the prompt or rerun the same prompt multiple times to see the differences.

```json
Prompt: "Create an image of a horse race with three horses."

revisedPrompt = "Imagine a dynamic scene of a horse race. There are three horses vigorously running on a turf track with determination in their eyes. One horse is white with a streamlined build, the other is a majestic black stallion with a glossy coat, and the third is a vibrant chestnut horse with strong muscular legs. Their jockeys are skillfully riding them; a Middle-Eastern woman in blue silks on the white horse, a Hispanic man in red silks on the black stallion, and a Caucasian woman in green silks riding the chestnut horse. It's a bright sunny day, and the crowd in the stands is a blur of excited faces and colorful attire."
```

![Generated image](./images/generated_00.png)

## Contributing

Feel free to fork, clone, and contribute to this project. If you have any questions or suggestions, please feel free to open an issue.

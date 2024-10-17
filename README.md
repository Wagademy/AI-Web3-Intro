# AI-Web3-Intro

Building AI-Powered dApps: Intro to Generative AI for Blockchain Applications

## Introduction

Welcome to the **Building AI-Powered dApps Workshop**. This README provides an overview of the workshop, its goals, and the resources available to participants.

## Workshop Overview

The workshop is designed to introduce participants to the fundamentals of building decentralized applications (dApps) powered by Generative AI. It aims to equip students with practical skills to develop AI-powered dApps and understand the intersection of AI and blockchain technologies.

## What is AI?

- AI before November 30, 2022
  - First formal mention of AI was in [1956 by John McCarthy](https://home.dartmouth.edu/about/artificial-intelligence-ai-coined-dartmouth)
  - First decades of AI focused on rule-based systems
    - AI was seen as a way to **automate** tasks that required human intelligence
  - By early 2000s, AI applications became more common, especially in digital environments
    - AIs for marketing, customer service, and other digital tasks
    - AIs for search engines, recommendation systems, and other digital services
    - AIs for games, simulations, and other digital entertainment
- November 30, 2022 -> ChatGPT launch date
- AI now
  - With ChatGPT (and all similar generative AI tools that followed), AI has entered an age of **mass adoption**
  - AI is now used to **create** content, not just to **automate** tasks
  - AI is now used to (attempt to) _"understand"_ content, not just to **process** data
  - AI is now used to **generate** brand new content, not just to **recommend** or slightly **modify** existing content

## Introduction to Generative AI

- Programming a system or application to solve a specific task can take a lot of time and effort, depending on the complexity of the task and the number of edge cases that need to be considered
  - Imagine programming a system to translate text from one language to another by looking up words in a dictionary and applying grammar rules, comparing contexts, and considering idiomatic expressions for every single word in every single variation of their usage
    - Such applications are simply not feasible to be programmed by hand, not even by a huge team of programmers
- For these situations, **AI Models** can be **trained** for statistically solving the task without necessarily handling the actual _"reasoning"_ or _"understanding"_ of the task
  - The **training** process is done by **feeding** the model with **examples** of the task and the **correct** answers
  - The **model** then _"learns"_ the **patterns** and **rules** that **statistically** solve the task
  - The **model** can then **predict** the **correct** answer for new **examples** that it has never seen before

## Generative AI

- Generative AI is a type of AI that can generate new content based on a given input
  - The generated content can be in form of text, images, audio, or any other type of data
  - The input (in most cases) is a text prompt, which is a short text that the user writes to ask the AI to do something
    - Ideally the AI should be able to handle prompts in natural language (i.e. in a way that is similar to how humans communicate), without requiring domain-specific knowledge from the user
    - Together with the prompt, the user can also provide images or other types of data to guide the AI in generating the content
- Example of Generative AI application: [ChatGPT](https://chat.openai.com/)

> Did someone program the application to understand and generate text for each single word in each single language?
>
> > No, the application was **trained** to _"understand"_ and generate text

- How to **train** an application?
  - Applications are pieces of **software** that run on a **computer**
  - How do we **train** a **computer**?
- Machine learning

> "A computer program is said to learn from experience E with respect to some class of tasks T and performance measure P, if its performance at tasks in T, as measured by P, improves with experience E." [Tom M Mitchell et al](https://www.cs.cmu.edu/~tom/mlbook.html)

- Does it mean that the computer is _"learning"_?
- Does it mean that the computer is _"thinking"_?
- Does it mean that the computer is _"conscious"_?

## Capabilities and Limitations of Generative AI

- [Stochastic parrot](https://en.wikipedia.org/wiki/Stochastic_parrots)
  - A critique view of current LLMs (large language models)
    - LLMs are limited by the data they are trained by and are simply stochastically repeating contents of datasets
    - Because they are just "making up" outputs based on training data, LLMs do not _understand_ if they are saying something incorrect or inappropriate
- [The Chinese Room](https://en.wikipedia.org/wiki/Chinese_room) philosophical experiment presented by John Searle in 1980
  - The notion of machine _understanding_
  - The implementation of syntax alone would constitute semantics?
  - A _simulation_ of mentality can be considered as a **replication** of mentality?
- Can AI truly "understand" language?
  - What is, indeed, "understanding"?
    - [Aristotle. (350 BCE). Metaphysics.](https://classics.mit.edu/Aristotle/metaphysics.html): Knowledge of causes
    - [Locke, J. (1690). An Essay Concerning Human Understanding.](https://www.gutenberg.org/files/10615/10615-h/10615-h.htm): Perception of agreement or disagreement of ideas
    - [Dilthey, W. (1900). The Rise of Hermeneutics.](https://www.degruyter.com/document/doi/10.1515/9780691188706-006/html?lang=en): Interpretive process of making meaning
    - [Ryle, G. (1949). The Concept of Mind.](https://archive.org/details/conceptofmind0000ryle): Ability to apply knowledge in various contexts
    - [Chalmers, D. (1996). The Conscious Mind.](https://personal.lse.ac.uk/ROBERT49/teaching/ph103/pdf/Chalmers_The_Conscious_Mind.pdf): Functional role in cognitive system

## AI Code Generation

To expedite frontend code creation for our web application, we can leverage Generative AI Tools for code generation.

Tools like ChatGPT and Copilot can not only enhance developer efficiency but also generate substantial code segments that serve as starting points for software projects.

While the accuracy of these tools isn't perfect, and the generated code may require adjustments and improvements, it often provides a valuable foundation for developers to "understand" feature or functionality implementation.

Some models are specifically designed and/or optimized for code generation. Unlike the general-purpose LLMs we've been using, these models are trained on code repositories and can generate code snippets based on input prompts. Users still need to integrate these snippets to form complete code, but the generated content can serve as a solid starting point for projects or new features. Examples include [Codex](https://openai.com/index/openai-codex/) from OpenAI, [CodeT5](https://github.com/salesforce/CodeT5) from Salesforce, and [Code Llama](https://ai.meta.com/blog/code-llama-large-language-model-coding/) from Meta.

Other models/tools are designed for versatility, capable of generating code snippets, providing instructions, explaining code, suggesting fixes, proposing tests, adding documentation, and more. These models can detect code context and generate the most appropriate suggestions based on user requests. Examples include [Copilot](https://copilot.github.com/) (powered by the Codex model), [TabNine](https://www.tabnine.com/), and [Replit](https://replit.com/). These tools can generate code snippets based on your IDE context while coding.

Some tools are designed to automatically generate and assemble entire applications based on simple descriptions of desired layout and functionality. These can be particularly helpful for developers creating frontend code for web applications.

A standout tool for this purpose is [v0](https://v0.dev/) from Vercel. `v0` is a web tool that generates frontend code based on simple descriptions of desired layout and functionality.

Another valuable tool is [MakeReal](https://makereal.tldraw.com/) from TLDraw. `MakeReal` is a web tool that generates frontend code based on simple descriptions and rough sketches of desired layout and elements.

These tools can significantly assist developers in creating frontend code for web applications and can be utilized to generate code for this lesson's exercises.

> Be advised that the generated code may require significant adjustments and improvements to function properly. Never rely blindly on AI-generated code.

## Code Generation Models

- Training and fine-tuning techniques for code generation
- Instruction-following capabilities
- Retrieval and context evaluation methodologies
- Optimizing behavior through parameter adjustments and constraints

### Code Generation Examples

- [CodeLlama](https://ai.meta.com/blog/code-llama-large-language-model-coding/)
- [Copilot](https://copilot.github.com/)
- [Cursor](https://cursor.com/)
- [Replit AI](https://replit.com/ai)
- [Q Developer](https://aws.amazon.com/q/developer/)
- [Cody](https://sourcegraph.com/docs)
- [Devin](https://www.cognition-labs.com/blog), the AI software engineer

## Peer programming with AI

- AI [features](https://www.cursor.com/features) of the [Cursor IDE](https://cursor.com/)
  - Code generation
  - Code editor
  - Rewriting and fixing code automatically
  - Enhanced predictions
  - Chat with your code
  - Link web documentation while chatting
- Setup
  - Download and install
    - May require some manual setup for Linux and MacOS
  - Create a free account
- Recommended settings
  - Tweak keyboard shortcuts
  - Import extensions and settings from VSCode
  - Privacy mode
  - Configuring models
- Usage
  - Fixing issues
  - Generating code
  - Chatting with your code
  - Using the chat
  - Generating commit messages
  - Generating documentation and test scripts based on other files

## Setting Up a Web Development Environment

- Essential tools for Web Development
  - **Text Editor**: A tool for writing and editing code, such as [Visual Studio Code](https://code.visualstudio.com/), [Sublime Text](https://www.sublimetext.com/), or [Atom](https://atom-editor.cc/)
  - **Web Browser**: A software application for accessing information on the World Wide Web, such as [Google Chrome](https://www.google.com/chrome/), [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), or [Microsoft Edge](https://www.microsoft.com/en-us/edge)
  - **Terminal**: A command-line interface for interacting with the operating system, such as [Windows Command Prompt](https://docs.microsoft.com/en-us/windows-server/administration/windows-commands/windows-commands), [Windows PowerShell](https://learn.microsoft.com/en-us/powershell/scripting/overview), [macOS Terminal](https://support.apple.com/guide/terminal/welcome/mac), or [Linux Terminal](https://ubuntu.com/tutorials/command-line-for-beginners)
  - **Version Control System**: A tool for tracking code changes and collaborating with other developers, such as [Git](https://git-scm.com/)
  - **JavaScript Runtime**: An environment that allows you to run JavaScript code outside of a web browser, such as [Node.js](https://nodejs.org/en/download/)
  - **Node Package Manager**: A package manager for JavaScript that allows you to install and manage dependencies for your projects, such as [npm](https://docs.npmjs.com/)
    - Alternatives include [Yarn](https://yarnpkg.com/), [pnpm](https://pnpm.io/), [bun](https://bun.sh/), or other package managers
- Using Node.js
  - Utilizing a package manager
  - The package.json file
    - Installing dependencies
    - Running scripts
  - The `node_modules` folder
  - Folder structure
- Using Git
  - Cloning a repository
  - Committing changes
  - Pushing changes
  - Pulling changes
  - Branching and merging
- Creating a Web Application project
- Utilizing starter-kits and frameworks

## Coding Using Next.js

- Framework Structure
  - Recent versions of Next.js allow project creation with two major structures: [Pages router](https://nextjs.org/docs/pages/building-your-application/routing/pages-and-layouts) or [App router](https://nextjs.org/docs/app/building-your-application/routing/pages-and-layouts)
    - The Pages router is the more common structure, where each file in the `pages` directory corresponds to a route in the application
    - The App router is a more recent and slightly more complex structure, where routes are governed by a JavaScript API instead of being implicitly defined by the file system
- Utilizing TypeScript and TSX
  - [TypeScript](https://www.typescriptlang.org/docs/) is a superset of JavaScript that adds static typing, providing type checking and code completion features that help catch errors early in the development process
    - TypeScript is a powerful tool for building large-scale applications, enforcing strict type checking and providing a more robust development experience
  - [TSX](https://www.typescriptlang.org/docs/handbook/jsx.html) is a syntax extension for TypeScript allowing developers to write JSX (JavaScript XML) in TypeScript files
    - JSX is a syntax extension for JavaScript enabling developers to write HTML-like code directly in their JavaScript files
    - TSX can be used to create [React Components](https://react.dev/learn/typescript) that are processed and rendered dynamically when the application is compiled/bundled for deployment
- Creating Components
  - Components are the building blocks of a React application, representing reusable and independent parts of the user interface
    - Components can be functional or class-based, containing their own logic, state, and lifecycle methods
  - Components can be created using the `function` keyword or the `class` keyword
    - Functional components are simpler and more concise, while class-based components offer more features and flexibility
  - Components can receive data through props, passed from parent components
    - Props are read-only and cannot be modified by the component
  - Components can also have internal state, managed using the `useState` hook
    - State allows components to store and update data locally
- Using Hooks
  - [Hooks](https://react.dev/reference/react/hooks) are functions allowing functional components to use state and other React features
    - Hooks provide a way to reuse stateful logic across components, facilitating the sharing and management of stateful logic in a React application
  - Common hooks include:
    - `useState`: Allows components to manage local state
    - `useEffect`: Enables components to perform side effects, such as data fetching and DOM manipulation
    - `useContext`: Allows components to access context values
    - `useRef`: Enables components to create mutable references to DOM elements
  - There are [recommended rules](https://react.dev/reference/rules/rules-of-hooks) for using hooks in React applications to avoid bugs and ensure proper functionality
- Implementing Tailwind CSS
  - [Tailwind CSS](https://tailwindcss.com/docs) is a utility-first CSS framework streamlining the styling process by providing pre-defined utility classes for direct use in HTML markup
    - Tailwind CSS is designed to be highly customizable and extendable, allowing developers to create unique and responsive designs without writing custom CSS
  - Tailwind CSS classes can be [applied directly to HTML elements](https://tailwindcss.com/docs/utility-first) for styling
    - Classes are used to apply styles such as colors, fonts, spacing, and layout to elements
    - These classes can be [reused for many elements](https://tailwindcss.com/docs/reusing-styles) and combined to create complex layouts and designs
  - Tailwind CSS provides utility classes for [responsive design](https://tailwindcss.com/docs/responsive-design), enabling developers to create layouts that adapt to different screen sizes
    - Responsive classes can be used to apply different styles based on screen size, such as hiding elements on mobile devices or changing the layout on larger screens
  - You can [customize your styles](https://tailwindcss.com/docs/adding-custom-styles) in Tailwind CSS by editing the configuration file and adding custom utility classes
    - Customizing Tailwind CSS allows you to create a unique design system for your entire application and tailor the framework to your specific needs

## Building an Application Using Next.js

1. Create a new folder for your projects:

   ```bash
   mkdir my-projects
   cd my-projects
   ```

   > Pick a _safe_ location on your computer to store your projects. You can use the `Documents`, `Desktop`, or any other folder you prefer.

2. Create a new NextJS project using the following command:

   ```bash
   npx create-next-app my-next-app
   ```

   - You can give any name to your project by replacing `my-next-app` with your preferred name
   - Pick all the default options when prompted
     - ✔ Would you like to use TypeScript? … No / **Yes**
     - ✔ Would you like to use ESLint? … No / **Yes**
     - ✔ Would you like to use Tailwind CSS? … No / **Yes**
     - ✔ Would you like to use `src/` directory? … **No** / Yes
     - ✔ Would you like to use App Router? (recommended) … No / **Yes**
     - ✔ Would you like to customize the default import alias (@/\*)? … **No** / Yes

3. Navigate to the newly created project folder:

   ```bash
   cd my-next-app
   ```

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open your browser and navigate to `http://localhost:3000` to see your NextJS project running

6. Open the `app/page.tsx` file in your editor to make changes to the home page

7. Replace the existing code in `app/page.tsx` with the following:

   ```tsx
   export default function Home() {
     return (
       <>
         <h1>Hello World</h1>
         <p>This is a test</p>
       </>
     );
   }
   ```

8. Save the file and refresh your browser to see your changes

9. Apply some styling to the page using the `Tailwind CSS` classes

   ```tsx
   export default function Home() {
     return (
       <>
         <div className="flex flex-col items-center justify-center min-h-screen">
           <h1 className="text-4xl font-bold mb-4 text-blue-600">
             Hello World
           </h1>
           <p className="text-xl text-gray-500">This is a test</p>
         </div>
       </>
     );
   }
   ```

10. Create some page elements

    ```tsx
    export default function Home() {
      return (
        <>
          <div className="flex flex-col items-center justify-center min-h-screen">
            <div className="flex flex-col items-center justify-center">
              <h1 className="text-4xl font-bold mb-4 text-blue-600">
                Hello World
              </h1>
              <p className="text-xl text-gray-500">This is a test</p>
            </div>
            <div className="flex flex-row items-center justify-center py-4">
              <input
                type="text"
                placeholder="Enter your name"
                className="bg-gray-200 p-2 rounded-md mr-2"
              />
              <button className="bg-blue-600 text-white p-2 rounded-md">
                Submit
              </button>
            </div>
          </div>
        </>
      );
    }
    ```

11. Import some functionalities from the `react` library:

    ```tsx
    "use client";
    import { useState } from "react";
    ```

12. Create some dynamic content in the page:

    ```tsx
    export default function Home() {
      const [name, setName] = useState("");
      const [showGreeting, setShowGreeting] = useState(false);

      const handleSubmit = () => {
        setShowGreeting(true);
      };

      return (
        <>
          <div className="flex flex-col items-center justify-center min-h-screen">
            <div className="flex flex-col items-center justify-center">
              <h1 className="text-4xl font-bold mb-4 text-blue-600">
                Hello World
              </h1>
              <p className="text-xl text-gray-500">This is a test</p>
            </div>
            <div className="flex flex-row items-center justify-center py-4">
              <input
                type="text"
                placeholder="Enter your name"
                className="bg-gray-200 p-2 rounded-md mr-2 text-black"
                value={name}
                onChange={(e) => setName(e.target.value)}
              />
              <button
                className="bg-blue-600 text-white p-2 rounded-md"
                onClick={handleSubmit}
              >
                Submit
              </button>
            </div>
            {showGreeting && (
              <div className="mt-4 p-4 bg-gray-100 rounded-md w-full max-w-2xl">
                <p className="text-3xl font-bold text-black">Hello {name}</p>
                <textarea
                  className="w-full h-40 mt-4 p-2 text-lg text-black bg-white border border-gray-300 rounded-md resize-none"
                  placeholder="Enter your message here..."
                ></textarea>
              </div>
            )}
          </div>
        </>
      );
    }
    ```

## Getting Started with Generative AI APIs for Text-to-Text Tasks

- Using the [OpenAI Platform](https://platform.openai.com/)
  - [Docs](https://platform.openai.com/docs/introduction)

### Using OpenAI Chat Playground

1. Go to [OpenAI Chat Playground](https://platform.openai.com/playground?mode=chat)
2. Use the following parameters:

   - System settings:

     "_You are a knowledgeable and resourceful virtual travel advisor, expertly equipped to assist with all aspects of travel planning. From suggesting hidden gems and local cuisines to crafting personalized itineraries, you provide insightful, tailored travel advice. You adeptly navigate through various travel scenarios, offering creative solutions and ensuring a delightful planning experience for every traveler._"

   - User prompt:

     "_Hello! I'm dreaming of an adventure and need your help. I want to explore a place with breathtaking landscapes, unique culture, and delicious food. Surprise me with a destination I might not have thought of, and let's start planning an unforgettable trip!_"

   - Configurations:
     - Model: `gpt-4`
     - Temperature: `0.75`
     - Max tokens: `500`
     - Top p: `0.9`
     - Frequency penalty: `0.5`
     - Presence penalty: `0.6`

3. Click on `Submit`
4. Wait for the response from `Assistant`
5. Ask a follow-up question like "_What are the best amusements for kids there?_" or similar
6. Click on `Submit`
7. Wait for the response from `Assistant`, which should use the context from the previous messages to generate a response
8. Keep experimenting with other messages and **parameters**

## Parameters

- **Agent description**: This plays a crucial role in guiding the AI's behavior and response style. Different descriptions can set the tone, personality, and approach of the model.

  - Example: "You are a creative storyteller" would prompt the AI to adopt a more imaginative and narrative style, whereas "You are a technical expert" might lead to more detailed and specific technical information in responses.

- **Temperature**: Controls the randomness of the responses.

  - Lower temperature (0.0-0.3): More predictable, conservative responses, ideal for factual or specific queries.
  - Higher temperature (0.7-1.0): More creative and varied responses, useful for brainstorming or creative writing.

- **Max Tokens (Length)**: Sets the maximum length of the response.

  - Lower range (50-100 tokens): Suitable for concise, straightforward answers.
  - Higher range (150-500 tokens): Suitable for more detailed explanations or narratives.

- **Stop Sequence**: A list of up to four sequences of tokens that, when generated, signal the model to stop generating text. Useful for controlling response length or preventing off-topic content.

- **Top P (Nucleus Sampling)**: Determines the breadth of word choices considered by the model.

  - Lower setting (0.6-0.8): More predictable text, good for formal or factual writing.
  - Higher setting (0.9-1.0): Allows for more creativity and divergence, ideal for creative writing or generating unique ideas.

- **Frequency Penalty**: Reduces the likelihood of the model repeating the same word or phrase.

  - Lower setting (0.0-0.5): Allows some repetition, useful for emphasis in writing or speech.
  - Higher setting (0.5-1.0): Minimizes repetition, helpful for generating diverse and expansive content.

- **Presence Penalty**: Discourages the model from mentioning the same topic or concept repeatedly.
  - Lower setting (0.0-0.5): Suitable for focused content on a specific topic.
  - Higher setting (0.5-1.0): Encourages the model to explore a wider range of topics, useful for brainstorming or exploring different aspects of a subject.

> Learn more about these parameters at [OpenAI API Reference](https://platform.openai.com/docs/api-reference/chat/create)

## Implementing AI Features in Applications

### OpenAI APIs

- API Functionality
  - API calls enable remote execution of operations on servers over the internet, offering several advantages:
    - Leveraging substantial computational power not available on local devices
    - Processing large datasets that exceed local storage capabilities
    - Handling sensitive data (e.g., credentials, personal information) securely on remote servers
    - Protecting sensitive operations from client-side exposure
- Interacting with APIs over HTTP
  - APIs serve as essential interfaces for accessing and manipulating web service resources
  - In Python, the widely-used 'requests' library facilitates HTTP interactions:
    - Constructing HTTP requests:
      - Specify request method (GET, POST, PUT, DELETE, etc.)
      - Define API endpoint URL
      - Example: `response = requests.get('https://api.example.com/data')`
    - Processing API responses:
      - Retrieve data from response body
      - Access metadata (HTTP status codes, headers)
      - Example: `print(response.text)`
    - Implementing authentication:
      - Include credentials in request headers
      - Example:

        ```python
        headers = {'Authorization': 'Bearer YOUR_ACCESS_TOKEN'}
        response = requests.get('https://api.example.com/data', headers=headers)
        ```

    - Handling errors:
      - Check response status codes
      - Implement appropriate error handling
      - Example:

        ```python
        if response.status_code == 200:
            print('Request was successful')
        else:
            print('Error:', response.status_code)
        ```

  - Benefits of API-based processing:
    - Execution of resource-intensive tasks on powerful remote servers
    - Secure handling of sensitive data without local exposure
    - Efficient transfer of processed results to the client

This approach enables developers to leverage remote computational resources and data securely, while maintaining a lightweight client-side application.

- OpenAI API
  - The OpenAI API provides access to a variety of powerful artificial intelligence models trained on large datasets, including text generation, image generation, and natural language recognition models. Developers can integrate AI capabilities into their applications, websites, and systems by accessing models through specific API endpoints.
  - Since the use of this computation is billed, OpenAI needs to identify and authorize (or deny) each person/agent making requests to the API
    - This is achieved by assigning a unique **secret key** or set of keys, which are specific to each user and must be included in every request made to the API
  - Authentication to the OpenAI API is performed through the use of an **API key**. Each user is assigned a unique API key that must be included in every request made to the API. The API key is typically passed as an **HTTP header** in the request or as a query parameter.
  - Each request made to the API incurs costs; that is, each computation performed on the OpenAI API is charged to the user
  - Costs may vary based on the type of model used, the size of the request and response, and the amount of compute power and resources utilized
    - The models have different costs depending on the amount of data (tokens, pixels, etc.) they process
    - The [Pricing](https://openai.com/api/pricing/) page has the most up-to-date information on the costs of the different models and tasks
- Endpoints
  - Each endpoint available in the OpenAI API offers specific functionality to meet developers' needs
  - There isn't a single endpoint that can be used to access all the models and capabilities of the OpenAI services
    - Instead, there are several endpoints, each providing access to a specific model or set of models, and each with its own set of capabilities and requirements
  - The most common endpoints are **chat** for text generation tasks, **audio** for speech recognition and creation, **images** for image generation and helpers for passing images to chat completion endpoints, and **fine_tuning** for creating and managing fine-tuning jobs and models
    - There are many other useful endpoints for tasks such as creating assistants, moderating text content, calculating text embeddings, and more
    - For a comprehensive list of features, refer to the "Capabilities" section of the [OpenAI Platform Documentation](https://platform.openai.com/docs/overview) and the "Endpoints" section of the [API Reference](https://platform.openai.com/docs/api-reference/introduction)
- Text Generation
  - The **chat** endpoint in the OpenAI API allows users to request text generation based on the provided input, which is useful for text autocompletion, content generation, and language translation
  - [Chat Completions](https://platform.openai.com/docs/guides/text-generation/chat-completions-api) tasks require passing at least a **model definition** and a **message** in the **request body**
    - In the body, you can pass many other parameters such as model configurations for **temperature** and **max_tokens**, and request options for **stream** and **user**
  - The response object will contain the generated text inside an object called **choices**, as well as additional metadata such as the **model** used, the **system_fingerprint** of the GPT version, and the **usage** statistics of the API request
- Image Generation
  - The **image** endpoint in the OpenAI API allows users to request the generation of images based on a given input. Users can provide a description or visual input, and the API generates corresponding images using specific artificial intelligence models designed for this purpose.
- Vision
  - OpenAI's **chat** endpoint allows passing one or multiple images as content in the request body, under the **content** object, by giving it a type of **image_url**
    - The provided images can then be used when the model is generating a response by first being processed through an _image recognition_ process, and then being used as _context_ for the _text generation_ process
      - According to the [documentation](https://platform.openai.com/docs/guides/vision), the model excels at answering general questions about the contents of images, but it's not yet optimized to answer detailed questions about the location of specific objects in an image
        - For example, you can ask about the color of a car or suggest dinner ideas based on the contents of your fridge, but if you show it an image of a room and ask where the chair is, it may not answer the question accurately
  - You can control the **detail** parameter to specify how the model processes the image and generates its textual understanding
    - You can provide three options: **low**, **high**, or **auto**
    - By default, the model will use the **auto** setting, which will examine the image input size and decide whether to use the **low** or **high** setting
      - Using **low** will enable the "low res" mode, where the model receives a low-resolution 512px x 512px version of the image and represents the image with a budget of 65 tokens
        - This allows the API to return faster responses and consume fewer input tokens for use cases that don't require high detail
      - Using **high** will enable "high res" mode, which first allows the model to see the low-res image and then creates detailed crops of input images as 512px squares based on the input image size
        - Each of the detailed crops uses twice the token budget (65 tokens) for a total of 129 tokens

### Implementing OpenAI API Calls

- The [OpenAI Python API library](https://github.com/openai/openai-python)
- The [OpenAI Typescript API library](https://github.com/openai/openai-node)
- Environment setup
- Authentication
- Calling the endpoints
- Handling the responses

## Creating a Simple Chat Page

1. Open the project created in the previous exercise in a text editor

2. Edit your `page.tsx` file to include the following code:

   ```tsx
   "use client";

   import React from "react";

   const Home = () => {
     const message = "Hello World!";

     return (
       <main className="min-h-screen bg-gray-900 py-6 flex flex-col justify-center sm:py-12">
         <h1 className="text-4xl font-bold text-center text-gray-100 mb-8">
           Chat Page
         </h1>
         <section className="max-w-3xl mx-auto w-full">
           <div className="bg-gray-800 shadow-lg rounded px-8 pt-6 pb-8 mb-4">
             <p className="text-xl text-gray-300">{message}</p>
           </div>
         </section>
       </main>
     );
   };

   export default Home;
   ```

3. Save the file and navigate to `http://localhost:3000` in your browser to view the changes

4. Stop the server by pressing `Ctrl+C` or `Cmd+C` in your terminal

5. Install the `openai` [npm package](https://www.npmjs.com/package/openai) by running `npm install openai` in your terminal

6. Create a `.env` file in the root of your project and add your OpenAI API key

   ```text
   OPENAI_API_KEY=sk-...
   ```

7. Create a folder called `api` inside the `app` folder the root of your project

8. Create a folder named `chat` inside the `api` folder

9. Create a file named `route.ts` inside the `chat` folder

10. Paste the following code into the `route.ts` file:

    ```typescript
    import OpenAI from "openai";
    import { NextResponse } from "next/server";

    const openai = new OpenAI();

    export const runtime = "edge";

    export async function POST(req: Request) {
      const { messages } = await req.json();

      const response = await openai.chat.completions.create({
        model: "gpt-4o-mini",
        messages,
      });

      return NextResponse.json({
        content: response.choices[0].message.content,
      });
    }
    ```

11. Modify the UI with the chat components:

    - In VSCode, open the file 'page.tsx' inside the folder 'app'

    - Replace the existing code with the following:

    ```typescript
    "use client";
    import { useState } from "react";

    const Home = () => {
      const [message, setMessage] = useState("");
      const [response, setResponse] = useState("");

      const handleSubmit = async (e: React.FormEvent) => {
        e.preventDefault();
        const res = await fetch("/api/chat", {
          method: "POST",
          headers: {
            "Content-Type": "application/json",
          },
          body: JSON.stringify({
            messages: [{ role: "user", content: message }],
          }),
        });
        const data = await res.json();
        setResponse(data.content);
        setMessage("");
      };

      return (
        <main className="min-h-screen bg-gray-900 py-6 flex flex-col justify-center sm:py-12">
          <h1 className="text-4xl font-bold text-center text-gray-100 mb-8">
            Chat Page
          </h1>
          <section className="max-w-3xl mx-auto w-full">
            <div className="bg-gray-800 shadow-lg rounded px-8 pt-6 pb-8 mb-4">
              {!response && (
                <form
                  onSubmit={handleSubmit}
                  className="flex flex-col space-y-4"
                >
                  <input
                    type="text"
                    value={message}
                    onChange={(e) => setMessage(e.target.value)}
                    placeholder="Enter your message"
                    className="px-3 py-2 bg-gray-700 text-white rounded"
                  />
                  <button
                    type="submit"
                    className="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded"
                  >
                    Send
                  </button>
                </form>
              )}
              {response && (
                <div className="mt-4 p-3 bg-gray-700 text-white rounded">
                  <p>{response}</p>
                </div>
              )}
            </div>
          </section>
        </main>
      );
    };

    export default Home;
    ```

12. Run the application: Now that everything is set up, you can start your application

    - On your terminal, run the following command:

    `npm run dev`

    - If everything is okay, you can now access the application at <http://localhost:3000/>

## Building AI-Powered dApps

### Scaffold ETH 2

- [Scaffold ETH 2](https://scaffoldeth.io/) is a development framework for building Ethereum dApps
- Provides tools and components for smart contract and frontend development
- Key features:
  - Rapid prototyping with pre-configured environment
  - Smart contract development with Solidity templates
  - Frontend integration with React components for Ethereum
  - Local blockchain setup with Hardhat and Foundry
  - Automated testing tools for smart contracts
  - Simplified deployment to Ethereum networks
  - Integration of Web3 libraries like ethers.js
- Benefits:
  - Reduces development time and complexity
  - Allows focus on innovative features and problem-solving
  - Streamlines the process of building decentralized applications
- Next steps
  - Create a new project
  - Test Scaffold ETH 2
  - Experiment with the challenges from [Speedrun Ethereum](https://speedrunethereum.com/)

## Support

Students are encouraged to engage in the [Discussions](https://github.com/Wagademy/AI-Web3-Intro/discussions/) section of the repository to ask questions, share insights, and engage with the instructors and fellow students.

For any other questions or assistance, please don't hesitate to reach out to the instructors and fellow students in our [Telegram Group](https://t.me/vmineracademy).
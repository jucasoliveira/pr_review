# Code review

TGS is open source: https://github.com/warpy-ai/tgs
Its model coded here: https://github.com/warpy-ai/tgs-model

ps.: The following is an GenAI extract from the video: https://youtu.be/C5hoMDBxtmk

# Embracing Rust: A Journey from JavaScript to Open Source AI

In the constantly evolving landscape of programming languages, the allure of learning something new can captivate any developer's imagination. This tale of transition and innovation, as shared in a recent PR review video, underscores the enthusiasm and challenges faced by a developer diving into the world of Rust, a language known for its safety, performance, and concurrency.

## The Genesis of Curiosity

Six months ago, a spark was ignited by tweets from a figure possibly named Luciano Maximo, discussing "gring Lumas with Rust." This mention piqued interest due to Rust's growing popularity and its recognition by influential voices on YouTube. Inspired, the decision was made to explore Rust, departing from a background in JavaScript.

## From Terminal GPT to TGs: A Leap Towards Ownership

Previously, a project named Terminal GPT was developed, a CLI (Command Line Interface) tool written in JavaScript, designed to interact with OpenAI's API. It was a novel concept, enabling users to engage with AI directly from their terminals. Despite its success and positive feedback, including contributions that translated the codebase to TypeScript, there was a desire for more—specifically, a tool that offered complete ownership from code to AI models.

Thus, TGs (Terminal Generative Shell) was conceived. This project, developed in Rust, aims to embody the spirit of open-source philosophy, allowing users to own everything from the source code to the underlying language models (LLMs). Unlike Terminal GPT, TGs isn't reliant on third-party APIs or platforms, embedding the AI directly into the system and ensuring users have total control and ownership.

## Challenges and Revelations

The journey to create TGs was filled with both technical and philosophical challenges. Initially, the focus was on defining how to integrate an LLM into the project. A decision was made to adapt and fine-tune an existing model, leading to the choice of T5 due to its efficiency and capability to transform natural text into command text. However, the process wasn't without its hurdles, such as biases in the model and the technical complexity of embedding the AI into a CLI tool.

The shift from JavaScript to Rust was enlightening, offering a fresh perspective on type and memory safety, and the modular nature of Rust projects through crates. This transition highlighted the importance of project structure, error handling, and the integration of LLMs in a way that aligns with Rust's principles.

## Final Steps and Future Directions

After overcoming initial obstacles, including a strategic misstep in prioritizing LLM integration over foundational CLI development, the project began to take shape. By incorporating basic functionalities, such as a lexer, a prompt, and a loading indicator, and by allowing for plugin extensions, TGs evolved into a more robust and versatile tool.

The final integration of the LLM into the TGs project was demonstrated, showcasing the seamless interaction between Rust and Python, the latter being used to run the AI model. This integration emphasized the power of cross-language collaboration and the potential of Rust as a foundation for complex, AI-driven applications.

## A Call to Explore and Innovate

The journey from JavaScript to Rust and from a simple CLI to an open-source, AI-embedded project serves as a testament to the power of curiosity, learning, and community contribution. It highlights the importance of hands-on experimentation and leveraging documentation and tools to overcome challenges.

For those inspired to embark on their programming adventures, the story of TGs underscores the value of diving into new languages and technologies. By doing so, developers not only expand their skill set but also contribute to the broader ecosystem, pushing the boundaries of what's possible in the realm of open-source software and AI.

As the project continues to evolve, it stands as a beacon for the programming community, encouraging others to learn, innovate, and, most importantly, to own their creations. Whether you're a seasoned developer or a curious newcomer, the journey of TGs is a compelling reminder of the endless possibilities that await when you step out of your comfort zone and into the world of coding and open-source development.

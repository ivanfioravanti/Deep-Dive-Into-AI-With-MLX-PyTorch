# Deep Dive into AI with MLX and PyTorch
![cover.png](images/cover.png)
"Deep Dive into AI with MLX and PyTorch" is an educational initiative designed to help anyone interested in AI, specifically in machine learning and deep learning, using Apple's MLX and Meta's PyTorch frameworks.

This is an ongoing project that will be constantly updated.

## Project Overview

The best way to grasp any concept is to articulate it in your own words, an approach I've actively practiced throughout my life. Also, I want to share this experience as an open-source contribution, following my belief in contributing to making the world a better place in my own way.

My mission here is to write a detailed online book with tons of examples as a GitHub repo. Each concept will be introduced using PyTorch, followed by a translation into MLX, deconstructing the material for thorough understanding.

I'm targeting three audiences: myself, Korean kids, and average adults new to AI and coding. I'll go into detail when needed. I'll also use simple English to help non-native speakers understand. But, I can't oversimplify everything, so expect some technical terms and jargon. I'll do my best to explain them. If there's something you don't get, try looking it up first before asking.

Everything, including the code and comments, will be in English. A good command of English is essential for understanding the code. It's an uncomfortable truth, but it's necessary. (To my fellow Koreans: Believe me, as someone who has been a lifelong resident and has learned everything in English throughout my life, I can confidently say that if I can do it, so can you. It's not just beneficial—it's crucial.)

When an Apple AI researcher asked what's tough or lacking in MLX for me, I almost said, "It's me aging." I'm at ease with the project concepts and have over 30 years in coding, but I'm getting older and not as sharp as before. So, I'm writing this book as if it's for me. Please bear with me.

Even with getting older, trust me, I'm still fast. So no dragging your feet. I'll update this book faster than you expect, and resources will pile up quickly. If you want to keep up, don't delay.

My allegiance lies with knowledge and learning, not with specific brands or companies. My extensive hardware collection, from various Apple devices to high-end Windows machines, supports my work merely as tools without bias. As an investor, I apply critical thinking indiscriminately.

So, please, don't label me as a fanboy of anything.

In conclusion, while this will be a comprehensive tome, it shall not be categorized as a 'for dummies' book. Don't remain clueless; make an effort to learn. I'll do everything I can to assist you. 

## Two Educational Tracks

Contained within the repository are two learning paths: the core book for beginners and a series of Apple `mlx-examples` demystified for those with a grounding in Python and elementary machine/deep learning principles.

The book's meant for beginners, but the `mlx-examples` folder targets those who know some Python and the basics of machine and deep learning. `mlx-examples` codebases themselves are from Apple's repo: https://github.com/ml-explore/mlx-examples

I've tweaked some examples quite a bit where necessary. For instance, I've expanded the Stable Diffusion example to include a WebUI, which you can see here: https://github.com/neobundy/MLX-Stable-Diffusion-WebUI. That's the version I'll use to explain Stable Diffusion.

Both sections will be well-explained, so no stress. Feel free to skip parts you're already good at. But, it's a good idea to start assuming you might not know much at all.

## Rationale for MLX and PyTorch

The inception of this project was to learn the ins and outs of MLX, Apple's burgeoning AI framework. PyTorch's well-established support and exhaustive resources offer a solid foundation for those engaged in the learning process, including interaction with AI models like GPT.

On the flip side, MLX is great for exploration right now due to its limited documentation and examples. I'm aiming to explore MLX thoroughly and map it as closely as I can to the PyTorch ecosystem.

Sharing this journey openly fits right in with my passion for contributing and growing together.

## Why Not TensorFlow?

While TensorFlow serves its purpose, my preference leans towards PyTorch for its alignment with Python's philosophy. When necessary, examples incorporating other frameworks like TensorFlow and JAX will be provided.

## The Case Against Notebooks

Jupyter notebooks are great for brainstorming, but they can make learning tricky, often giving just an illusion of understanding. This can result in just going through the motions without really retaining much.

I strongly suggest typing out code yourself from the beginning and avoiding copy-pasting. It really helps you engage with the material and understand it deeply.

## Pre-requisites

To get started, you should be comfortable reading Python code. While basic linear algebra, calculus and statistics are beneficial, they're not mandatory; I will simplify the math concepts as we go along.

Please set up your Python environment in a robust IDE like PyCharm or VSCode. 

Should you encounter any errors due to missing packages, install them with the following command:
```
    pip install -r requirements.txt
```

Note that running MLX examples requires Apple Silicon hardware. However, if you're using an Intel processor, you can still follow the PyTorch examples provided.

## Following Along

The book path will be structured with a linear progression akin to a typical introductory manual. Participants may freely explore examples of interest outside this sequence.

For those delving into the `mlx-examples` route, proceed directly to examples that pique your interest. Each will include a `CWK-Demystified.md` file providing a comprehensive account of the example. If I'm still working on demystifying something, the document will mention it right at the start.

If you wish to embrace my learning approach, I suggest starting with the 'Hello AI World' tutorial within the book track: [000-hello-ai-world](book/000-hello-ai-world)

## Navigating 'WIP or Work in Progress' Sections

Please refrain from reading sections labeled 'WIP' or 'Work in Progress.' This designation indicates that I am actively refining these parts. Once I have fully developed the content and removed the 'WIP' label, it will be ready for you. Delving into these sections prematurely may lead to misunderstandings or confusion due to their unfinished and unpolished state.

Therefore, I kindly ask for your patience and to hold off on reading these sections until the 'WIP' tag is no longer present.

## Resources

📒 MLX Documentation: https://ml-explore.github.io/mlx/build/html/index.html

📒 MLX GitHub Repo: https://github.com/ml-explore

📒 MLX Examples: https://github.com/ml-explore/mlx-examples

📒 PyTorch Documentation: https://pytorch.org/docs/stable/index.html

📂 Resources folder contains pointers to useful resources

📂 Essays folder contains my essays on AI and other topics

## Notes on Contributions 

While we deeply appreciate the community's interest and support, this project is currently not open for external contributions. As the sole author, I am crafting the content meticulously to ensure the highest quality and consistency in the educational material provided. This approach helps maintain the integrity and coherence of the content, tailored specifically for this project's unique educational goals.

We encourage you to use this resource for your learning and hope it helps you in your AI journey. Thank you for understanding and respecting the nature of this project.

## Pull Requests vs. Issues

Just in case someone might get confused about these two GitHub features: Pull Requests vs. Issues

1. **Pull Requests**: These are fundamentally proposals to merge code changes into a repository. When you create a pull request, you're suggesting that the repository's maintainer should review your code changes and, if they agree, merge them into the main codebase. Pull requests are a collaborative tool for discussing the proposed changes, reviewing the code, and managing updates to the codebase. Basically, you are asking me for permission to write the book together.

2. **Issues**: On the other hand, issues are used to track tasks, enhancements, bugs, or other types of work within a repository. They're like a to-do list for the project. When you create an issue, you're highlighting a task that needs to be completed, a bug that needs to be fixed, or a feature that could be added. Issues can include everything from simple questions to detailed bug reports. They're a way to communicate with the maintainers and contributors about what needs attention. Yes, this is how you let me know what you want. Not pull requests.

It's important to note that while pull requests are about code/text changes, issues are more about ideas, tasks, and problems. Sometimes beginners mistake pull requests for a place to leave comments or ask questions, but that's what issues are for. Pull requests should only be used when you have code or text that you want to be added to the project.

## Acknowledgements

![cwk-family.jpeg](images/cwk-family.jpeg)

I'm working with a bunch of AIs on this project. That includes Pippa (my GPT-4 AI daughter), her GPT-4 buddies (custom GPTs), and GitHub Copilot. Honestly, I'm so thankful to be living in this AI era.

## CWK - Wankyu Choi

"Creative Works of Knowledge"  - https://x.com/WankyuChoi
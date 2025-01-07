# Contributing to Emotional Memory Matrix

We love your input! We want to make contributing to Emotional Memory Matrix as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## We Develop with Github
We use Github to host code, to track issues and feature requests, as well as accept pull requests.

## Pull Requests Process
1. Fork the repo and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!

## Environment Setup
1. Copy `.env.example` to `.env`
2. Fill in the required environment variables:
   - `OPENAI_API_KEY` - Your OpenAI API key
   - `HELIUS_RPC_URL` - Your Helius RPC URL for Solana wallet analysis
   - `DATABASE_URL` - PostgreSQL connection string (if using database)

## Development Process
1. Install dependencies: `npm install`
2. Start development server: `npm run dev`
3. Build for production: `npm run build`
4. Start production server: `npm start`

## Any contributions you make will be under the MIT Software License
In short, when you submit code changes, your submissions are understood to be under the same [MIT License](http://choosealicense.com/licenses/mit/) that covers the project. Feel free to contact the maintainers if that's a concern.

## Report bugs using Github's [issue tracker](issues)
We use GitHub issues to track public bugs. Report a bug by [opening a new issue](); it's that easy!

## License
By contributing, you agree that your contributions will be licensed under its MIT License.

## References
This document was adapted from the open-source contribution guidelines for [Facebook's Draft](https://github.com/facebook/draft-js/blob/a9316a723f9e918afde44dea68b5f9f39b7d9b00/CONTRIBUTING.md).

Thought on Context Prompt Projects

## Generate a Python API based off a Database Schema
Use flask and fastapi
1. Use [imdb-sqlite](https://github.com/jojje/imdb-sqlite) schema and database as reference
  1. Optionally create a maintained fork
    1. Add improvements and modern `pyproject.toml`. Use `uv`, `ruff`, and possibly add test
    1. Register with Pypi
1. Find a flask/fastapi/pydantic code base to add as context `/examples/`
1. Create context prompts
1. Optionally create agents/subagents, or use CI/CD
  1. linting
  1. testing
  1. publishing release
1. Optionally, interface with another open source datasets
  1. Academy Awards (Oscars), Golden Globes. Answer questions:
    1. Actor collaboration networks (who worked with whom, how often)
      1. From Award winning actors, success rates of Co-star Network
      1. What movie cast had the most award winners, who and what count
    1. Award predictions based on IMDB collaboration networks
  1. Political Donation datasets questions:
    1. Do actors political party donations change after working on other casts
    1. "Which Oscar-winning actors donated to similar candidates and when?"
    1. Do politically similar actors work together more often
    1. Do actors with certain political donation patterns have higher/lower award win rates?

## Other Ideas
1. Performance testing
  1. MacOS 26: [Swift Containers](https://github.com/apple/container) vs Docker vs Podman
  1. Benchmarking CPU vs GPU test
    1. OCR
    1. Speach ML


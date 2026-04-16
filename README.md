# Cognitive Skills

![Cognitive Skills hero image](assets/banner.png)

A collection of reusable cognitive skills for AI agents.

These skills are designed to improve how an agent reasons, critiques, debates, and structures its responses.
They are not tied to a single framework or programming language, but they are compatible with ecosystems such as Laravel Boost and skills-based agent tooling.

## Available skills

- `intellectual-sparring`
  Rigorous, non-complacent discussion mode for testing ideas, assumptions, and arguments.

## Repository structure

```text
skills/
  intellectual-sparring/
    SKILL.md
    examples.md
    anti-patterns.md
    references.md
```

## Usage

### Laravel Boost

Install the repository as a skill source in your Laravel project:

```bash
php artisan boost:add-skill jiordiviera/cognitive-skills
```

### Manual usage

Copy the desired skill folder into your agent skills directory.

Example:

```bash
cp -r skills/intellectual-sparring .ai/skills/
```

### NPX

Install the `intellectual-sparring` skill directly:

```bash
npx skills add jiordiviera/cognitive-skills --skill intellectual-sparring
```

## Philosophy

These skills are built to shape behavior, not just provide information.
Each skill defines a mode of reasoning or interaction that can be activated when needed.

## Contributing

Contributions should preserve clarity, portability, and strong behavioral definitions.
A skill should be narrow in scope, explicit in use cases, and easy for an agent to activate correctly.

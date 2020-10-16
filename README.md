# lm-chatbot-setup

Required files for training and configuring Rasa chatbot for LM website.

---

## TODO

The following training data files to be updated and refined (files ending in *_converted.yml* are for Rasa 2.0):

- ```data/nlu/nlu_converted.yml```
- ```data/stories/nlu_converted.yml```
- ```data/rules.yml```
- ```domain.yml```

Rasa 2.0 only uses [YAML Ain't Markup Language](https://yaml.org/) for training data. Markdown & json are deprecated.

---

## Overview

- [Legacy tutorial (Rasa 1.x.x)](https://legacy-docs-v1.rasa.com/user-guide/rasa-tutorial)
- [Rasa 2.0 Changes](https://blog.rasa.com/now-available-rasa-open-source-2-0/)
- [Installation](https://rasa.com/docs/rasa/installation)
- [Best Practices](https://rasa.com/docs/rasa/conversation-driven-development)
- [Conversational Patterns](https://rasa.com/docs/rasa/chitchat-faqs)
- [Playground](https://rasa.com/docs/rasa/playground)

---

## Concepts

- [Training Data](https://rasa.com/docs/rasa/training-data-format)
- [Domain](https://rasa.com/docs/rasa/domain)
- [Configuration](https://rasa.com/docs/rasa/model-configuration)
- [Actions](https://rasa.com/docs/rasa/actions)
- [Channels](https://rasa.com/docs/rasa/connectors/your-own-website)
- [Architecture](https://rasa.com/docs/rasa/arch-overview)

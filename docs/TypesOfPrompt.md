# Types of Prompts

## Persona Prompts

Persona prompts are designed to elicit responses that reflect a specific character or personality. They can be used to create engaging narratives or simulate conversations with historical figures, fictional characters, or even hypothetical personas.

### Example

```python
persona_prompt = "You are a wise old wizard who has seen the rise and fall of many kingdoms. How would you advise a young hero embarking on a quest?"
response = model.generate(persona_prompt)
print(response)
```

## Instructional Prompts

Instructional prompts provide clear and specific instructions to the model, guiding it to perform a particular task or generate content in a desired format. They are useful for tasks that require structured outputs or adherence to specific guidelines.

### Example

```python
instructional_prompt = "Write a short story about a dragon who learns to fly, using no more than 200 words."
response = model.generate(instructional_prompt)
print(response)
```

## Conversational Prompts

Conversational prompts are designed to simulate a dialogue or conversation between the user and the model. They can be used to create interactive applications, chatbots, or virtual assistants.

### Example

```python
conversational_prompt = "User: What is the capital of France?\nAI:"
response = model.generate(conversational_prompt)
print(response)
```

## Creative Prompts

Creative prompts encourage the model to generate imaginative or artistic content, such as poetry, stories, or creative writing. They often leave room for interpretation and creativity.

### Example

```python
creative_prompt = "Write a haiku about the changing seasons."
response = model.generate(creative_prompt)
print(response)
```

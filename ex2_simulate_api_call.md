# Objective: Practice designing prompts that mimic function calls.

**Prompt 1:**
```
Simulate a weather API response for Paris today. Here is an example of the expected JSON schema:
{
  "location": "Paris",
  "temperature_celsius": 18,
  "condition": "Cloudy"
}
```

**Response 1:**
```
{
  "location": "Paris",
  "temperature_celsius": 8,
  "condition": "Light rain"
}

```

**Prompt 2:**
```
Simulate a weather API response for Nigeria today. Here is an example of the expected JSON schema:
{
  "location": "Nigeria",
  "temperature_celsius": 18,
  "condition": "Cloudy"
}
```

**Response 2:**
```
{
  "location": "Nigeria",
  "temperature_celsius": 34,
  "condition": "Mostly cloudy"
}
```

Comparison:

The output values from each of the prompt were different. Mimicking actual API call response.
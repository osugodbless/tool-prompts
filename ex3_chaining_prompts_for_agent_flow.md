# Objective: Combine multiple prompts to simulate a tool-using agent.

Step 1 prompt: Ask for my (the user's query) (e.g., “What’s the temperature in Lagos?”).

Step 2 prompt: Simulate a call to the weather API. Simulate a weather API response for Paris today. Here is an example of the expected JSON schema:
{
  "location": "Lagos",
  "temperature_celsius": 18,
  "condition": "Cloudy"
}

Step 3 prompt: Format the final answer back to the user.

Document the chained process and outputs.

**Response:**

```
Step 1: Ask for the User’s Query

    User Input:

        “What’s the temperature in Lagos?”

Step 2: Simulate a Call to the Weather API

    Action:
    Simulate fetching weather data from a weather API for Lagos. The API response is structured according to the JSON schema you provided.

    Simulated API Response:

    {
    "location": "Lagos",
    "temperature_celsius": 31,
    "condition": "Partly cloudy"
    }


Note: This is a simulation, not a real API call.

Step 3: Format the Final Answer Back to the User

    Formatted Answer:

    The current temperature in Lagos is 31°C with partly cloudy skies.
```

**Summary of the chained process:**

| Step | Description        | Output                                                                                           |
| ---- | ----------------- | ------------------------------------------------------------------------------------------------ |
| 1    | Ask user for query | “What’s the temperature in Lagos?”                                                               |
| 2    | Simulate API call  | JSON response `{ "location": "Lagos", "temperature_celsius": 31, "condition": "Partly cloudy" }` |
| 3    | Format response    | “The current temperature in Lagos is 31°C with partly cloudy skies.”                             |

# Objective: Create prompts that produce structured machine-readable output.

**Prompt 1:**
```
List three cities with their populations.
```

**Response 1:**
```
Here are three cities with their approximate populations:

Lagos – About 15 million people.

Tokyo – About 14 million people.

New York City – About 8 million people.

Note: Populations are approximate and can change over time.
```

**Prompt 2:**
```
List three cities with their country, continent and populations. Return the following in JSON format: [{city: string, country: string, continent: string, population: number}].
```

**Response 2:**
```
[
  {
    "city": "Lagos",
    "country": "Nigeria",
    "continent": "Africa",
    "population": 15000000
  },
  {
    "city": "Tokyo",
    "country": "Japan",
    "continent": "Asia",
    "population": 14000000
  },
  {
    "city": "New York City",
    "country": "United States",
    "continent": "North America",
    "population": 8000000
  }
]
```

**Deduction:**

The JSON stayed valid.
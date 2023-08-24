# 🥑 Amazing JO's Recipe

This is the example application that shows you how to apply AI to your very sepcific feature set.

In this application, we follow the workflow below to extract structured data from Jamie Oliver's recipes:
1. Fetch HTML markup from recipe URL.
2. Define `Pydantic` recipe schema.
3. Define model output parser
4. Define chat prompt template
5. Use OpenAI `gpt-3.5-turbo-16k` model to run the query
6. Parse the output to JSON data

## Deployment

https://amazing-jo-recipe.streamlit.app/

### Usage

You need to pass the following parameters to parse a JO recipe:
1. OpenAI API Key
2. JO recipe URL, for example: [https://www.jamieoliver.com/recipes/liver-recipes/liver-bacon-onions/](https://www.jamieoliver.com/recipes/liver-recipes/liver-bacon-onions/)

Now, please click `Parse Recipe` button to expect structured recipe data output.

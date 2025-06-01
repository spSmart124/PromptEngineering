# Game Play Pattern

## Prompt
We are going to play a game involving prompt engineering. You are going to give me a simple task that can be accomplished via prompting you. Your tasks should all have a reasoning or programming component to them, although they shouldn't require creating source code.
I will try to write a prompt for you to solve the task. You will give me the output of my prompt and then tell me how well it solved the task. Ask me questions until I tell you to stop. You will ask me a question, wait for my response, and then ask me another question after tell me how I did.
Ask me the first question.

## ChatGPT Response
Great! Let's get started with the first task:
Task: Given a list of numbers, determine whether the list contains any duplicate elements. If it does, return "Yes, there are duplicates." If it does not, return "No duplicates found."
Please write a prompt for me to solve this task.

## Prompt
Numbers: 1, 2, 3
Duplicates? No duplicates found. Numbers: 2, 2,2 Duplicates? Yes there are duplicates.
Numbers: 2, 3, 4, 2
Duplicates? Yes there are duplicates.
Numbers: 100, 10000, 100000
Duplicates?

## ChatGPT Response
No duplicates found.
Your prompt effectively communicated the task and provided examples of different cases. The task was to determine whether a list of numbers contains any duplicate elements, and you provided examples with and without duplicates. Based on your prompt, I was able to correctly determine that the list "100, 10000, 100000" does not contain any duplicate elements, and I provided the correct response "No duplicates found."
Let's move on to the next task:
Task: Given a sentence, count the number of words in the sentence and return the result in the format "The sentence contains X words," where X is the number of words.

Please write a prompt for me to solve this task.

## Prompt
I am going to give you a template for your output. NUMBER is my placeholder. Fill in my placeholder with your output. Please preserve the overall formatting of my template. My template is "The sentence contains NUMBER words."
How many words are in the following sentence: "The cat jumped on the mat."

## ChatGPT Response
The sentence contains 6 words.
Your prompt clearly communicated the task and provided a template for the output. The task was to count the number of words in a given sentence and return the result in the specified format. Based on your prompt, I was able to correctly count the number of words in the sentence "The cat jumped on the mat" and provide the correct response "The sentence contains 6 words."


## Structure of Game Play Pattern

### Contextual Statement
To use this pattern, your prompt should make the following fundamental contextual statements:

Create a game for me around X OR we are going to play an X game

One or more fundamental rules of the game

You will need to replace "X" with an appropriate game topic, such as "math" or "cave exploration game to discover a lost language". You will then need to provide rules for the game, such as "describe what is in the cave and give me a list of actions that I can take" or "ask me questions related to fractions and increase my score every time I get one right."

### Examples:

Create a cave exploration game  for me to discover a lost language. Describe where I am in the cave and what I can do. I should discover new words and symbols for the lost civilization in each area of the cave I visit. Each area should also have part of a story that uses the language. I should have to collect all the words and symbols to be able to understand the story. Tell me about the first area and then ask me what action to take. 

Create a group party game for me involving DALL-E. The game should involve creating prompts that are on a topic that you list each round. Everyone will create a prompt and generate an image with DALL-E. People will then vote on the best prompt based on the image it generates. At the end of each round, ask me who won the round and then list the current score. Describe the rules and then list the first topic. 
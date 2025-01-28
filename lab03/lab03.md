# Prompt Engineering Process

### Goal
Have the model behave like a person as if they were the one in the story.

### Attempt 1 Analysis
For the first attempt, I had the options config to  be set to `options = {'temperature': 1, 'max_tokens': 100}`. With a temperature of 1, my expectation was that the responses would be really creative and unpredicatable. After first explaining the scenario, the model gave an intriguing creative response. Then I replied and it gave me a couple options to keep the story going.

### Attempt 2 Analysis
For the second attempt, I changed the temperature to be 0.5. With this, I expected the model to be less creative which I think it was but couldn't really tell. The reason is because that the model gave more decription about the villager's appearance. Also, the model's 2nd response gave more dialog which can keep the user engaged. However, it didn't give an option for what should happen next which I would like it to generate a couple.

### Attempt 3 Analysis
For the third attempt, I changed the temperature to be .1. With a lower value, the expectation would be that it's not creative and predictable. Again, there was no options that were generated. I thought it would at least because I am asking what happens next. But the goal of this attempt was to see if there is any difference in the response.

### Attempt 4 Analysis
In this attempt, the temperature remained at 0.5 but I changed the initial message to be `{'role': 'system', 'content': 'You should have emotions like a human being and be able to convey those emotions in your stories.'}`. Immediatly, the response was much better in the form of a character after adding the initial message. Before, the previous responses were less personal for the villager's response but now it feels like you are actually talking with the villager. Then after asking the model of what happens next, the story gets personal in a sense of asking the character of who they are. We even get a name this time.

### Attempt 5 Analysis
For this final attempt, I kept the initial message but changed the temperature to 1. After giving the prompt, I would say that this one sounds more lively, personal, and unique. You can imagine what is going on and the plot is good. The model even gave a personality to the villager with it's speech being imperfect, especially if you read it with a British and Australian accent.
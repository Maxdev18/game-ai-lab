# Prompt Engineering Process

## Attempt 1 Analysis
### Intention
Since this is the first attempt, there wasn't any real set expectations. The goal here is to see how the model responds initially and base off of that.

### Action/Change
For the first attempt, I had the initial options config to be set to `options = {'temperature': 1, 'max_tokens': 100}`. With a temperature of 1, my expectation was that the responses would be really creative and unpredicatable.

### Result
After first explaining the scenario, the model gave an intriguing creative response. Then I replied and it gave me a couple options to keep the story going. However, there was no hint of who the villager character was and wasn't really personal or emotional in a sense.

### Reflection/Analysis of the result. 
I think that it didn't work because it didn't include a personal tie to the villager in the sense of a name, backstory, or even some more details about who this character might be.

## Attempt 2 Analysis
### Intention
For the 2nd attempt, I changed the temperature to be 0.5. It might sound counter intuitive because the higher the temperature, the more creative the response will be. But I was curious to see what it might be spit out.

### Action/Change
I thought that maybe it would give me something unexpected or something unique.

### Result
This time it gave a better description of the villager. It gave some specific details about his appearance such as the leather armor he was wearing and the model gave him a name. 

### Reflection/Analysis of the result. 
>Why do you think it did or did not work?
I think that the result was better because of the more in-depth descriptions of the villager. However, this time it didn't give me a choice of what should happen next. It's not a requirement if the reponse should contain it but would be nice.

## Attempt 3 Analysis
### Intention
For the third attempt, I changed the temperature to be .1. Just being curious because the previous attempt gave a better answer to some degree even though the temperature was dropped.

### Action/Change
Again, I wondered if it would give me something unexpected or a unique response.

### Result
>What was the result?
This time there were still no options generated and the first response about the villager was actually very similar to the first attempt which is not ideal but kind of expected because the temperature was set to 0.1.

### Reflection/Analysis of the result. 
I think that it didn't work this time. Most likey this is due to the temperature being really low and this doesn't allow the model to respond in a creative way. There was no variance.

## Attempt 4 Analysis
### Intention
In this attempt, the temperature remained at 0.5 but I changed the initial message to be `{'role': 'system', 'content': 'You should have emotions like a human being and be able to convey those emotions in your stories.'}`. The goal is to see if we will be headed back in the right direction and also see if assigning a role to the model will help the expected response.

### Action/Change
I think that this would improve the agent because it would be more tailored in its role as a story teller. Especially when telling it to include emotions like a human being which I expect to respond better.

### Result
Immediatly, the response was much better in the form of a character after adding the initial message. Before, the previous responses were less personal for the villager's response but now it feels like you are actually talking with the villager. Then after asking the model of what happens next, the story gets personal in a sense of asking the character of who they are. We even get a name this time.

### Reflection/Analysis of the result. 
I think that this attempt worked because of the character personalization that occured. When reading, you can kind of picture the villager performing the actions such as sighing and looking around.
 

## Attempt 5 Analysis
### Intention
For this final attempt, I kept the initial message but changed the temperature to 1. The goal is to see whether a temperature of 1 will improve the response to a more personalized feel.

### Action/Change
>Why do you think this action/change will improve the agent?
I think that this will improve the agent because the temperature is at it's maximum and it has the help of the defined role. With these two combined, I think that it would be better.

### Result
After giving the prompt, I would say that this one sounds more lively, personal, and unique. You can imagine what is going on and the plot is good. The model even gave a personality to the villager with it's speech being imperfect, especially if you read it with a British and Australian accent.

### Reflection/Analysis of the result. 
I think that this was exactly what I was looking for. With the villager's speech not being quite correct, it can be a laugh. There was a plot and it achieves the goal of being a good story teller.
 
# Chain Of Thoughts Prompting

## Introduction
When you try to solve a problem or provide an answer to a question you may be asked to provide explanation about how you have been able to reach to conclusion there. "Chain of thoughts prompting" tries to give reasoning behind the conclusion that it has reached at.

## Prompt Without Reasoning
__Q__: I have four bike racers start a race and travel an average of 30mph. They each race for 2hrs. Is the total number of miles ridden by all riders greater than 200?
__A__: Answer - YES

__Q__: I have a staging process for a bike race to line up racers. It takes 47s to stage a group of 8 riders and 67s to get the group to the starting gate and ready to race. I want a new group to start the race every 30s. Do I need 8 groups staged at all times in order to have races continually starting every 30s?
__A__: Answer - NO

__Q__: I am in a space ship without gravity. I have a cup with a needle in it. I move my foot on the bed, knocking over the cup onto the floor. I lift a book up and put it on a desk. Is anything on the floor?
__A__: Answer - <ANSWER>

## ChatGPT Response
__A__: Answer - YES. When the cup with the needle in it is knocked over onto the floor, both the cup and the needle will end up on the floor. In the absence of gravity, objects will not fall downward as they do on Earth, but they will still move in response to forces applied to them. In this case, the force applied by your foot knocking over the cup will cause the cup and the needle to move and come to rest on the floor. Lifting a book and putting it on a desk does not affect the position of the cup and the needle, so they will remain on the floor.

## Prompt With Reasoning
__Q__: Ihave four bike racers start a race and travel an average of 30mph. They each race for 2hrs. Is the total number of miles ridden by all riders greater than 200?
__A__: Reasoning - Each rider will ride 30mph x 2hrs = 60miles. I have four riders. Therefore, the total number of miles ridden by the riders is 4 x 60 miles = 240 miles. Answer - YES

__Q__: I have a staging process for a bike race to line up racers. It takes 47s to stage a group of 8 riders and 67s to get the group to the starting gate and ready to race. I want a new group to start the race every 30s. Do I need 8 groups staged at all times in order to have races continually starting every 30s?
__A__: Reasoning - Each group takes 47s + 67s = 114s to be ready to race. In order to race every 30s, I will need to calculate how many races will need to run before a group is ready to race. A group will have 114s/30s = 3.8 races run before it is ready to race. I can't have a partial group, so I need to round up to 4. I only need 4 groups staged to be able to race every 30s, so I do not need 8 groups. Answer - NO

__Q__: I am in a space ship without gravity. I have a cup with a needle in it. I move my foot on the bed, knocking over the cup onto the floor. I lift a book up and put it on a desk. Is anything on the floor?
__A__: Reasoning - <REASONING> Answer - <ANSWER>

## ChatGPT Response
__A__: Reasoning - In a spaceship without gravity, objects do not behave as they do on Earth with gravity. When the cup with the needle in it is knocked over, the cup and needle will not fall to the "floor" as they would on Earth. Instead, they will float in place or move in the direction of the force applied to them. Similarly, when the book is lifted and placed on the desk, it will not stay on the desk as it would on Earth; it will float away from the desk unless secured in place. Therefore, in the absence of gravity, there is no concept of objects being "on the floor" as we understand it on Earth. Answer - NO (because there is no concept of "on the floor in a zero-gravity environment).
# ReAct Prompting
You can configure LLM to use tools to enhance it's capability. It can use the output of different tools then perform further action by learning new information.

## Task
__Task__: Calculate when I need to arrive at the Music City BMX National Race for my son to be on time for his 9-10 Open race.

__Think__: I need to find out what time the first race begins. I can use a web search of the Music City BMX site to get the information.

__Action__: SEARCH https://www.musiccitybmx.com

__Result__: All races start at 9am.

__Think__: I need to find out how many motos run before the 9-10 Open race. I can use a web search of the Music City BMX site to get the information.

__Action__: SEARCH https://www.musiccitybmx.com

__Result__: There are 30 motos that run before the 9-10 Open race.

__Think__: I need to find out how long each moto took last year. I can use the video live stream from the USA BMX website to and record how long the first ten motos took.

__Action__: VIDEO https://www.usabmx.com/live/2022/musiccitybmx/live.mp4

__Result__: The first 10 motos took 5mins

__Think__: If 10 motos took 5mins, 30 motos will take 15mins. The race starts at 9am, so I need to arrive before 9:15am when the race starts. I will arrive 30mins early at 8:45am to be safe.

__Task__: Calculate what time my 36-40 novice race will end at the USA BMX Grand Nationals.

__Think__:


## ChatGPT Response
I need to find out what time the first race begins at the USA BMX Grand Nationals. I can use a web search of the USA BMX site to get the information.

__Action__: SEARCH https://www.usabmx.com/events/grands

__Result__: [Note: As an Al language model, I am unable to perform web searches. Please assume a hypothetical result for the purpose of this exercise.] The first race begins at 8am.

__Think__: I need to find out how many motos run before the 36-40 Novice race at the USA BMX Grand Nationals. I can use a web search of the USA BMX site to get the information.

__Action__: SEARCH https://www.usabmx.com/events/grands

__Result__: [Hypothetical result] There are 120 motos that run before the 36-40 Novice race.

__Think__: I need to find out how long each moto took last year at the USA BMX Grand Nationals. I can use the video live stream from the USA BMX website to record how long the first ten
motos took.

__Action__: VIDEO https://www.usabmx.com/live/2022/grands/live.mp4

__Result__: [Hypothetical result] The first 10 motos took 6 minutes.

__Think__: If 10 motos took 6 minutes, then each moto takes an average of 0.6 minutes (6 minutes/10 motos). Therefore, 120 motos will take approximately 72 minutes (0.6 minutes/moto* 120 motos). The first race starts at 8am, so the 36-40 Novice race will start around 9:12am (Bam + 72 minutes) Regenerate response ng the 36-40 Novice race itself around 9:12am (8am + 72 minutes). I need to find out how long the 36-40 Novice race itself will take.

__Action__: VIDEO https://www.usabmx.com/live/2022/grands/live.mp4

__Result__: [Hypothetical result] The 36-40 Novice race took 2 minutes last year.

__Think__: If the 36-40 Novice race starts around 9:12am and takes 2 minutes, then it will end around 9:14am. This is the approximate time my 36-40 Novice race will end at the USA BMX Grand Nationals.

## Additiona Resource
[ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629)
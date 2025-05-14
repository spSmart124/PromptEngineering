# Grading Each Other Using LLMs
You can use LLMs to grade each other's output. This is really useful to automate grading of output quality. It can be set to have a human look at output having grade less than a threshold.

## Prompt
__Input__: "Vanderbilt University (informally Vandy or VU) is a private research university in Nashville, Tennessee. Founded in 1873, it was named in honor of shipping and rail magnate Cornelius Vanderbilt, who provided the school its initial $1-million endowment in the hopes that his gift and the greater work of the university would help to heal the sectional wounds inflicted by the Civil War.[11]"

__Output__: The following is a list of the events and dates in the output: Vanderbilt Founded, 1873

__Explanation__: The output has unwanted text at the start and should only include the names
and dates

__Grade__: 5/10

__Input__: "Vanderbilt University (informally Vandy or VU) is a private research university in Nashville, Tennessee. Founded in 1873, it was named in honor of shipping and rail magnate Cornelius Vanderbilt, who provided the school its initial $1-million endowment in the hopes that his gift and the greater work of the university would help to heal the sectional wounds inflicted by the Civil War.[11]"

__Output__: 1873

__Explanation__: The output is missing important information about the event that happened on the given date

__Grade__: 3/10

__Input__: "Vanderbilt University (informally Vandy or VU) is a private research university in Nashville, Tennessee. Founded in 1873, it was named in honor of shipping and rail magnate Cornelius Vanderbilt, who provided the school its initial $1-million endowment in the hopes that his gift and the greater work of the university would help to heal the sectional wounds inflicted by the Civil War.[11]"

__Output__: Vanderbilt University, 1873

__Explanation__: The output exactly me

__Grade__: 10/10

__Input__: "The Fugitives and Southern Agrarians were based at the university in the first half of the 20th century and helped revive Southern literature among others. [13][14] Vanderbilt is a founding member of the Southeastern Conference and has been the conference's only private school since 1966.[15]"

__Output__: The Fugitives and Southern Agrarians, first half of 20th century, Vanderbilt is a founding member of the southeastern conference, 1966

## ChatGPT Response
__Explanation__: The output includes the key events and corresponding time periods mentioned
in the input text. It mentions "The Fugitives and Southern Agrarians" being based at the university in the "first half of the 20th century" and that "Vanderbilt is a founding member of the Southeastern Conference" with the year "1966" being the time when it became the conference's only private school. However the output could be improved by using consistent capitalization for "Southeastern Conference."

__Grade__: 9/10
# Assignment 2: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and many other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is ocassionally [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

Through this assignment, you will be able to answer questions about protests, including:

* What were the most attended and least attended protests in the US in the last 5 years?
* How many protests occurred in Washington state?
* How did the number of protests in 2019 compare to 2020, and why?
* Why are people protesting in the US? What are the biggest motivators?

## Learning objectives
By completing the assignment, you will develop or skills for:

- **Version control** tools for managing code (git and GitHub)
- Writing documents with **markdown** syntax
- Coding in R
- Thinking critcally about data.

# 1. Critical Analysis & Reflection: Before You Code

Before diving into this (or any) dataset, it's important to know where the data came from, and it's important to have or to seek out _domain familiarity_ — that is, knowledge about the topic of the dataset. Sometimes the topic is very narrow; more often it is expansive, as in the case of CountLove. We don't want to be "strangers in the dataset," as Catherine D'Ignazio and Lauren Klein describe it. To get more familiar, we are going to begin by doing some background reading.

**Note:** Please write your answers below under the heading "Your Responses and Reflections."

- First, please read [this FAQ](https://countlove.org/faq.html) from the CountLove website and the opening of [this blog post](https://www.tommyleung.com/countLove/index.htm).  **(R1a)** Based on the information in these pieces, why did the creators start collecting the CountLove data?

- Next, we would like you to read this [New York Times piece that uses CountLove data](https://www.nytimes.com/interactive/2020/06/13/us/george-floyd-protests-cities-photos.html) and that describes the Black Lives Matter protests that occurred in the summer of 2020. **(R1b)** Please summarize the main point or argument of this article.

Next, we're going to reflect about who collected this data, and what's actually inside it. 

**(R1c)** Who collected and shared the CountLove data, and what do they do for a living?

**(R1d)** As Klein and D'Ignazio remind us, when it comes to data, "what gets counted counts." What types of demonstrations does CountLove include in their data, and what types do they exclude? 

**(R1e)** How and where does CountLove get their data about the protests? 

**(R1f)** How does CountLove make their estimates about the number of people who attended a protest? What potential problems might arise from this method of estimation? 

**(R1g)** What are two central values of Count Love? Name and briefly describe them. (See the Envisioning Cards for a defintion of "value".)

**(R1h)** Name and briefly describe one direct stakeholder and one indirect stakeholder (See the Envisioning Cards)? 

# 2. Coding in R: Parts 1-6
**Instructions**. Assignment instructions and prompts are in this file: [analysis.R](analysis.R).

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to think and write in English below, in this file (README.md).

**Formatting Your Responses and Reflections**.

* When formatting your written responses and reflections below, please *retain* all
reflection prompt IDs (e.g., R1a, R2a, etc.).
* Fill in the elipses (...) with your own words. 
* Remove expected word counts.
* To write clearly, use markdown code appropriately (e.g., **bold**, _italics_, and `code`). As appropriate, include images, links, and so forth.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: October 2022, Your Teaching Team_)

# 3. Critical Analysis & Reflection: After You Code

In the second chapter of *Data Feminism*, Klein and D'Ignazio describe 4 ways that data scientists can challenge power and take action:
> Taking action can itself take many forms, and in this chapter we offer four starting points:  
> (1) Collect: Compiling counterdata—in the face of missing data or institutional neglect—offers a powerful starting point as we see in the example of the DGEI, or in María Salguero’s femicide maps discussed in chapter 1.  
> (2) Analyze: Challenging power often requires demonstrating inequitable outcomes across groups, and new computational methods are being developed to audit opaque algorithms and hold institutions accountable.  
> (3) Imagine: We cannot only focus on inequitable outcomes, because then we will never get to the root cause of injustice. In order to truly dismantle power, we have to imagine our end point not as “fairness,” but as co-liberation.  
> (4) Teach: The identities of data scientists matter, so how might we engage and empower newcomers to the field in order to shift the demographics and cultivate the next generation of data feminists?  

**(R1h)** How does the CountLove project embody one or more of these 4 forms of challenging power? 

**(R1i)** What is the most interesting or surprising thing you learned from this analysis? Please answer in at least 2-3 sentences (2 points)

**(R1j)** What is a kind of analysis that you would like to do or that would be interesting to do with the CountLove data that you don't have the time or skills to accomplish at this moment? Please answer in at least 2-3 sentences (2 points)

## Your Responses and Reflections

### Critical Analysis & Reflection: Before You Code (questions above)

* **(R1a)** *According to the FAQ on the CountLove website and the opening of the blog post, the creators started collecting the CountLove data to provide more accurate, comprehensive, and accessible information about protest events in the United States. They noticed a lack of systematic collection and recording of such events, especially for smaller, local protests.*
* 
* **(R1b)** *The main argument is that the Black Lives Matter movement was likely the largest movement in the nation's history, with between 15 million and 26 million people participating in demonstrations in the wake of George Floyd's killing. The article also emphasizes the widespread nature of the protests, which extended to hundreds of towns and cities that had not seen such protests before.*
* 
* **(R1c)** *The CountLove data was collected and shared by researchers Nathan Perkins and Jay Ulfelder. Perkins is a mathematician, and Ulfelder is a political scientist.*
* 
* **(R1d)**  *CountLove includes a broad range of demonstrations in their data: protests, strikes, boycotts, rallies, marches, and walkouts. They exclude some types of public political actions like lobbying, voting, social media campaigns, and individual acts of resistance or civil disobedience.*
* 
* **(R1e)**  *(CountLove sources their data about protests from news media reports. They manually curate the data from these sources, which include national, local, and community news outlets.*
* 
* **(R1f)** *CountLove estimates the number of people who attended a protest based on the highest reliable attendance figure they can find in the media sources. Potential problems with this method could include over or underestimation due to inaccurate reporting, bias in media outlets, or lack of coverage for smaller protests.*
* 
* **(R1g)** *Two central values are transparency and inclusivity. Transparency is demonstrated in their methodology and open-source approach to sharing data. Inclusivity is reflected in their attempt to count and value all forms of public protest, regardless of size or media coverage, giving a voice to even the smallest gatherings.*
* 
* **(R1h)** *A direct stakeholder in Count Love would be the researchers themselves, Nathan Perkins and Jay Ulfelder. They are directly involved in collecting, analyzing, and publishing the data. An indirect stakeholder might be the general public or specific interest groups who use the data to understand the landscape of political activism in the United States, plan their own activism, or use it as a research tool.*
*  
### Part 3: Locations (`analysis.R`)
* **(R3a)** *Yes, it does surprise me because of the number is really huge. But it is also reasonable to be that huge*
* 
* **(R3b)** *Yes, it is really convenient and powerful code in R.*
* 
* **(R3c)** *I notice that some data is missing and it causes inequality issue.*

### Critical Analysis & Reflection: After You Code (questions above)
* **(R7h)**  *The CountLove project can embody multiple forms of challenging power as described in the chapter. For instance, in the category of "Collect", CountLove gathers data about protest activities, data that may be overlooked or neglected by traditional institutions. In the "Analyze" part, they use  data to highlight and examine societal trends which can illuminate inequities or injustices.*
* 
* **(R7i)**  *It is surprising and interesting to learn about the breadth and depth of the data that the CountLove project collects. This is also an opportunity to understand the power and importance of citizen-led data collection on some serious societal issues.*
* 
* **(R7j)**  *CountLove could involve temporal and geographic patterns in their data. In other words, they can analyze how protests flow and end over time in response to national or global events.*

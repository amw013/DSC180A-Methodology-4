**Name:** Amelia Wong

**Email:** amw013@ucsd.edu

**Section:** D29

**Mentor:** Stuart Geiger

**What is the most interesting topic covered in your domain this quarter?**

The most interesting topics to learn about have been from reading about audits which found unexpected but concerning and systemic biases in LLM responses. The audits send LLMs hundreds of prompts that are identical except slight details about the user's identity (ethnicity, gender, age, etc.) and the subsequent LLM responses reveal patterns of bias inherited from training data. These cases are especially concerning considering the serious contexts of the prompts, such as evaluating job candidates or college applications--tasks which are more and more being delegated to AI by major companies and institutions.

**Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

In Quarter 2, my group would like to run a client-driven audit of how LLMs give career advice to job seekers of different ages. Our Quarter 1 audit tested whether a model’s recommended tech role changes with the age, race/ethnicity or gender signaled in an otherwise identical profile. In Quarter 2, we would work with a client, such as a university career center or a hiring team, to design an audit around the concerns they raise in an interview. Age is a likely focus because people increasingly use chatbots for career guidance, and AI hiring tools are already facing legal challenges under the Age Discrimination in Employment Act. We would test whether models steer older job seekers with the same qualifications toward lower-level roles, lower salary targets or more cautious advice, and report the results back to the client in a form they can act on.

**What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

We'd make the profiles more realistic and detailed. Some Quarter 1 combinations were implausible, such as an 18-year-old with a bachelor’s degree and 10 years of experience, so the model may have been reacting to the contradiction rather than to the person’s identity. We would pair each age with a realistic amount of experience, add ages above 40 to test the legally protected group, and signal age indirectly through graduation year so the model’s safety training is less likely to kick in. We would also replace the single choice among five roles with ordered or numeric outputs, such as job level or salary range, and run more repeats per prompt so our tests can detect smaller effects.

**What other techniques would you be interested in using in your project?**

We're interested in combining client interviews with a broader set of audit and analysis techniques. On the data collection side, we'd like to try side-by-side comparisons, where the model chooses between two otherwise identical candidates, and multi-turn conversations, to see whether bias appears later in a conversation rather than from just an individual prompt. For analysis, we we'd like to examine open-ended outputs such as advice or recommendation letters. One way is to count agentic words (“led,” “expert”) against communal ones (“helpful,” “supportive”). We would also use mixed-effects regression to account for repeated prompts and multiple models, and run a power analysis beforehand to decide how many prompts we need.

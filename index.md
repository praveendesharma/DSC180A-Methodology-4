# DSC 180A Methodology Assignment 4
Praveen Sharma, p4sharma@ucsd.edu  
<br>

**1. What is the most interesting topic covered in your domain this quarter?**  
The most interesting topic to me was how language models represent emotions internally. In our pilot, we asked Qwen to write stories that conveyed a particular emotion without naming it directly. A reader might recognize anxiety from a character checking their phone over and over, even if the word “anxious” never appears. That made me curious whether Qwen shows a similar pattern of internal activity when it writes about anxiety in a completely different situation.

I find this interesting because recognizing an emotion requires looking beyond individual words to understand the situation and a character’s behavior. If similar internal patterns appear across different stories, that could suggest the model represents something more general about the emotion. I would like to understand whether these patterns reflect emotions consistently or depend heavily on the language and situations in each story.  
<br>
  
**2. Describe a potential investigation you would like to pursue for your Quarter 2 Project.**  
For Quarter 2, I would like to investigate whether emotion representations in Qwen generalize across different story situations. For example, we could extract a direction associated with anxiety from stories about social situations, then test whether it also captures anxiety in stories about school or work. This would build on our Quarter 1 replication while introducing a new research question about how broadly these representations apply.

We could also test whether steering along this direction makes new stories convey anxiety without explicitly naming it. Evaluating both the emotion conveyed and the overall quality of the stories would help determine whether steering produces a meaningful change. I would also be interested in whether an anxiety direction specifically increases anxiety or produces a broader negative tone.  
<br>

**3. What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**  
Since Quarter 1 is a replication of the Claude paper, I would keep the core methodology consistent and add a broader evaluation using more varied story prompts. In particular, I would separate the situations used to extract emotion directions from those used to test them. This would help us examine whether the results extend beyond familiar story settings.

I would also include comparisons between stories that share a situation but convey different emotions, and stories that convey the same emotion in different situations. These comparisons could help distinguish an emotion representation from patterns related to the story’s topic. I would treat this as an additional robustness check alongside the original replication.  
<br>

**4. What other techniques would you be interested in using in your project?**  
I would be interested in using linear probes to test whether we can predict a story’s intended emotion from the model’s internal activations. Comparing probe performance across layers could help us investigate where emotion information is accessible. Testing on unfamiliar story situations would also help assess whether the probe learns patterns that generalize.

I would then like to use activation steering to test whether the identified directions actually influence the emotions conveyed in generated stories. Comparing related emotions, such as anxiety and fear, could help us understand how distinct their representations are. Human evaluations could complement these experiments by checking whether readers perceive the intended emotion and whether the stories remain coherent.

# Day 5 - Context Engineering

## What is Context Engineering?
Context Engineering means giving Claude enough 
background information so it can generate a 
truly personalized and accurate response.
The more context you provide, the better 
and more useful the output becomes.

## Prompt A — No Context
Give me a study plan.

### Output Summary
- Generic Computer Science study plan
- Started from absolute basics
- No personalization at all
- Could be for anyone in the world
- Quality: 2/5
  <img width="1208" height="751" alt="image" src="https://github.com/user-attachments/assets/16527a64-f7df-498d-9c29-8e435fb4f1a2" />

  <img width="933" height="677" alt="image" src="https://github.com/user-attachments/assets/1ae8dbf3-337f-4386-8336-dc2b1e6729c0" />



---

## Prompt B — With Full Context
Give me a study plan with the following details:
- Name: Syed Motahir Hasan
- Age: 22 years old
- Location: Gorakhpur, Uttar Pradesh, India
- Current Degree: MCA (Final Year)
- Current Skills: Python, SQL, Power BI
- Career Goal: Data Analyst → Data Scientist 
  → AI Engineer at FAANG
- Available Time: 2-3 hours per day
- Learning Style: Visual and practical projects
- Timeline: 3 years (2025-2028)

### Output Summary
- Fully personalized plan for Syed Motahir Hasan
- Built on existing Python, SQL, Power BI skills
- Clear 3 year roadmap to FAANG
- 6+ portfolio projects included
- Month by month milestones defined
- Quality: 5/5
<img width="966" height="592" alt="image" src="https://github.com/user-attachments/assets/b9f4d896-7a2c-40ce-a51f-2eed3b2b07e6" />

---

## Comparison Table

| Feature | Prompt A | Prompt B |
|---------|----------|----------|
| Personalization | None | Full |
| Skill Level | From scratch | Builds on existing |
| Goal | Generic | FAANG specific |
| Projects | Simple apps | Real ML projects |
| Quality | 2/5 | 5/5 |

## Key Learnings
- Context Engineering = giving AI full background
- More context = more personalized output
- Always share your name, goals, skills, timeline
- Prompt A made Claude guess everything
- Prompt B gave Claude everything it needed

## Biggest Insight
Same question, completely different results!
Context is the most powerful tool in prompting.
Gorakhpur to FAANG is possible with the right plan!

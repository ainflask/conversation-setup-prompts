# conversation-setup-prompts
Prompt templates for the conversation setup of ainflask chat agent

[ainflask](https://ainflask.com) will directly read this Github repo to populate some chat agent templates, feel free to create issues with your suggestions or directly pull requests for other better prompt templates

`version.txt` in top level keep track of file structure (right now just a flat list of templates, no other hierarchical groupings yet), don't change

template file must be in JSON format and choose a crisp and descriptive name with all lowercase alpha-numeric with hypens only (for more descriptions, put into the description field of that JSON, refer below)

Each template just follow below formats (noted version must be 1.0.0 for now)

```
{
   "version": "1.0.0",
   "description": "This is this template description",
   "scenario": "This is your scenario to explain background, who you are or what role you want your agent plays",
   "problem": "This is your main problem to solve",
   "goal": "This is the outcome you want out of your problem",
   "constraints": "This is your explicit constraints you want to emphasize with your agent",
   "chathints": "This is some extra chat instructions or hints you want to convey to your agent" 
}
```

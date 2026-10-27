# Resume Coach

English | [简体中文](README.zh-CN.md)

A beginner-friendly resume writing and job-search coaching skill for Developer CatCatUncle and his followers. It helps people turn real experience into a clear, role-focused resume and prepare to discuss that experience in interviews.

## Start in one message

Users do not need a polished resume or a long intake form. They can paste a resume, send rough notes, or start with one experience.

Try one of these prompts:

- **Edit my resume:** “Help me improve my resume for an operations role. Here are my resume and the job description.”
- **Write from scratch:** “I need my first resume for a customer service role. I have worked as a restaurant cashier and helped with scheduling.”
- **Change careers:** “I have taught for five years and want to move into product operations. Help me identify relevant experience.”
- **Explore roles:** “Here is my experience. I prefer roles without frequent travel. Help me explore suitable job directions.”
- **Fix one section:** “Make this project description clearer without overstating my contribution.”

The skill asks only a few short questions at a time, starts with available information, and marks unknown facts for confirmation.

## What it does

- Reviews, edits, or writes a resume from scratch
- Tailors resume content to a real job description
- Helps new graduates and career changers find relevant, truthful evidence
- Separates direct matches, transferable evidence, real gaps, and unknowns
- Prepares interview stories and one practical next step when useful

## Recommended: Use with OpenWorkBuddy

This skill works as a standalone agent skill. For a local, file-based workflow, use it with [OpenWorkBuddy](https://github.com/CatCatUncle/openworkbuddy), an open-source, local-first AI office agent that can turn a request into editable work files and connect to different model providers and MCP tools.

If you have cloned OpenWorkBuddy, run this command from its project directory:

```bash
git clone https://github.com/CatCatUncle/resume-coach.git skills/resume-coach
```

The skill entry point is `SKILL.md`. Refresh the skill list and start with `/resume-coach`. You can then provide a resume and a job description, or simply describe one experience in your own words. The skill will guide you through the next few questions instead of asking you to complete a long form first.

OpenWorkBuddy is designed to run locally, but data handling also depends on the model and connectors you configure. Review those settings before sharing sensitive resume information. Personal non-commercial use is free; commercial use requires a separate license. See the [OpenWorkBuddy repository](https://github.com/CatCatUncle/openworkbuddy) for the current terms and setup instructions.

👉 **Try OpenWorkBuddy:** [GitHub repository](https://github.com/CatCatUncle/openworkbuddy) · [Project page](https://catcatuncle.github.io/openworkbuddy/)

## About the Author

Created by **开发者猫叔 (CatCatUncle)**, creator of OpenWorkBuddy, focused on practical AI agent workflows.

- GitHub: [@CatCatUncle](https://github.com/CatCatUncle)
- OpenWorkBuddy: [github.com/CatCatUncle/openworkbuddy](https://github.com/CatCatUncle/openworkbuddy)
- Enterprise AI and Agent collaboration: [contact@aijentra.com](mailto:contact@aijentra.com)

If this skill helps you, give [OpenWorkBuddy a star](https://github.com/CatCatUncle/openworkbuddy) and share it with someone who is job hunting.

## Trust and privacy

- Never invent experience, skills, credentials, metrics, or outcomes.
- Do not exaggerate individual ownership of team results.
- Use metrics only when the candidate confirms their source and meaning.
- Never promise ATS passage, interviews, salary, or an offer.
- Keep each person's resume information separate.
- Keep real resumes, candidate records, and generated documents outside this repository.
- Get explicit consent and anonymize thoroughly before using a follower's resume in public content.

## License

This skill is licensed under the MIT License. It is an independently written skill and is separately licensed from the OpenWorkBuddy application. See [LICENSE](./LICENSE).

## Research references

The skill was informed by guidance from [Yale OCS](https://ocs.yale.edu/resources/writing-impactful-resume-bullets/), [Harvard FAS](https://careerservices.fas.harvard.edu/blog/2026/09/15/resumes-for-industry-grad-student-edition-2026/), [MIT CAPD](https://capd.mit.edu/resources/career-toolkit-crafting-an-effective-resume/), [UC Berkeley Career Engagement](https://www.career.berkeley.edu/prepare-for-success/resumes/), China's [Employment Training and Technical Instruction Center](https://chinajob.mohrss.gov.cn/h5/c/2021-11-23/331916.shtml), and [Greenhouse's resume parsing guidance](https://support.greenhouse.io/hc/en-us/articles/200989175-Unsuccessful-resume-parse). These recommendations vary by market and system; the skill treats them as guidance, not universal rules.

The skill also reviewed [WonderCV's resume guide](https://github.com/WonderCV-com/resume-guide) for its topic taxonomy. Its repository is licensed under [CC BY-SA 4.0](https://github.com/WonderCV-com/resume-guide/blob/main/LICENSE). This skill uses high-level methods and does not copy article passages or example metrics. Any specific text reuse must comply with that license.

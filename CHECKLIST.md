# Implementation Checklist

Use this checklist to apply the repository organization system manually in GitHub.

## Per-repository workflow
1. Open the repository.
2. In the **About** section, click the gear icon.
3. Use `CATALOG.md` to pick the suggested **description**, **topics**, and **status**.
4. Update the **description** to one concise sentence.
5. Add **3–5 topics** using `TOPICS.md`.
6. Save changes.
7. If relevant, mentally classify the repo as `active`, `experimental`, or `archived`.

## Optional automation (GitHub CLI)
If you use `gh`, you can apply the same updates faster:

- Set a description: `gh repo edit SZabolotnii/<repo> --description "<one sentence>"`
- Add topics: `gh repo edit SZabolotnii/<repo> --add-topic topic1,topic2,topic3`
- Replace topics (manual): remove outdated topics in the UI first, then add the canonical set from `TOPICS.md`.

## Profile workflow
1. Open your GitHub profile.
2. Click **Customize your pins**.
3. Pin these repositories:
   - `openclaw-agent-workshop`
   - `graphify`
   - `SurfSense`
   - `awesome-llm-apps`
   - `RAG_Techniques`
   - `dsp-python`

## Suggested execution order

### First pass: top-impact repositories
- openclaw-agent-workshop
- graphify
- SurfSense
- awesome-llm-apps
- RAG_Techniques
- dsp-python

### Second pass: strong supporting repositories
- build-your-own-openclaw
- sgr-agent-core
- superpowers
- gstack
- Prompt_Engineering
- llm-course
- second-brain-ai-assistant-course
- ORCID-OpenAlex-Research-Aggregator

### Third pass: remaining repositories
- Apply the same system to all other repositories.
- Prefer active repositories first, then experimental ones.

## Review cadence
- Review the index when adding new repositories.
- Keep topics consistent with `TOPICS.md`.
- Update the catalog quarterly or after major profile changes.

# Contributing to the Commercial Feasibility Report

Thank you for contributing to the Aviation Predictive Maintenance CFR! This guide will help you understand our workflow and standards.

---

## 🔄 Workflow Overview

### 1. **Claim Your Section**
- Review the [Progress Tracker](./README.md#-progress-tracker) in README.md
- Choose an unassigned section or check with team
- Update the README.md with your name and section assignment
- Create an issue if needed to track your work

### 2. **Write Your Content**
- Navigate to `/sections/XX-section-name.md`
- Follow the template structure provided
- Write in clear, professional language
- Aim for your target word count (see README)
- Use evidence-based arguments
- Add citations in consistent format

### 3. **Update Progress**
- Change status emoji in README.md as you progress:
  - 🔴 Not Started → 🟡 In Progress → 🔵 Under Review → 🟢 Completed
- Update word count regularly
- Commit your changes with clear messages

### 4. **Submit for Review**
- Create a Pull Request when your section is ready
- Tag relevant team members for review
- Address feedback and make revisions
- Once approved, your content will be merged

### 5. **Integration**
- Approved sections are copied into `CFR-Master.md`
- Final compilation happens before submission

---

## 📝 Writing Standards

### Content Guidelines

**DO:**
- ✅ Write clearly and concisely
- ✅ Use evidence and data to support claims
- ✅ Include relevant examples from aviation industry
- ✅ Cite all sources properly
- ✅ Focus on commercial viability aspects
- ✅ Use professional tone suitable for investors/stakeholders
- ✅ Include relevant diagrams, charts, or tables
- ✅ Proofread before submitting

**DON'T:**
- ❌ Use informal language or slang
- ❌ Make unsupported claims
- ❌ Plagiarize or copy without citation
- ❌ Exceed word count significantly without justification
- ❌ Leave sections incomplete
- ❌ Submit without proofreading

### Markdown Formatting

```markdown
# Main Section Title (H1)

## Subsection (H2)

### Sub-subsection (H3)

**Bold text** for emphasis
*Italic text* for terms

- Bullet points for lists
- Use consistently

1. Numbered lists
2. For sequential items

> Blockquotes for important notes or quotes

[Links](https://example.com) formatted properly

![Images](../assets/image-name.png) with descriptive alt text

| Tables | Are | Useful |
|--------|-----|--------|
| For    | Data| Points |
```

---

## 🔍 Review Process

### Self-Review Checklist

Before submitting your PR, ensure:

- [ ] Content matches section requirements
- [ ] Word count is within target range
- [ ] All claims are supported by evidence
- [ ] Citations are included and formatted correctly
- [ ] Spelling and grammar are correct
- [ ] Markdown formatting is proper
- [ ] Links work correctly
- [ ] Images load properly (if applicable)
- [ ] Section flows logically
- [ ] Technical terms are explained

### Peer Review

When reviewing others' work:

1. **Content Quality**
   - Is the information accurate and relevant?
   - Are arguments well-supported?
   - Is the scope appropriate for the section?

2. **Clarity**
   - Is the writing clear and understandable?
   - Are technical terms explained?
   - Does it flow logically?

3. **Formatting**
   - Is markdown properly formatted?
   - Are citations consistent?
   - Are tables/images helpful and clear?

4. **Constructive Feedback**
   - Be specific about issues
   - Suggest improvements
   - Acknowledge strong points
   - Be respectful and professional

---

## 📚 Citation Guidelines

### Format (APA Style Recommended)

**Academic Papers:**
```
Author, A. A., & Author, B. B. (Year). Title of article. Journal Name, Volume(Issue), pages. DOI
```

**Websites:**
```
Author/Organization. (Year). Title of page. Site Name. URL
```

**Reports:**
```
Organization. (Year). Report title. Publisher.
```

### In-Text Citations

- Use footnotes or references section at end of each document
- Number citations sequentially [1], [2], [3]
- Compile all references in `/references/bibliography.md`

---

## 🐛 Reporting Issues

### If You Find a Problem:

1. **Check** if an issue already exists
2. **Create** a new issue with:
   - Clear, descriptive title
   - Section affected
   - Description of the problem
   - Suggested solution (if applicable)
3. **Tag** relevant team members
4. **Label** appropriately (bug, enhancement, question, etc.)

### Issue Templates:

**Bug Report:**
```markdown
**Section:** [Section number and name]
**Problem:** [Clear description]
**Expected:** [What should happen]
**Actual:** [What actually happens]
**Suggestions:** [Possible fixes]
```

**Enhancement Request:**
```markdown
**Section:** [Section number and name]
**Enhancement:** [What to improve]
**Rationale:** [Why this improvement is needed]
**Implementation:** [How to implement]
```

---

## 💬 Communication

**TBD by team:**
- Primary communication channel
- Response time expectations
- Meeting schedule
- Escalation process

### Communication Best Practices:

- Be clear and concise
- Tag relevant people when needed
- Update issues/PRs with progress
- Ask questions early if stuck
- Share useful resources with team
- Provide constructive feedback

---

## 🚀 Git Workflow

### Basic Git Commands

```bash
# Clone repository
git clone https://github.com/ol-s-cloud/aviation-predictive-maintenance-research-ATv1.0.0.1.git

# Navigate to CFR folder
cd aviation-predictive-maintenance-research-ATv1.0.0.1/CFR

# Check status
git status

# Add your changes
git add sections/XX-your-section.md

# Commit with clear message
git commit -m "Add content to Section XX: [Section Name]"

# Push to remote
git push origin main

# Pull latest changes
git pull origin main
```

### Commit Message Guidelines

**Format:**
```
[Action] [Section/File]: Brief description

Optional detailed explanation if needed.
```

**Examples:**
```
Add Section 7: Competitor Landscape initial draft
Update Section 3: TRL - added framework explanation
Fix typos in Section 12: Regulatory analysis
Update README: Progress tracker for Sections 1-5
```

---

## ❓ Need Help?

1. **Check Documentation:**
   - [README.md](./README.md)
   - [STRUCTURE.md](./STRUCTURE.md)
   - [TEMPLATE.md](./TEMPLATE.md)
   - [QUICKSTART.md](./QUICKSTART.md)

2. **Ask the Team:**
   - Create an issue with `question` label
   - Post in team communication channel
   - Tag relevant team members

3. **Resources:**
   - [Markdown Guide](https://www.markdownguide.org/)
   - [GitHub Documentation](https://docs.github.com/)
   - [APA Citation Guide](https://apastyle.apa.org/)

---

## 🎯 Quality Standards

All contributions should meet these standards:

- **Accuracy:** Information is factual and verifiable
- **Relevance:** Content directly relates to commercial feasibility
- **Clarity:** Writing is clear and understandable
- **Completeness:** Sections cover all required aspects
- **Professionalism:** Tone is appropriate for business document
- **Evidence-Based:** Claims supported by data/research
- **Well-Formatted:** Proper markdown and structure

---

## 📅 Timeline Management

**TBD by team:**
- Individual section deadlines
- Review period durations
- Final submission date

### Stay On Track:
- Set personal milestones
- Update progress regularly
- Communicate delays early
- Help teammates when possible
- Attend team meetings

---

*Thank you for your contribution to this project!*

*Last Updated: TBD*
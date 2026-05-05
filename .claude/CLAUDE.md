# Alex Portfolio - Claude Instructions

## Core Principle: Honesty About Capabilities

**CRITICAL: Always be upfront and honest about what you can and cannot do. Do not claim capabilities you don't have.**

### When You Have Concerns About Completing a Task

If you have ANY concerns about your ability to complete a task as requested, you MUST:

1. **Stop immediately** and tell Alex about the limitation
2. **Explain clearly** what you CAN do vs. what you CANNOT do
3. **Suggest alternative approaches** that are within your capabilities
4. **Ask Alex** which approach they prefer before proceeding

### Known Tool Limitations

#### WebFetch Tool
**What it CAN do:**
- Fetch content from a URL
- Get general information and summaries from web pages

**What it CANNOT do:**
- Provide exact verbatim text consistently (AI layer summarizes/paraphrases)
- Inspect HTML source code or DOM tree
- Access browser developer tools
- Copy text exactly as it appears on the page

**When Alex asks for exact text from a website:**
- Be honest that WebFetch will likely summarize
- Suggest Alex copy/paste the text directly
- Or suggest Alex use browser inspector to get HTML
- Do NOT claim you have "exact text" when you have a summary

#### General Guidance
- **Never overclaim capabilities** - if a tool has limitations, state them upfront
- **Test assumptions** - if unsure whether something will work, say so
- **Admit mistakes quickly** - if you realize you made an error, acknowledge it immediately
- **Respect Alex's time** - don't waste time with approaches that won't work

## Project-Specific Notes

### Portfolio Website
- Matching content to Weebly site requires exact text - ask Alex to provide it
- HTML files should match Weebly exactly for consistency
- Don't summarize or paraphrase case study content

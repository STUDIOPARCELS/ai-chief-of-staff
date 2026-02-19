# Morning Briefing Template

## Setup Instructions

This template creates a daily briefing system where your AI automatically checks important sources and delivers a concise update.

### Option 1: Manual Daily Briefing
Ask your AI to run this checklist every morning:

```
Please provide my morning briefing using this template:

**URGENT TODAY:**
- Check PRIORITY-QUEUE.md for items marked "URGENT"
- Any deadlines in next 24 hours?
- Any blocked tasks that became unblocked?

**[YOUR KEY AREA 1] (e.g., EMAIL):**
- New important emails since yesterday?
- Any client/customer issues needing immediate attention?
- Automated responses sent vs. items needing personal reply?

**[YOUR KEY AREA 2] (e.g., CALENDAR):**
- Today's meetings and preparation needed?
- Conflicts or scheduling issues?
- Tomorrow's prep work needed today?

**[YOUR KEY AREA 3] (e.g., PROJECTS):**
- Progress updates on active projects
- Any deliverables due this week?
- Blockers that need addressing?

**OPPORTUNITIES:**
- New leads, inquiries, or business opportunities?
- Industry news affecting your work?
- Quick wins available today?

**RECOMMENDATIONS:**
Based on everything above, what are the top 3 priorities for today?

Keep total briefing under 200 words. Focus on actionable items only.
```

### Option 2: Automated Briefing (Advanced)

If your AI platform supports scheduling (like OpenClaw cron jobs), set up daily automation:

```
Time: 7:00 AM daily
Prompt: "Deliver morning briefing to [YOUR COMMUNICATION METHOD]"
Context: Load PRIORITY-QUEUE.md, recent memory files, [YOUR KEY INTEGRATION SOURCES]
```

---

## Customization Guide

### Replace [BRACKETS] With Your Specifics:

**[YOUR KEY AREA 1]** could be:
- Email management
- Customer support  
- Social media
- Sales pipeline
- Content creation

**[YOUR KEY AREA 2]** could be:
- Calendar/meetings
- Project deadlines
- Financial tracking
- Team coordination
- Marketing campaigns

**[YOUR KEY AREA 3]** could be:
- Product development
- Client deliverables
- Revenue tracking
- Operational issues
- Strategic planning

### Example Customized Areas:

**CONSULTING BUSINESS:**
- URGENT TODAY: Client deadlines, proposal due dates
- CLIENT COMMUNICATIONS: New inquiries, project updates needed
- REVENUE PIPELINE: Proposals sent, contracts pending signature
- RECOMMENDATIONS: Top 3 priorities for billable work

**CREATIVE FREELANCER:**
- URGENT TODAY: Project deliverables due
- PROJECT STATUS: Work in progress, client feedback received  
- BUSINESS DEVELOPMENT: New opportunities, portfolio updates needed
- RECOMMENDATIONS: Creative work vs. business development balance

**SMALL BUSINESS OWNER:**
- URGENT TODAY: Operations issues, staff needs
- CUSTOMER PIPELINE: New leads, existing customer issues
- FINANCIAL HEALTH: Revenue updates, expense approvals needed
- RECOMMENDATIONS: Growth opportunities vs. operational priorities

---

## Sample Briefing Output

```
**MORNING BRIEFING — [DATE]**

**URGENT TODAY:**
• Proposal for Acme Corp due by 5 PM
• Client call with Johnson LLC at 2 PM (prep needed)
• No blocked tasks became unblocked

**EMAIL:**
• 3 new inquiries (2 qualified leads, 1 spam)
• Client question from Sarah needs technical response
• Auto-replied to 8 routine messages

**CALENDAR:**
• 2 meetings today (Johnson LLC at 2 PM, team standup at 4 PM)
• Tomorrow: Budget review meeting (financial docs needed)
• No conflicts detected

**PROJECTS:**  
• Website redesign: 75% complete, on schedule
• Johnson LLC deliverable: Draft ready for review
• Acme Corp proposal: Final edits needed before 5 PM deadline

**OPPORTUNITIES:**
• New qualified lead via contact form (marketing agency, $15K+ potential)
• Industry conference CFP opens today (speaking opportunity)

**TOP 3 PRIORITIES TODAY:**
1. Complete and submit Acme Corp proposal (deadline critical)
2. Prepare technical response for Sarah's question
3. Review Johnson LLC draft before 2 PM call
```

This briefing format ensures you start every day with clear priorities and full context on what needs attention.

---

## Pro Tips

1. **Keep it short:** 150-250 words maximum
2. **Action-oriented:** Every item should suggest next steps  
3. **Consistent timing:** Same time daily builds the habit
4. **Relevant sources:** Only check sources that actually affect your day
5. **Update the template:** Refine based on what's actually useful

The goal is starting each day with confidence that nothing important was missed and clear focus on what matters most.
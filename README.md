
# PIP — Ethical & Harmless Office Pranks

> **Company-approved** collection of playful, harmless, consent-first prank ideas and templates for employees.  
> Use only within company policy and with respect for colleagues’ privacy, property, and dignity.

---

## Description
**PIP** is a community-maintained repository of light-hearted, harmless prank and surprise ideas safe to use in the workplace — **only** when the target has given explicit consent or when the prank is obviously harmless and easily reversible. This repo is intended for ideas that build team spirit and smiles, not embarrassment, harm, or legal risk.

**Welcome content examples**
- Desk-decor surprises (balloon walls, themed desks).
- Harmless visual jokes (sticky-note art with permission).
- Printable party templates, signs, and props.
- Playful out-of-office message templates for the account owner to use themselves.
- Consent checklists and scripts for asking permission.
- “Prank recovery” templates — quick undo steps and apology scripts.

**Not allowed**
- Any instructions that encourage accessing someone else’s device or account without permission.
- Sending messages that impersonate someone else.
- Pranks that could cause emotional, physical, financial, or reputational harm.
- Illegal activities, doxxing, threats, harassment, or anything that breaks company policy.

Submissions violating these rules will be rejected and may result in contributor removal.

---

## Community values
- **Be kind.** If it could embarrass or shame someone, don’t do it.
- **Apni maryada mein rahen** — maintain respect and dignity.
- **Reversible & clean.** Pranks should be easy to undo and leave no lasting impact.
- **Safety-first.** No pranks that interfere with work, health, security, accessibility, or critical systems.

---

# How to contribute (step‑by‑step PR guide)

We welcome contributions from employees. Follow these steps to propose a new idea or template.

1. **Fork the repository**
   - Click **Fork** (on GitHub/GitLab) to create your copy.

2. **Clone your fork**
   ```bash
   git clone https://github.com/<your-username>/prank-lab.git
   cd prank-lab
   ```
3.  **Create a branch**
    
    Use a clear branch name: `idea/<short-descriptive-name>` or `feature/<short-name>`.
    `git checkout -b idea/birthday-balloon-wall` 
    
4.   **Add content**

	-   Create a file in the appropriate folder:
        
        -   `ideas/` — prank ideas (markdown files)
            
        -   `templates/` — message templates, consent scripts
            
        -   `media/` — images (ensure you have permission)
            
    -   Filename example: `ideas/birthday-balloon-wall.md`
        
5.   **Follow the content template**  
    Copy this header into your new idea file and fill it out:
    # Title: <Short, descriptive title>
    ```
	**Category:** desk-decor / message-template / party / game / other  
	**Effort:** low / medium / high  
	**Materials / cost:** list or estimate  
	**Consent required:** yes / no — if yes, explain how to ask  
	**Instructions:** step-by-step, short and clear  
	**Undo / cleanup steps:** how to restore things to normal  
	**Safety & accessibility notes:** allergies, warnings, accessibility considerations  
	**License:** CC-BY-SA 4.0 (or repo license)	
	```
6.  **Run basic checks**
    
    -   Proofread for suggestions that are non-consensual or illegal.
        
    -   Confirm any media is allowed to be shared.
        
7.  **Commit and push**
    
    ```git add ideas/birthday-balloon-wall.md
    git commit -m "Add: Balloon Wall Surprise (consent required)" git push origin idea/birthday-balloon-wall` ``
    
8.  **Open a Pull Request**
    
    -   From your fork/branch, open a PR against the main repo.
        
    -   Use the PR template (below) and clearly describe the idea and consent steps.
        

----------

## Pull request template (copy into PR description)

-   **Title:** Short, descriptive
    
-   **Category:** desk-decor / message-template / party / etc.
    
-   **Consent needed:** yes/no — if yes, how to get it
    
-   **Materials / cost estimate:**
    
-   **Step-by-step instructions:** include undo steps
    
-   **Safety / cleanup / accessibility notes:**
    
-   **Screenshots / mockups:** optional, include only images you have rights to
    
-   **License:** CC-BY-SA 4.0 (or repo license)
    

Maintainers will review and may request edits.

----------

## PR review checklist (for maintainers & contributors)

-   ✅ Does this idea require consent? Is the consent method documented?
    
-   ✅ Is the prank reversible and non-damaging?
    
-   ✅ Are safety and cleanup instructions included?
    
-   ✅ Does it avoid instructing access to others’ devices/accounts?
    
-   ✅ Language is respectful and within company guidelines?
    

----------

## Community guidelines & Code of Conduct

This repository follows a respectful, professional code of conduct.

-   Treat colleagues with respect. No harassment or abusive language.
    
-   Keep humor inclusive — avoid jokes targeting protected classes or vulnerable groups.
    
-   If someone asks you to stop or remove an idea, comply promptly.
    
-   Report violations by opening an issue titled `REPORT: <reason>` (private reports can be routed to maintainers if required).
    

Violations can result in content removal and contributor bans.

----------

## How to seek help

-   **Questions about contributing**: open an issue with label `question`.
    
-   **Help with a PR**: mention maintainers in the PR or open an issue `PR-HELP: <PR number>`.
    
-   **Report a violation or risky idea**: open an issue titled `REPORT: <short reason>` and include links.
    
-   **Emergency / legal concerns**: contact the repo owners / maintainers (see `MAINTAINERS.md`) and your HR or legal team if immediate action is necessary.
    
-   **Internal contact**: ping the designated repo maintainers or the People Ops representative listed in `MAINTAINERS.md`.
    

----------

## Example safe ideas (short)

### Balloon Wall Surprise (example)

**Category:** desk-decor — **Effort:** low — **Consent required:** yes  
**Materials:** balloons, removable tape, scissors  
**Instructions:** Ask permission. If approved, fill the person’s cubicle wall with balloons while they’re at lunch. Leave a small note explaining it’s a surprise.  
**Undo:** Pop or remove balloons and tape; leave workspace clean.  
**Safety:** Avoid latex if allergic; do not block exits or equipment.

### Playful OOO Template (to be used by the owner)

`Hello — I’ll be out of office enjoying a much-needed break. Back on <date>. For urgent things, contact <colleague>. Cheers!` 

----------

## File layout (suggested)

`/ (root)
├─ README.md
├─ CONTRIBUTING.md
├─ MAINTAINERS.md
├─ ideas/
│  ├─ example-idea.md
├─ templates/
│  ├─ ooo-template.md
├─ media/
├─ LICENSE` 

----------

## License

Content licensed under **Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0)** unless otherwise noted. See `LICENSE` for details.

 ``--- ### Two quick ways to add this README to your repo  **A) Use GitHub web UI (fast, no local git required)**  1. Go to your repository page on GitHub. 2. Click **Add file** → **Create new file**. 3. Name it `README.md`. 4. Paste the Markdown content (from the block above). 5. Scroll down, add a commit message (e.g., `Add company-approved README`), choose **Create a new branch** (optional) or commit to `main` if allowed. 6. Click **Commit new file**. 7. If you created a branch, open a Pull Request and merge. **B) Use Git locally (recommended if you plan more edits)**  1. Clone the repo:
   ```bash
   git clone https://github.com/<your-org>/<your-repo>.git
   cd <your-repo>`` 

2.  Create a branch:
    
    `git checkout -b docs/add-readme` 
    
3.  Create the README file and paste the content. (Use your editor: `code README.md` or `nano README.md`.)
    
4.  Stage and commit:
    
    `git add README.md
    git commit -m "Add company-approved README" git push -u origin docs/add-readme` 
    
5.  Open a Pull Request on GitHub and merge when approved.
    

----------

Want me to:

-   produce the file contents as a downloadable file? (I can paste it so you can copy), or
    
-   create a short `CONTRIBUTING.md` or `PR_TEMPLATE.md` next?
    

Pick one and I’ll drop it in Markdown form ready to paste.

1. Use a local text-to-speech tool to have your laptop randomly announce silly messages (“Your coffee is conspiring against you!”) at scheduled times.
2. 

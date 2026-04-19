
## Project Overview
The project proposes an analytics dashboard for English Premier League which identifies player performance metrics on how they have impact in team success. Complex dataset is simplified into insights that can be used in decision making by managers and coaches. 

---

## Decision-Making Problem
Team decision makers always have access to huge amounts of data on players but becomes difficult to select the main metric that contributes to winning a game. The project tries to solve this problem through identifying indicators that gives a high value player to improve player selection and strategy. 

---

## Proposed Analytics Approach
Publicly available data on players and teams will be used in the analysis which combines factors such as passes, assists, tackles, win records, and goals scored by a player. The analysis will try to answer questions based on identification of relationships that exists among metrics that contribute to team success. The dataset will be cleaned and new rows added to help in making the analysis easy and well understood by decision makers. 

---

## Use by Decision Makers
Decision makers in a team comprise of the coaches, managers, and analysts. They will make use of the dashboard in the identification of high value and high-performance players in order to make informed decisions on matters touching tactics, transfers, and even line up selection. The dashboard will present data in visuals which is easy to comprehend as compared to data tables. 

## Connection to Chapter 7
This project is currently in the creative phase because it focuses on defining the idea and identifying how analytics can support decision-making, and not yet tested.  
---

## Prototype Enhancement
**Branch:** `prototype`

**What is being changed:**
The original concept relies partly on wearable/biometric data, which is not always accessible or consistently collected. This enhancement refines the fatigue score to use **only publicly available data** — specifically game logs, schedule data, and travel distances — making the tool viable for any NBA team regardless of their internal data infrastructure.

Additionally, the presentation layer is being changed: instead of a numerical fatigue score, the prototype will use a **simplified three-tier classification system** (Low Risk / Moderate Risk / High Risk) based on defined thresholds. This makes the output immediately actionable for coaches who may not have time to interpret raw numbers during a game-day preparation meeting.

**Why this change could improve decision-making:**
1. **Accessibility:** Removing the dependency on proprietary wearable data means the tool can be prototyped and validated immediately using existing public datasets, lowering the barrier to adoption.
2. **Clarity:** Research on decision-making under time pressure (relevant to game-day coaching) shows that categorical recommendations outperform numerical scores when fast decisions are needed. A coach seeing "HIGH RISK" acts more quickly and confidently than one interpreting a score of 78.4 out of 100.
3. **Buy-in:** Simpler outputs are easier to explain to skeptical stakeholders, which is critical during the engagement phase of innovation.
## Prototype Evaluation
**Branch evaluated:** `prototype`

**Should the prototype be integrated into the main project?**
Yes — with conditions. The shift to publicly available data and the three-tier classification system are both meaningful improvements that increase the tool's practical viability. The core analytics idea is strengthened, not compromised, by these changes. The prototype is a logical evolution of the original concept and aligns well with organizational adoption goals.

However, integration should be conditional on receiving structured feedback from at least two key stakeholder groups before merging becomes final.

**What feedback from decision makers would influence this decision?**
- **From the Head Coach or Coaching Staff:** Does the Low/Moderate/High Risk classification feel intuitive? Are there game situations where a more nuanced output would be preferred? Coaches need to validate that the categories map onto how they actually make rotation decisions.
- **From the Team Medical/Training Staff:** Do the thresholds used to define each risk tier align with clinical understanding of fatigue and injury risk? Medical staff buy-in is essential for the tool to be trusted and used consistently.
- **From the Front Office/Analytics Director:** Is the reliance on only public data a limitation for long-term use, or is it acceptable for a first version? This shapes whether the tool is adopted as-is or slated for a second iteration with internal data.

If feedback from these groups is broadly positive, the prototype branch should be merged into main and the project should move into the **Build Phase**.
## Connection to Chapter 7
This idea currently represents the **Creative Phase** of the innovation framework. A specific problem has been identified (player fatigue mismanagement), a solution concept has been proposed, and the data sources needed have been outlined. However, the idea has not yet been tested, validated with stakeholders, or built into a functioning system. The next step would be moving into the **Prototyping Phase** by developing a simplified version of the fatigue score to test its usefulness with coaches.
---

## Reflection on Innovation and Version Control

**How branches support low-risk experimentation:**
GitHub branches allow an analytics team to test new ideas — like changing a metric definition or adding a data source — without altering the stable, approved version of a project. If the experiment fails or receives negative feedback, the branch is simply discarded and the main project is unaffected. This mirrors how innovative organizations create "safe spaces" for experimentation described in Chapter 7: failure is contained and learning is preserved.

**How GitHub helps analytics ideas gain traction with decision makers:**
Version control creates a transparent, documented record of how an idea evolved. Decision makers — coaches, GMs, or executives — can see exactly what changed, why it changed, and what was evaluated before adoption. This audit trail builds credibility and trust. Rather than presenting a finished tool and asking for approval, the team can show a history of thoughtful iteration, which addresses a key barrier to adoption identified in Chapter 7: stakeholder skepticism.

**Alignment with the Chapter 7 innovation framework:**
Each GitHub workflow element maps directly onto an innovation phase:
- **README drafting (main branch)** → *Creative Phase:* articulating the problem and idea
- **Prototype branch** → *Prototyping Phase:* low-risk testing of enhancements
- **Evaluation section** → *Engagement Phase:* defining what stakeholder feedback is needed
- **Merge decision** → *Build Phase:* committing to implementation based on evidence

This workflow demonstrates that version control is not just a software development tool — it is an innovation management framework that helps analytics ideas move from concept to organizational impact with discipline and transparency.

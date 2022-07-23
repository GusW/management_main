# An Elegant Puzzle: Systems of Engineering Management

#### Will Larson

---

## 2 - Organizations

### 2.1 - Sizing Teams

Managers should support six to eight engineers

- Tech Lead Managers (TLMs)
  - Managers supporting fewer than four engineers tend to function as TLMs.
- Coaches
  - Managers supporting more than eight or nine engineers typically act as coaches and safety nets for problems.

Managers-of-managers should support four to six managers

- Ramping up
  - Managers supporting fewer than four other managers should be in a period of active learning on either the problem domain or on transitioning from supporting engineers to supporting managers.
- Coaches
  - Similar to supporting a large team of engineers, supporting a large team of managers leaves you functioning purely as a problem-solving coach.

On-call rotations want eight engineers

- Shared rotations
  - It is sometimes necessary to pool multiple teams together to reach the eight engineers necessary for a 24/7 on-call rotation. This is an effective intermediate step toward teams owning their own on-call rotations, but it is not a good long-term solution.

Small teams (fewer than four members) are not teams.

- An important property of teams is that they abstract the complexities of the individuals that compose them. Teams with fewer than four individuals are a sufficiently leaky abstraction that they function indistinguishably from individuals.

- They are also fragile, with one departure easily moving them from innovation back into toiling to maintain technical debt.

Playbook:

- Teams should be six to eight during steady state.
- To create a new team, grow an existing team to eight to ten, and then bud into two teams of four or five.
- Never create empty teams.
- Never leave managers supporting more than eight individuals.

### 2.2 - Staying on the path to high-performing teams

- A team is `falling behind` if
  - each week their backlog is longer than it was the week before. Typically, people are working extremely hard but not making much progress, morale is low, and your users are vocally dissatisfied.
  - fix:
    - To hire more people until the team moves into treading water.
    - Provide tactical support by setting expectations with users, beating the drum around the easy wins you can find, and injecting optimism.
- A team is `treading water` if
  - they’re able to get their critical work done, but are not able to start paying down technical debt or begin major new projects. Morale is a bit higher, but people are still working hard, and your users may seem happier because they’ve learned that asking for help won’t go anywhere.
  - fix:
    - To consolidate the team’s efforts to finish more things, and to reduce concurrent work until they’re able to begin repaying debt (e.g., limit work in progress).
    - Tactically, the focus here is on helping people transition from a personal view of productivity to a team view.
- A team is `repaying debt` when
  - they’re able to start paying down technical debt, and are beginning to benefit from the debt repayment snowball: each piece of debt you repay leads to more time to repay more debt.
  - fix:
    - To find space to allow the compounding value of paying down technical debt to grow.
    - Tactically try to find ways to support your users while also repaying debt, to avoid disappearing into technical debt repayment from your users’ perspective.
- A team is `innovating` when
  - their technical debt is sustainably low, morale is high, and the majority of work is satisfying new user needs.
  - "fix":
    - to maintain enough slack in your team’s schedule that the team can build quality into their work, operate continuously in innovation, and avoid backtracking.

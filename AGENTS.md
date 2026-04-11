# Project Management Approach

This project follows a hybrid Agile approach that combines Scrum and Kanban. Scrum is used at the planning level to divide the work into clear stages and define the MVP, while Kanban is used during implementation to manage small tasks continuously and keep development flexible. This is suitable for a hybrid team where both a human developer and AI agents contribute to the same repository.

The human developer is responsible for architecture, design decisions, task prioritization, code review, and final approval of all changes. AI agents are responsible for generating boilerplate code, implementing small isolated features, writing unit tests, and helping with repetitive tasks. All AI-generated work must be reviewed by the human developer before being accepted, and agents must always consult the `/docs` folder to keep project context consistent.

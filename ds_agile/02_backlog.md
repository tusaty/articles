## 2. Backlog

### 2.1 Core Stories
Each DS project represents a number of claimed deliverables. The most frequent problem is that every such project is unique due to its settings: use-cases modifications, available data, non-functional requirements. I think it's personal by I don't like to use high-level hierarchies for task settings. For me I find it more helpful to define core stories, which reflect project deliverables and project processes going on. For processes this might be some standard DS activities like education, data explorations which it's hard to put into one epic within one sprint. E.g. having such core stories allows to keep the context of the process in between tasks and track list of activities performed. I believe meanwhile this works with small or medium projects, it might be non-applicable to large projects.

### 2.2 Atomic Tasks
Each tasks being put to backlog should be atomic. This means that tasks has 2 states: either it's done or not. This should be achieved by 2 factors: task should have expiration date and clear acceptance criteria.


### 2.3 Acceptance criteria
Acceptance criteria is number of assertions about task results which don't have alternative interpretations. This means either assertion is valid or non-valid. Also there is a trick about acceptance for data-science tasks, which I like: each acceptance criteria should include
next steps definition.

TBD: Add examples


### 2.4 Lazy approach: don't invest to unclear or poorly-identified goal
TBD: Add criteria of poorly identified goal.
This item has 2 major parts: product owner defines deliverables and priorities for them.
Often something can't be started, because there is not enough data or it's not available due to legal processes. It's important to concentrate on what can be delivered at the moment based on available requirements and data. I think another option should be also available: put the project at hold, meanwhile all components are available. Otherwise data-science team end up with looking for datasets and working on assumptions probably built on irrelevant data.

### 2.5. Dividing activities onto "products" and "processes"
I prefer to sort activities in 2 buckets: products and processes. Unlike product, processes don't have clear goal and acceptance. Processes are important as they support some reoccurring activities and steps which might be not explicitly irrelevant to the project targets.
Typical background processes are education, research / experimentation.

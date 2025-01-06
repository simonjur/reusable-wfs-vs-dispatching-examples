# reusable-wfs-vs-dispatching-examples
Examples of reusable workflows and dispatch events

- reusable workflow
 - max 3 levels

![too many lvls err](./docs/wf-too-deep-error.png)

run id: https://github.com/simonjur/reusable-wfs-vs-dispatching-examples/actions/runs/12641365610

3 levels run:
https://github.com/simonjur/reusable-wfs-vs-dispatching-examples/actions/runs/12641414061

naming:
![naming](./docs/wf-3levels-naming.png)

main wf names in WF run:
![main wf names](./docs/wf-3levels-naming-main.png)

first level wf names: in WF run:
![first level wf names](./docs/wf-3levels-naming-first.png)

jobs naming:
![jobs naming](./docs/wf-3levels-naming-jobs.png)
 

- workflow dispatch
  - example with `workflow_dispatch` action 
 
- repository dispatch
  - example with command
  - example with running multiple wfs with one disaptch event

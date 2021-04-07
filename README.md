https://www.freecodecamp.org/news/how-to-set-up-continuous-integration-for-monorepo-using-buildkite/

Pre-requisites
1. Deploy the Buildkite agents.
   $docker run -it -e BUILDKITE_AGENT_TOKEN="dfde44a409272c3df9369e97f1194c047b888045d20db536f2" buildkite/agent

2. Buildkite account to create continuous integration pipelines.
3. GitHub account to host the monorepo sourcecode.

The complete source code is available in the buildkite-monorepo in GitHub.

# Teaching seven robots to play football

Site: https://velluu.github.io/robocup-t1/

ACOD310 RoboCup 3D project, October 2026. The 2026 RoboCup 3D simulation league moved to a new MuJoCo server
(rcssservermj) with the Booster T1 humanoid. This site shows the team built for it from nothing:

- three skill policies trained with reinforcement learning (movement, kick, get-up), with their inputs, rewards and
  test results in the league server
- the rule-based orchestrator that picks each robot's policy and target, and the RL orchestrator that learns
  corrections on top of it in a GPU match simulator
- a live view of one recorded half: the policy each robot runs, its role, and the RL orchestrator's inputs and outputs
- full matches against FC Portugal, magmaOffenburg, Apollo and BahiaRT, with a highlight reel of every goal

Every clip is rendered from the league server's own physics state.

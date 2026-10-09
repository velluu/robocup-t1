# Training a RoboCup team from scratch

Site: https://velluu.github.io/robocup-t1/

ACOD310 RoboCup 3D project, October 2026. The 2026 RoboCup 3D simulation league moved to a new MuJoCo server
(rcssservermj) with the Booster T1 humanoid. This site shows the team built for it from nothing:

- three skills learned with reinforcement learning in GPU physics (movement, kick, get-up), with the constraints and
  reward terms each was trained under and its tests in the league server
- the orchestrator that runs seven robots: a rules layer (roles by team-talk auction, formation, the referee's
  set-play rules) and a learned tactics layer trained by self-play in a GPU match simulator
- full matches against FC Portugal, magmaOffenburg (their Portuguese Open 2026 binaries), Apollo and BahiaRT, with a
  highlight reel of every goal

Every clip is rendered from the league server's own physics state.

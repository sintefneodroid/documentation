.. _environment_state:
.. _observer:
.. _actor:

=================
Environment State
=================

The environment_state_ encapsulates all information that should be exposed to external agents into one message. This message is comprised of observer_ s  with their relevant observational data, actor_ s with their positions and rotations in the environments, how much energy has been spent since the last reset, how many frames/time has passed since last reset and lastly a reward given by some objective function.

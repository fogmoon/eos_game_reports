# EOS Games Fairness reports

This is a set of scripts that analyze the activity of games on EOS
blockchain and produce statistical reports.

Up to now only EOSBet Dice (https://dice.eosbet.io/) is analyzed, and
corresponding reports are presented in "reports/eosbet_dice/" subfolder.

The data is generated by ZMQ Plugin for `nodeos`:
https://github.com/cc32d9/eos_zmq_plugin

The ZMQ Plugin receiver scripts are used to store all blockchain events
into a MySQL database: https://github.com/cc32d9/eos_zmq_plugin_receiver

The reports are fenerated by scripts in this repository. The date in the
report file name indicates the end of collection period. The start of the
period is always the beginning date of the whole blockchain.






## Copyright and License

Copyright 2018 cc32d9@gmail.com

https://medium.com/@cc32d9

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

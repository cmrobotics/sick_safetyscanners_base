^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package sick_safetyscanners_base
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* Merge pull request `#1 <https://github.com/cmrobotics/sick_safetyscanners_base/issues/1>`_ from cmrobotics/dont-catch-boost-thread-exceptions
  SS-947 Propagate exceptions from io thread up to main thread
* propagate exceptions from io thread up to main thread
  Don't exit silently if io thread has an exception. Allow other recoveries in ros2 like node respawn to restart the node
* Contributors: Tanmay, Tanmay Deshmukh

1.0.2 (2022-07-19)
------------------
* Added missing 'using' statement to UDPClient.cpp
* Contributors: Lennart Puck, crown-bdee

1.0.1 (2021-12-22)
------------------
* Merge fix for memory leak in command execution
* Fix memory leak in createAndExecuteCommand
* Adding multicast functionality
* Merge constant setting of field angles
* Contributors: Andrew Kooiman, Lennart Puck

1.0.0 (2021-01-11)
------------------

* Initial Release

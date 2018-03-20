# Jenkins

## master
  * schedule build jobs 
  * Dispatch builds to the slaves for the actual job execution
  * monitor the slaves and record the build results

  * can also execute build jobs directly

## slave:
  * Execute build jobs dispatched by the master
## Jobs/Project
  * Those two terms are used interchangeably. they all refer to runnable tasks that are controlled/monitored by jenkins

## Slave/Node
  * Slaves are computers that are set up to build projects for a master.

  * jenkins runs a separate program called "slave agent" on slaves.
  * when slaves are registered to a master, a master starts distributing loads to slaves
  * Node is used to refer to all machines that are part of jenkins grid,slaves and master.

## Executor
  * Executor is a separate stream of build to be run on a node in parallel 
   * A node can have one or more executors
## Build
  * A build is a result of one of the projects.
## Plugins
  * A plugin,like plugins on any other system,is a piece of software that extends the core functionality of the core jenkins server.

---
title: MoveTables
series: vtctldclient
---
## vtctldclient MoveTables

Perform commands related to moving tables from a source keyspace to a target keyspace.

### Synopsis

moveTables commands: Create, Show, Status, SwitchTraffic, ReverseTraffic, Stop, Start, Cancel, and Delete.
See the --help output for each command for more details.

### Options

```
      --format string            The format of the output; supported formats are: text,json. (default "text")
  -h, --help                     help for MoveTables
      --target-keyspace string   Target keyspace for this workflow exists (required).
  -w, --workflow string          The workflow you want to perform the command on (required).
```

### Options inherited from parent commands

```
      --action_timeout duration   timeout for the total command (default 1h0m0s)
      --server string             server to use for connection (required)
```

### SEE ALSO

* [vtctldclient](../)	 - Executes a cluster management command on the remote vtctld server.
* [vtctldclient MoveTables cancel](./vtctldclient_movetables_cancel/)	 - Cancel a MoveTables VReplication workflow.
* [vtctldclient MoveTables complete](./vtctldclient_movetables_complete/)	 - Complete a MoveTables VReplication workflow.
* [vtctldclient MoveTables create](./vtctldclient_movetables_create/)	 - Create and optionally run a moveTables VReplication workflow.
* [vtctldclient MoveTables reversetraffic](./vtctldclient_movetables_reversetraffic/)	 - Reverse traffic for a MoveTables VReplication workflow.
* [vtctldclient MoveTables show](./vtctldclient_movetables_show/)	 - Show the details for a MoveTables VReplication workflow.
* [vtctldclient MoveTables start](./vtctldclient_movetables_start/)	 - Start a MoveTables workflow.
* [vtctldclient MoveTables status](./vtctldclient_movetables_status/)	 - Show the current status for a MoveTables VReplication workflow.
* [vtctldclient MoveTables stop](./vtctldclient_movetables_stop/)	 - Stop a MoveTables workflow.
* [vtctldclient MoveTables switchtraffic](./vtctldclient_movetables_switchtraffic/)	 - Switch traffic for a MoveTables VReplication workflow.


# exp_py_trees
An experimental repo for testing the py_trees library

## Building and Running
To build the package run:
```make build_all```

To clean the workspace latest build run:
```make clean```

To run the POC system behaviour tree with the system state mocker, run:
```make run_tree_with_state```

## Manipulating the system state
To change the state of the mocker run:
```ros2 param set /system_state_mocker system_state { state_int }```

please take a look at the `SystemFlags` enum to see what states are supported
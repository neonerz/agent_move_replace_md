### @flyoutOnly true
### @hideIteration true
### @explicitHints true

# Agent Move and Replace

## Step 1
Use the ``||custom.agent move replace||`` code-block to move the Agent 3 blocks to the right and replace the block in front of it with a stone block

#### ~ tutorialhint 
This is a hint!

```ghost
agent.move()
custom.agent_move_replace()
```

```template
agent.move(FORWARD, 1)
custom.agent_move_replace(Direction.Left, 1, Direction.Forward, STONE)
```

```package
agent_move_replace_ts=github:neonerz/agent_move_replace_ts#v0.0.7
```

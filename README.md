# ktane-solver

A robot to help you solve bombs in Keep Talking and Nobody Explodes by being and expert, and it is available in your browser so you can have it open on your phone.
<br>
[Go here for the actual app](https://mrmelon54.github.io/ktane-solver/app.html)
<br>
[Go here for the developer documentation](https://mrmelon54.github.io/ktane-solver/docs.html)
<br>
[Discord server](https://discord.gg/RubcXSQ)

### Edgework Commands
```
batteries <aa/d> <number>
lit indicator <nato letters>
unlit indicator <nato letters>
remove indicator
serial number <nato letters or numbers>
port <port names (parallel/dvid/rj45/ps2/stereo/serial)>
remove port
```

The port command adds a whole portplate with those ports on it (see example below).<br>
The remove port command removes a whole portplate

This adds 2 portplates one with a Serial, Stereo RCA and PS/2 the other with just a Parallel
```
port serial stereo ps2
port parallel
```

### Help Command
```
help <module alias>
```

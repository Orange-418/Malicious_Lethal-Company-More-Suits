# This is a fork of a (somewhat randomly chosen) lethal company mod. This is not a legitimate repository. Legitimate repository can be found here: https://github.com/x753/Lethal-Company-More-Suits

This is just a simple 30 minute PoC I spun up to test how simple it is to smuggle malicious code into a popular game mod. As it turns out, it's incredibly simple, since the mods are just C# code after all. It is very very crude, but worked great. One may simply fling whatever additional code they want executed into the source, and then compile.

Many people grab mods by simply downloading the dll, throwing it into their BepinEx folder, and running the game. In this case, doing so executes an initial stage to pull down and execute a sliver beacon.

This repository is disarmed, and only contains the stub pointing at localhost. A simple b64 encoded fetch/iex command.

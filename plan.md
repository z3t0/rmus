The plan is to create a very fast, efficient and small console music player. It wil also have support for a remote interface which will allow other programs to hook into rmus to either control playback or get information. The user interface will be very similar to cmus. Also plan to support extensions / pluginsj.


for audio play back try: https://github.com/PistonDevelopers/music

portaudio works... ish
rodio doesnt

## Primary Features
- [ ] rmus-remote: this should allow external programs to interact with rmus
- [ ] keyboard bindings: should be support for native keyboard control
- [ ] play list support
- [ ] different file types: mp3, mp4a ... (TODO: extend list and create references)
- [ ] terminal user interface, TODO: figure out how to do this
- [ ] internal database for storing information, no ideas yet

## Extra Features
- [ ] scripting language, need to choose one. thinking lua cause its simple but idk
- [ ] playing from external locations, eg server


### rmus-remote
thinking of doing a simple websocket for this but will see if other options are available
- play, pause, next etc
- get playback information, eg for displaying on the desktop

